rules_version = '2';

service cloud.firestore {
  match /databases/{database}/documents {
    
    match /usuarios/{usuarioId} {
      // Só permite ler e escrever se o usuário estiver logado e for o dono dos dados
      allow read: if request.auth != null && request.auth.uid == usuarioId;
      
      // Valida se os dados enviados não estão vazios antes de salvar
      allow write: if request.auth != null 
                   && request.auth.uid == usuarioId 
                   && request.resource.data.size() > 0;
    }
    
  }
}
