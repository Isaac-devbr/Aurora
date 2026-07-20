<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aurora - Finanças com Clareza</title>
    <style>
        /* --- DESIGN SISTEMA AURORA (DARK MODE CONTEXTUAL) --- */
        body {
            background-color: #0b111e;
            color: #ffffff;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            margin: 0;
            padding: 16px;
            display: flex;
            flex-direction: column;
            gap: 16px;
            box-sizing: border-box;
            min-height: 100vh;
        }

        .hidden { display: none !important; }

        /* --- TELA FLUXO AUTH / SETUP --- */
        .tela-fluxo {
            max-width: 400px;
            width: 100%;
            margin: auto;
            background: #111622;
            padding: 30px 24px;
            border-radius: 20px;
            border: 1px solid #1e293b;
            text-align: center;
            display: flex;
            flex-direction: column;
            gap: 16px;
            box-sizing: border-box;
        }

        .input-login {
            background: #0b111e;
            border: 1px solid #1e293b;
            color: white;
            padding: 12px;
            border-radius: 8px;
            font-size: 1rem;
            width: 100%;
            box-sizing: border-box;
            outline: none;
        }

        .opcoes-filhos {
            display: flex;
            gap: 10px;
            width: 100%;
        }

        .btn-opcao {
            flex: 1;
            background: #0b111e;
            border: 1px solid #1e293b;
            color: white;
            padding: 14px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.2s ease;
        }

        .btn-opcao.selecionado {
            background: #0066ff;
            border-color: #0066ff;
        }

        /* --- HEADER PRINCIPAL --- */
        #app-container {
            max-width: 480px;
            width: 100%;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 14px;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: relative;
        }

        .app-title-wrapper {
            display: flex;
            align-items: center;
            gap: 10px;
            cursor: pointer;
            position: relative;
        }

        .logo-box {
            background: #1e3a8a;
            color: #3b82f6;
            padding: 8px 12px;
            border-radius: 6px;
            font-weight: bold;
        }

        .logo-dropdown {
            position: absolute;
            top: 45px;
            left: 0;
            background: #111622;
            border: 1px solid #1e293b;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.5);
            z-index: 10;
            width: 160px;
            display: none;
        }

        .logo-dropdown button {
            background: transparent;
            border: none;
            color: #f43f5e;
            padding: 12px;
            width: 100%;
            text-align: left;
            cursor: pointer;
            font-weight: bold;
            font-size: 0.9rem;
        }

        .header-utils {
            margin-left: auto;
        }

        .btn-top-util {
            background: #111622;
            border: 1px solid #1e293b;
            color: white;
            padding: 8px 12px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 6px;
        }

        /* --- SUBHEADER PERFIL E OPÇÕES --- */
        .perfil-row {
            display: flex;
            gap: 8px;
            align-items: center;
        }

        .select-custom {
            background: #111622;
            border: 1px solid #1e293b;
            color: white;
            padding: 10px;
            border-radius: 8px;
            outline: none;
            flex: 1;
        }

        .btn-blue {
            background: #0066ff;
            color: white;
            border: none;
            padding: 10px 14px;
            border-radius: 8px;
            font-weight: bold;
            cursor: pointer;
        }

        /* --- BARRA HORIZONTAL DE MESES --- */
        .meses-scroll {
            display: flex;
            gap: 8px;
            overflow-x: auto;
            padding-bottom: 4px;
        }
        .meses-scroll::-webkit-scrollbar { height: 4px; }
        .meses-scroll::-webkit-scrollbar-thumb { background: #1e293b; border-radius: 4px; }

        .btn-mes {
            background: #111622;
            border: 1px solid #1e293b;
            color: #a0aec0;
            padding: 8px 16px;
            border-radius: 20px;
            cursor: pointer;
            white-space: nowrap;
            font-size: 0.9rem;
        }

        .btn-mes.ativo {
            background: #0066ff;
            color: white;
            border-color: #0066ff;
        }

        /* --- CARDS DE VALORES --- */
        .card-visao-geral {
            background: #111622;
            border: 1px solid #1e293b;
            border-radius: 16px;
            padding: 16px;
        }

        .card-header-row {
            display: flex;
            justify-content: space-between;
            color: #718096;
            font-size: 0.8rem;
            font-weight: bold;
            margin-bottom: 12px;
            text-transform: uppercase;
        }

        .valores-grid {
            display: flex;
            justify-content: space-between;
        }

        .v-box span {
            display: block;
            font-size: 0.75rem;
            color: #a0aec0;
            margin-bottom: 4px;
        }

        .v-box var {
            font-style: normal;
            font-size: 1.3rem;
            font-weight: bold;
            color: #0066ff;
        }

        /* --- GRÁFICO ROSCA REAL --- */
        .card-grafico {
            background: #111622;
            border: 1px solid #1e293b;
            border-radius: 16px;
            padding: 24px 16px;
            display: flex;
            align-items: center;
            justify-content: space-around;
        }

        .circle-progress {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: conic-gradient(#10b981 0% 50%, #f43f5e 50% 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            transition: background 0.3s ease;
        }

        .circle-inner {
            background: #111622;
            width: 90px;
            height: 90px;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-size: 0.75rem;
            color: #a0aec0;
            z-index: 2;
        }

        .circle-inner var {
            font-style: normal;
            font-size: 0.95rem;
            font-weight: bold;
            color: white;
            margin-top: 2px;
        }

        .grafico-legendas {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .legenda-item {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.85rem;
            color: #a0aec0;
        }

        .dot { width: 10px; height: 10px; border-radius: 50%; }
        .dot.verde { background: #10b981; }
        .dot.vermelho { background: #f43f5e; }

        .legenda-item span var {
            font-style: normal;
            display: block;
            color: white;
            font-weight: bold;
            font-size: 0.95rem;
        }

        /* --- ABAS SUB-NAVEGACAO --- */
        .sub-abas {
            display: flex;
            background: #111622;
            border: 1px solid #1e293b;
            padding: 4px;
            border-radius: 10px;
            gap: 4px;
        }

        .btn-sub-aba {
            flex: 1;
            background: transparent;
            border: none;
            color: #a0aec0;
            padding: 10px;
            cursor: pointer;
            font-weight: bold;
            border-radius: 6px;
            font-size: 0.85rem;
        }

        .btn-sub-aba.ativa {
            background: #1e293b;
            color: #0066ff;
        }

        /* --- COMPONENTES DAS PÁGINAS INTERNAS --- */
        .secao-card {
            background: #111622;
            border: 1px solid #1e293b;
            border-radius: 16px;
            padding: 16px;
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .secao-card h3 {
            margin: 0;
            font-size: 1.1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .linha-categoria {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 4px 0;
        }

        .lbl-cat {
            display: flex;
            flex-direction: column;
        }
        .lbl-cat strong { font-size: 0.95rem; }
        .lbl-cat span { font-size: 0.75rem; color: #a0aec0; }

        .input-dinheiro {
            background: #0b111e;
            border: 1px solid #1e293b;
            color: white;
            padding: 10px;
            border-radius: 8px;
            text-align: right;
            width: 110px;
            font-weight: bold;
            outline: none;
        }

        /* --- PLANILHA / TABELA DE HISTÓRICO --- */
        .tabela-wrapper {
            overflow-x: auto;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            text-align: left;
            font-size: 0.85rem;
        }
        th, td {
            padding: 10px 8px;
            border-bottom: 1px solid #1e293b;
        }
        th { color: #a0aec0; font-weight: normal; }

        /* --- SIDEBAR DE CONFIGURAÇÕES --- */
        .sidebar-config {
            position: fixed;
            top: 0;
            right: 0;
            width: 300px;
            height: 100vh;
            background: #111622;
            border-left: 1px solid #1e293b;
            box-shadow: -5px 0 25px rgba(0,0,0,0.5);
            z-index: 100;
            padding: 20px;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .sidebar-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #1e293b;
            padding-bottom: 12px;
        }

        .config-label {
            font-size: 0.8rem;
            color: #0066ff;
            font-weight: bold;
            text-transform: uppercase;
        }

        .conversor-box {
            background: #0b111e;
            border: 1px solid #1e293b;
            border-radius: 12px;
            padding: 12px;
            display: flex;
            flex-direction: column;
            gap: 8px;
        }

        .item-cambio {
            display: flex;
            justify-content: space-between;
            font-size: 0.85rem;
            padding: 4px 0;
            border-bottom: 1px solid #1e293b;
        }
        .item-cambio:last-child { border-bottom: none; }
    </style>

    <!-- CONFIGURAÇÃO DO FIREBASE -->
    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-app.js";
        import { getAuth, signInWithEmailAndPassword, createUserWithEmailAndPassword, onAuthStateChanged, signOut } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-auth.js";
        import { getFirestore, doc, setDoc, getDoc } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-firestore.js";

        const firebaseConfig = {
            apiKey: "AIzaSyCp_zRDAvgQIAs0yWlN8_zogvRAoIaZknc",
            authDomain: "aurora-1fe32.firebaseapp.com",
            projectId: "aurora-1fe32",
            storageBucket: "aurora-1fe32.firebasestorage.app",
            messagingSenderId: "954720527805",
            appId: "1:954720527805:web:281087a7b23b54e3ae9ed4",
            measurementId: "G-SKX6K3BBP9"
        };

        const app = initializeApp(firebaseConfig);
        const auth = getAuth(app);
        const db = getFirestore(app);

        window.authEnv = { 
            auth, db, doc, setDoc, getDoc, signOut,
            criarUsuario: createUserWithEmailAndPassword,
            fazerLogin: signInWithEmailAndPassword
        };
    </script>
</head>
<body>

    <!-- TELA DE AUTENTICAÇÃO -->
    <div id="tela-autenticacao" class="tela-fluxo">
        <h2 id="auth-titulo" style="color: #0066ff; margin:0;">Entrar no Aurora</h2>
        <input type="email" id="auth-email" class="input-login" placeholder="Seu e-mail">
        <input type="password" id="auth-password" class="input-login" placeholder="Sua senha">
        <button class="btn-blue" id="btn-auth-principal" onclick="executarAutenticacao()">Entrar</button>
        <button class="btn-top-util" style="border:none; margin:auto;" id="btn-auth-alternar" onclick="alternarModoAuth()">Não tem uma conta? Cadastre-se</button>
    </div>

    <!-- CONFIGURAÇÃO INICIAL DE FILHOS -->
    <div id="tela-filhos" class="tela-fluxo hidden">
        <h2>Personalize seu Horizonte</h2>
        <p style="color: #a0aec0; font-size: 0.9rem;">Você possui filhos? Ajustaremos suas categorias automaticamente.</p>
        <div class="opcoes-filhos">
            <button class="btn-opcao" id="opt-filhos-sim" onclick="selecionarOpcaoFilhos(true)">Sim</button>
            <button class="btn-opcao" id="opt-filhos-nao" onclick="selecionarOpcaoFilhos(false)">Não</button>
        </div>
        
        <div id="box-quantidade-filhos" class="hidden" style="width: 100%; margin-top: 8px;">
            <p style="font-size: 0.85rem; margin-bottom: 8px; text-align: left; color: #a0aec0;">Quantos filhos você tem?</p>
            <input type="number" id="input-qtd-filhos" class="input-login" min="1" placeholder="Ex: 2">
        </div>

        <button class="btn-blue" style="margin-top: 12px;" onclick="concluirSetupInicial()">Concluir Configuração</button>
    </div>

    <!-- CONTAINER PRINCIPAL -->
    <div id="app-container" class="hidden">
        <header>
            <div class="app-title-wrapper" onclick="toggleLogoDropdown(event)">
                <div class="logo-box">Α</div>
                <h2 style="margin:0; font-size:1.3rem;">Aurora</h2>
                <div id="logo-menu-dropdown" class="logo-dropdown">
                    <button onclick="fazerLogout()">Ir para tela inicial</button>
                </div>
            </div>
            <div class="header-utils">
                <button class="btn-top-util" onclick="alternarSidebar(true)">⚙️ Configurações</button>
            </div>
        </header>

        <!-- SELEÇÃO DE PERFIL -->
        <div class="perfil-row">
            <select class="select-custom" id="select-perfil-usuario" onchange="alterarPerfilAtivo(this.value)">
                <option value="Principal">Principal (Padrão)</option>
            </select>
            <button class="btn-blue" onclick="criarNovoPerfil()">+ Novo Perfil</button>
        </div>

        <!-- SCROLL DOS MESES -->
        <div class="meses-scroll" id="container-meses-botoes"></div>

        <!-- SUB-NAVEGAÇÃO DAS TRÊS ABAS -->
        <div class="sub-abas">
            <button class="btn-sub-aba ativa" id="sub-aba-1" onclick="mudarSubAba(1)">📊 Visão Geral</button>
            <button class="btn-sub-aba" id="sub-aba-2" onclick="mudarSubAba(2)">📋 Planilhas</button>
            <button class="btn-sub-aba" id="sub-aba-3" onclick="mudarSubAba(3)">📂 Categorias</button>
        </div>

        <!-- ABA 1: VISÃO GERAL -->
        <div id="view-visao-geral" class="sub-view-item">
            <div class="card-visao-geral">
                <div class="card-header-row">
                    <span>Visão Geral</span>
                    <span id="btn-alternar-visibilidade" style="color:#0066ff; cursor:pointer;" onclick="alternarVisibilidadeSaldos()">👁️ Ocultar</span>
                </div>
                <div class="valores-grid">
                    <div class="v-box">
                        <span>SALDO ANTERIOR</span>
                        <var id="txt-saldo-anterior" style="color: #a0aec0;">R$ 0,00</var>
                    </div>
                    <div class="v-box" style="text-align: right;">
                        <span>NOVO SALDO FINAL</span>
                        <var id="txt-novo-saldo-final">R$ 0,00</var>
                    </div>
                </div>
            </div>

            <div class="card-grafico" style="margin-top:12px;">
                <div class="circle-progress" id="grafico-circular">
                    <div class="circle-inner">
                        <span>Balanço</span>
                        <var id="txt-grafico-sobrou">R$ 0,00</var>
                        <span id="txt-grafico-porcentagem">0%</span>
                    </div>
                </div>
                <div class="grafico-legendas">
                    <div class="legenda-item">
                        <div class="dot verde"></div>
                        <span>Entradas <var id="legenda-sobrou-porcento">0%</var></span>
                    </div>
                    <div class="legenda-item">
                        <div class="dot vermelho"></div>
                        <span>Saídas <var id="legenda-despesas-porcento">0%</var></span>
                    </div>
                </div>
            </div>

            <div class="secao-card" style="margin-top:12px;">
                <h3>💸 Movimentação de Saldos</h3>
                <div style="display: flex; gap:8px;">
                    <input type="date" id="mov-data" class="select-custom" style="flex:unset; width:130px;">
                    <select id="mov-tipo" class="select-custom">
                        <option value="entrada">Entrada (+)</option>
                        <option value="saida">Saída (-)</option>
                    </select>
                </div>
                <input type="text" id="mov-descricao" class="input-login" placeholder="Descrição">
                <div style="display:flex; gap:8px;">
                    <input type="number" id="mov-valor" class="input-login" placeholder="Valor (0.00)">
                    <button class="btn-blue" onclick="adicionarMovimentacao()">Lançar</button>
                </div>
            </div>
        </div>

        <!-- ABA 2: PLANILHAS (EXTRATO) -->
        <div id="view-planilhas" class="sub-view-item hidden">
            <div class="secao-card">
                <h3>📑 Histórico de Lançamentos</h3>
                <div class="tabela-wrapper">
                    <table>
                        <thead>
                            <tr>
                                <th>Data</th>
                                <th>Descrição</th>
                                <th>Tipo</th>
                                <th>Valor</th>
                            </tr>
                        </thead>
                        <tbody id="tabela-corpo-historico"></tbody>
                    </table>
                </div>
            </div>
        </div>

        <!-- ABA 3: CATEGORIAS DO MÊS -->
        <div id="view-categorias" class="sub-view-item hidden">
            <div class="secao-card">
                <h3>📝 Categorias do Mês</h3>
                
                <span style="color:#10b981; font-size:0.8rem; font-weight:bold;">ENTRADAS</span>
                <div class="linha-categoria">
                    <div class="lbl-cat"><strong>Salário</strong><span>Rendimento mensal</span></div>
                    <input type="text" id="cat-salario" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('salario', this.value)">
                </div>
                <div class="linha-categoria">
                    <div class="lbl-cat"><strong>Investimentos</strong><span>Dividendos e rendimentos</span></div>
                    <input type="text" id="cat-investimentos" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('investimentos', this.value)">
                </div>
                <div class="linha-categoria">
                    <div class="lbl-cat"><strong>Freelance / Extras</strong><span>Trabalhos esporádicos</span></div>
                    <input type="text" id="cat-freelance" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('freelance', this.value)">
                </div>

                <span style="color:#f43f5e; font-size:0.8rem; font-weight:bold; margin-top:8px; display:block;">SAÍDAS</span>
                <div class="linha-categoria">
                    <div class="lbl-cat"><strong>Mercado</strong><span>Compras do mês</span></div>
                    <input type="text" id="cat-mercado" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('mercado', this.value)">
                </div>
                <div class="linha-categoria">
                    <div class="lbl-cat"><strong>Contas Fixas</strong><span>Água, Luz, Aluguel</span></div>
                    <input type="text" id="cat-contas" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('contas', this.value)">
                </div>
                <div class="linha-categoria">
                    <div class="lbl-cat"><strong>Alimentação fora</strong><span>Restaurantes e Delivery</span></div>
                    <input type="text" id="cat-delivery" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('delivery', this.value)">
                </div>
                <div class="linha-categoria">
                    <div class="lbl-cat"><strong>Lazer e Viagens</strong><span>Cinema, passeios e férias</span></div>
                    <input type="text" id="cat-lazer" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('lazer', this.value)">
                </div>
                <div class="linha-categoria">
                    <div class="lbl-cat"><strong>Streaming</strong><span>Netflix, Spotify, etc.</span></div>
                    <input type="text" id="cat-streaming" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('streaming', this.value)">
                </div>
                <div class="linha-categoria">
                    <div class="lbl-cat"><strong>Transporte</strong><span>Uber, ônibus ou metrô</span></div>
                    <input type="text" id="cat-transporte" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('transporte', this.value)">
                </div>

                <!-- CATEGORIA OBRIGATÓRIA DINÂMICA DE FILHOS -->
                <div id="cat-box-filhos" class="hidden">
                    <div class="linha-categoria">
                        <div class="lbl-cat"><strong>Escola</strong><span id="txt-desc-filhos">Educação do(s) filho(s)</span></div>
                        <input type="text" id="cat-escola" class="input-dinheiro" value="0,00" oninput="salvarCategoriaInput('escola', this.value)">
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- SIDEBAR CONFIGURAÇÕES -->
    <div id="sidebar-config" class="sidebar-config hidden">
        <div class="sidebar-header">
            <h3 style="margin:0;">Configurações</h3>
            <button class="btn-top-util" onclick="alternarSidebar(false)">✕</button>
        </div>
        <div>
            <span class="config-label">Selecione o Ano</span>
            <!-- Removidas as tags manuais. Agora o JS popula dinamicamente -->
            <select class="select-custom" id="cfg-ano" style="width:100%; margin-top:6px;" onchange="mudarAnoCalendario(this.value)"></select>
        </div>
        <div>
            <span class="config-label">Moeda Principal</span>
            <select class="select-custom" id="cfg-moeda" style="width:100%; margin-top:6px;" onchange="alterarMoedaBase(this.value)">
                <option value="BRL">Real (BRL)</option>
                <option value="USD">Dólar (USD)</option>
                <option value="EUR">Euro (EUR)</option>
                <option value="GBP">Libra (GBP)</option>
                <option value="CHF">Franco Suíço (CHF)</option>
            </select>
        </div>
        <div>
            <span class="config-label">Conversor de Câmbio</span>
            <div class="conversor-box" style="margin-top:6px;">
                <input type="number" id="conv-valor-base" class="input-login" value="1.00" oninput="calcularConversorCambio(this.value)">
                <select class="select-custom" id="conv-moeda-origem" onchange="calcularConversorCambio()">
                    <option value="USD">De: Dólar (USD)</option>
                    <option value="BRL">De: Real (BRL)</option>
                    <option value="EUR">De: Euro (EUR)</option>
                    <option value="GBP">De: Libra (GBP)</option>
                    <option value="CHF">De: Franco Suíço (CHF)</option>
                </select>
                <div id="lista-cambio-valores" style="margin-top:8px;"></div>
            </div>
        </div>
        <button class="btn-top-util" style="color:#f43f5e; border-color:#f43f5e; margin-top:auto;" onclick="fazerLogout()">Sair da Conta 🚪</button>
    </div>

    <script>
        let modoCadastro = false;
        let usuarioAtualId = null;
        let saldosOcultados = false;
        
        let appState = {
            anoCorrente: new Date().getFullYear().toString(),
            mesCorrente: new Date().getMonth(),
            moedaCorrente: "BRL",
            perfilCorrente: "Principal",
            perfisCadastrados: ["Principal"],
            possuiFilhos: undefined,
            qtdFilhos: 0,
            dadosFinanceiros: {}
        };

        const mesesNomes = ["Janeiro", "Fevereiro", "Março", "Abril", "Maio", "Junho", "Julho", "Agosto", "Setembro", "Outubro", "Novembro", "Dezembro"];
        const simbolosMoedas = { BRL: "R$", USD: "$", EUR: "€", GBP: "£", CHF: "CHF" };
        
        const taxasCambioFixas = {
            USD: { BRL: 5.15, EUR: 0.92, GBP: 0.78, CHF: 0.89, USD: 1 },
            BRL: { BRL: 1, EUR: 0.18, GBP: 0.15, CHF: 0.17, USD: 0.19 },
            EUR: { BRL: 5.60, EUR: 1, GBP: 0.85, CHF: 0.97, USD: 1.09 },
            GBP: { BRL: 6.60, EUR: 1.18, GBP: 1, CHF: 1.14, USD: 1.28 },
            CHF: { BRL: 5.78, EUR: 1.03, GBP: 0.88, CHF: 1, USD: 1.12 }
        };

        // GERAÇÃO AUTOMÁTICA DOS ANOS NO SELECT
        function inicializarSelectAnos() {
            const selectAno = document.getElementById('cfg-ano');
            selectAno.innerHTML = "";
            const anoAtualNum = new Date().getFullYear();
            
            // Cria um range fixo e confortável: 1 ano atrás até 10 anos no futuro
            const anoInicial = 2025; 
            const anoFinal = anoAtualNum + 10;

            for (let ano = anoInicial; ano <= anoFinal; ano++) {
                const opt = document.createElement('option');
                opt.value = ano.toString();
                opt.innerText = ano.toString();
                if(ano.toString() === appState.anoCorrente) opt.selected = true;
                selectAno.appendChild(opt);
            }
        }

        function toggleLogoDropdown(event) {
            event.stopPropagation();
            const dropdown = document.getElementById('logo-menu-dropdown');
            dropdown.style.display = dropdown.style.display === 'block' ? 'none' : 'block';
        }

        document.addEventListener('click', () => {
            document.getElementById('logo-menu-dropdown').style.display = 'none';
        });

        function alternarModoAuth() {
            modoCadastro = !modoCadastro;
            document.getElementById('auth-titulo').innerText = modoCadastro ? "Cadastrar no Aurora" : "Entrar no Aurora";
            document.getElementById('btn-auth-principal').innerText = modoCadastro ? "Cadastrar" : "Entrar";
            document.getElementById('btn-auth-alternar').innerText = modoCadastro ? "Já tem conta? Faça Login" : "Não tem uma conta? Cadastre-se";
        }

        async function ejecutarAutenticacao() {
            const email = document.getElementById('auth-email').value;
            const password = document.getElementById('auth-password').value;
            if (!email || !password) return alert("Preencha os campos!");
            try {
                if (modoCadastro) {
                    await window.authEnv.criarUsuario(window.authEnv.auth, email, password);
                } else {
                    await window.authEnv.fazerLogin(window.authEnv.auth, email, password);
                }
            } catch (e) { alert("Erro: " + e.message); }
        }

        document.addEventListener("DOMContentLoaded", () => {
            document.getElementById('mov-data').valueAsDate = new Date();
            const verificarAuth = setInterval(() => {
                if (window.authEnv && window.authEnv.auth) {
                    clearInterval(verificarAuth);
                    window.authEnv.auth.onAuthStateChanged(async (user) => {
                        if (user) {
                            usuarioAtualId = user.uid;
                            document.getElementById('tela-autenticacao').classList.add('hidden');
                            
                            const docRef = window.authEnv.doc(window.authEnv.db, "usuarios", usuarioAtualId);
                            const docSnap = await window.authEnv.getDoc(docRef);

                            if (docSnap.exists()) {
                                appState = { ...appState, ...docSnap.data() };
                                if(!appState.perfisCadastrados) appState.perfisCadastrados = ["Principal"];
                                if(!appState.perfilCorrente) appState.perfilCorrente = "Principal";
                                atualizarSelectPerfis();
                                inicializarSelectAnos();
                                renderizarMesesBotoes();
                                abrirAppPrincipal();
                            } else {
                                document.getElementById('tela-filhos').classList.remove('hidden');
                            }
                        } else {
                            document.getElementById('app-container').classList.add('hidden');
                            document.getElementById('tela-autenticacao').classList.remove('hidden');
                        }
                    });
                }
            }, 500);
            calcularConversorCambio();
        });

        function selecionarOpcaoFilhos(opcao) {
            appState.possuiFilhos = opcao;
            document.getElementById('opt-filhos-sim').classList.toggle('selecionado', opcao === true);
            document.getElementById('opt-filhos-nao').classList.toggle('selecionado', opcao === false);
            
            const boxQtd = document.getElementById('box-quantidade-filhos');
            if (opcao === true) {
                boxQtd.classList.remove('hidden');
            } else {
                boxQtd.classList.add('hidden');
                document.getElementById('input-qtd-filhos').value = "";
                appState.qtdFilhos = 0;
            }
        }

        async function concluirSetupInicial() {
            if (appState.possuiFilhos === undefined) return alert("Selecione uma opção!");

            if (appState.possuiFilhos === true) {
                const qtd = parseInt(document.getElementById('input-qtd-filhos').value);
                if (isNaN(qtd) || qtd <= 0) return alert("Insira uma quantidade válida de filhos!");
                appState.qtdFilhos = qtd;
            }

            document.getElementById('tela-filhos').classList.add('hidden');
            appState.perfisCadastrados = ["Principal"];
            appState.perfilCorrente = "Principal";
            atualizarSelectPerfis();
            inicializarSelectAnos();
            renderizarMesesBotoes();
            abrirAppPrincipal();
            salvarDadosNoCloud();
        }

        function criarNovoPerfil() {
            const nomePerfil = prompt("Digite o nome do novo perfil:");
            if (!nomePerfil || nomePerfil.trim() === "") return;
            const nomeFormatado = nomePerfil.trim();
            if (appState.perfisCadastrados.includes(nomeFormatado)) return alert("Este perfil já existe.");
            
            appState.perfisCadastrados.push(nomeFormatado);
            appState.perfilCorrente = nomeFormatado;
            atualizarSelectPerfis();
            processarLógicaFinanceiraMês();
            salvarDadosNoCloud();
        }

        function atualizarSelectPerfis() {
            const select = document.getElementById('select-perfil-usuario');
            select.innerHTML = "";
            appState.perfisCadastrados.forEach(p => {
                const opt = document.createElement('option');
                opt.value = p;
                opt.innerText = p === "Principal" ? "Principal (Padrão)" : p;
                if(p === appState.perfilCorrente) opt.selected = true;
                select.appendChild(opt);
            });
        }

        function alterarPerfilAtivo(novoPerfil) {
            appState.perfilCorrente = novoPerfil;
            processarLógicaFinanceiraMês();
            salvarDadosNoCloud();
        }

        function renderizarMesesBotoes() {
            const container = document.getElementById('container-meses-botoes');
            container.innerHTML = "";
            mesesNomes.forEach((nome, index) => {
                const btn = document.createElement('button');
                btn.className = `btn-mes ${index === appState.mesCorrente ? 'ativo' : ''}`;
                btn.innerText = nome;
                btn.onclick = () => mudarMesAtivo(index);
                container.appendChild(btn);
            });
        }

        function mudarMesAtivo(indexMes) {
            appState.mesCorrente = indexMes;
            renderizarMesesBotoes();
            processarLógicaFinanceiraMês();
        }

        function abrirAppPrincipal() {
            document.getElementById('app-container').classList.remove('hidden');
            const catBoxFilhos = document.getElementById('cat-box-filhos');
            if (appState.possuiFilhos && appState.qtdFilhos > 0) {
                catBoxFilhos.classList.remove('hidden');
                document.getElementById('txt-desc-filhos').innerText = `Educação de ${appState.qtdFilhos} filho(s)`;
            } else {
                catBoxFilhos.classList.add('hidden');
            }
            document.getElementById('cfg-moeda').value = appState.moedaCorrente;
            document.getElementById('cfg-ano').value = appState.anoCorrente;
            processarLógicaFinanceiraMês();
        }

        function mudarSubAba(abaId) {
            document.querySelectorAll('.btn-sub-aba').forEach(b => b.classList.remove('ativa'));
            document.querySelectorAll('.sub-view-item').forEach(v => v.classList.add('hidden'));
            document.getElementById(`sub-aba-${abaId}`).classList.add('ativa');
            if(abaId === 1) document.getElementById('view-visao-geral').classList.remove('hidden');
            if(abaId === 2) document.getElementById('view-planilhas').classList.remove('hidden');
            if(abaId === 3) document.getElementById('view-categorias').classList.remove('hidden');
        }

        function alternarSidebar(abrir) {
            if(abrir) document.getElementById('sidebar-config').classList.remove('hidden');
            else document.getElementById('sidebar-config').classList.add('hidden');
        }

        function alternarVisibilidadeSaldos() {
            saldosOcultados = !saldosOcultados;
            const btn = document.getElementById('btn-alternar-visibilidade');
            btn.innerText = saldosOcultados ? "👁️ Mostrar" : "👁️ Ocultar";
            processarLógicaFinanceiraMês();
        }

        function obterDadosMes(perfil, ano, mesIdx) {
            if (!appState.dadosFinanceiros) appState.dadosFinanceiros = {};
            if (!appState.dadosFinanceiros[perfil]) appState.dadosFinanceiros[perfil] = {};
            if (!appState.dadosFinanceiros[perfil][ano]) appState.dadosFinanceiros[perfil][ano] = {};
            if (!appState.dadosFinanceiros[perfil][ano][mesIdx]) {
                appState.dadosFinanceiros[perfil][ano][mesIdx] = {
                    categorias: { salario: 0, investimentos: 0, freelance: 0, mercado: 0, contas: 0, delivery: 0, lazer: 0, streaming: 0, transporte: 0, escola: 0 },
                    movimentacoes: []
                };
            }
            return appState.dadosFinanceiros[perfil][ano][mesIdx];
        }

        // LÓGICA DE CÁLCULO DE SALDO ANTERIOR ULTRA CONTÍNUA (IGNORA LACUNAS DE ANOS)
        function calcularSaldoAnteriorMês(perfilAlvo, anoAlvo, mesAlvoIdx) {
            let saldoAcumulado = 0;
            
            // Coleta todos os anos que existem no banco, junta com o ano atual selecionado e ordena
            let todosAnosValidos = Object.keys(appState.dadosFinanceiros[perfilAlvo] || {});
            if(!todosAnosValidos.includes(anoAlvo)) todosAnosValidos.push(anoAlvo);
            todosAnosValidos.sort((a,b) => parseInt(a) - parseInt(b));
            
            for (let ano of todosAnosValidos) {
                if (parseInt(ano) > parseInt(anoAlvo)) break;
                
                let limiteMes = (ano === anoAlvo) ? mesAlvoIdx : 12;
                for (let m = 0; m < limiteMes; m++) {
                    if (!appState.dadosFinanceiros[perfilAlvo][ano] || !appState.dadosFinanceiros[perfilAlvo][ano][m]) continue;
                    let dados = appState.dadosFinanceiros[perfilAlvo][ano][m];
                    
                    let entradas = parseFloat(dados.categorias.salario || 0) + parseFloat(dados.categorias.investimentos || 0) + parseFloat(dados.categorias.freelance || 0);
                    let saidas = parseFloat(dados.categorias.mercado || 0) + parseFloat(dados.categorias.contas || 0) + 
                                 parseFloat(dados.categorias.delivery || 0) + parseFloat(dados.categorias.lazer || 0) + 
                                 parseFloat(dados.categorias.streaming || 0) + parseFloat(dados.categorias.transporte || 0) + 
                                 (appState.possuiFilhos ? parseFloat(dados.categorias.escola || 0) : 0);
                    
                    dados.movimentacoes.forEach(mov => {
                        if(mov.tipo === 'entrada') entradas += parseFloat(mov.valor);
                        else saidas += parseFloat(mov.valor);
                    });
                    saldoAcumulado += (entradas - saidas);
                }
            }
            return saldoAcumulado;
        }

        function processarLógicaFinanceiraMês() {
            const dadosMês = obterDadosMes(appState.perfilCorrente, appState.anoCorrente, appState.mesCorrente);
            const saldoAnterior = calcularSaldoAnteriorMês(appState.perfilCorrente, appState.anoCorrente, appState.mesCorrente);
            
            document.getElementById('cat-salario').value = formatarInput(dadosMês.categorias.salario);
            document.getElementById('cat-investimentos').value = formatarInput(dadosMês.categorias.investimentos);
            document.getElementById('cat-freelance').value = formatarInput(dadosMês.categorias.freelance);
            document.getElementById('cat-mercado').value = formatarInput(dadosMês.categorias.mercado);
            document.getElementById('cat-contas').value = formatarInput(dadosMês.categorias.contas);
            document.getElementById('cat-delivery').value = formatarInput(dadosMês.categorias.delivery);
            document.getElementById('cat-lazer').value = formatarInput(dadosMês.categorias.lazer);
            document.getElementById('cat-streaming').value = formatarInput(dadosMês.categorias.streaming);
            document.getElementById('cat-transporte').value = formatarInput(dadosMês.categorias.transporte);
            document.getElementById('cat-escola').value = formatarInput(dadosMês.categorias.escola);

            let despesasCategorias = parseFloat(dadosMês.categorias.mercado || 0) + 
                                     parseFloat(dadosMês.categorias.contas || 0) + 
                                     parseFloat(dadosMês.categorias.delivery || 0) + 
                                     parseFloat(dadosMês.categorias.lazer || 0) + 
                                     parseFloat(dadosMês.categorias.streaming || 0) + 
                                     parseFloat(dadosMês.categorias.transporte || 0) + 
                                     (appState.possuiFilhos ? parseFloat(dadosMês.categorias.escola || 0) : 0);
            
            let receitasTotais = parseFloat(dadosMês.categorias.salario || 0) + parseFloat(dadosMês.categorias.investimentos || 0) + parseFloat(dadosMês.categorias.freelance || 0);

            const tabelaCorpo = document.getElementById('tabela-corpo-historico');
            tabelaCorpo.innerHTML = "";

            dadosMês.movimentacoes.forEach(mov => {
                if(mov.tipo === 'entrada') receitasTotais += parseFloat(mov.valor);
                else despesasCategorias += parseFloat(mov.valor);

                let tr = document.createElement('tr');
                tr.innerHTML = `<td>${mov.data}</td><td>${mov.descricao}</td><td>${mov.tipo === 'entrada' ? 'Entrada' : 'Saída'}</td><td style="color:${mov.tipo === 'entrada' ? '#10b981':'#f43f5e'}">${simbolosMoedas[appState.moedaCorrente]} ${parseFloat(mov.valor).toFixed(2)}</td>`;
                tabelaCorpo.appendChild(tr);
            });

            const novoSaldoFinal = saldoAnterior + receitasTotais - despesasCategorias;
            const sobrouLiquido = receitasTotais - despesasCategorias;

            if (saldosOcultados) {
                document.getElementById('txt-saldo-anterior').innerText = "••••••";
                document.getElementById('txt-novo-saldo-final').innerText = "••••••";
                document.getElementById('txt-novo-saldo-final').style.color = "#ffffff";
                document.getElementById('txt-grafico-sobrou').innerText = "••••••";
            } else {
                document.getElementById('txt-saldo-anterior').innerText = `${simbolosMoedas[appState.moedaCorrente]} ${saldoAnterior.toFixed(2)}`;
                const txtFinal = document.getElementById('txt-novo-saldo-final');
                txtFinal.innerText = `${simbolosMoedas[appState.moedaCorrente]} ${novoSaldoFinal.toFixed(2)}`;
                txtFinal.style.color = novoSaldoFinal >= 0 ? '#10b981' : '#f43f5e';
                document.getElementById('txt-grafico-sobrou').innerText = `${simbolosMoedas[appState.moedaCorrente]} ${sobrouLiquido.toFixed(2)}`;
            }

            let porcReceitas = 0, porcDespesas = 0;
            const totalMovimentado = receitasTotais + despesasCategorias;
            
            if (totalMovimentado > 0) {
                porcReceitas = Math.round((receitasTotais / totalMovimentado) * 100);
                porcDespesas = 100 - porcReceitas;
            }

            document.getElementById('txt-grafico-porcentagem').innerText = totalMovimentado > 0 ? `${porcReceitas}%` : '0%';
            document.getElementById('legenda-sobrou-porcento').innerText = `${porcReceitas}%`;
            document.getElementById('legenda-despesas-porcento').innerText = `${porcDespesas}%`;
            
            const graficoCircular = document.getElementById('grafico-circular');
            if (totalMovimentado > 0) {
                graficoCircular.style.background = `conic-gradient(#10b981 0% ${porcReceitas}%, #f43f5e ${porcReceitas}% 100%)`;
            } else {
                graficoCircular.style.background = `conic-gradient(#1e293b 0% 100%)`;
            }
            calcularConversorCambio();
        }

        function salvarCategoriaInput(chave, valorRaw) {
            let valorLimpo = parseFloat(valorRaw.replace(/\./g, '').replace(',', '.')) || 0;
            const dadosMês = obterDadosMes(appState.perfilCorrente, appState.anoCorrente, appState.mesCorrente);
            dadosMês.categorias[chave] = valorLimpo;
            processarLógicaFinanceiraMês();
            salvarDadosNoCloud();
        }

        function adicionarMovimentacao() {
            const data = document.getElementById('mov-data').value;
            const tipo = document.getElementById('mov-tipo').value;
            const descricao = document.getElementById('mov-descricao').value;
            const valor = parseFloat(document.getElementById('mov-valor').value) || 0;

            if(!descricao || valor <= 0) return alert("Preencha corretamente!");

            const dadosMês = obterDadosMes(appState.perfilCorrente, appState.anoCorrente, appState.mesCorrente);
            dadosMês.movimentacoes.push({ data, tipo, descricao, valor });

            document.getElementById('mov-descricao').value = "";
            document.getElementById('mov-valor').value = "";

            processarLógicaFinanceiraMês();
            salvarDadosNoCloud();
        }

        function formatarInput(num) {
            if(!num) return "0,00";
            return parseFloat(num).toLocaleString('pt-BR', { minimumFractionDigits: 2 });
        }

        function alterarMoedaBase(novaMoeda) {
            appState.moedaCorrente = novaMoeda;
            processarLógicaFinanceiraMês();
            salvarDadosNoCloud();
        }

        function mudarAnoCalendario(novoAno) {
            appState.anoCorrente = novoAno;
            processarLógicaFinanceiraMês();
            salvarDadosNoCloud();
        }

        function calcularConversorCambio() {
            const valBase = parseFloat(document.getElementById('conv-valor-base').value) || 1;
            const deMoeda = document.getElementById('conv-moeda-origem').value;
            const boxValores = document.getElementById('lista-cambio-valores');
            if(!boxValores) return;
            boxValores.innerHTML = "";

            Object.keys(simbolosMoedas).forEach(m => {
                if(m === deMoeda) return;
                const variacaoRealTime = 1 + (Math.random() * 0.004 - 0.002); 
                let taxa = (taxasCambioFixas[deMoeda][m] || 1) * variacaoRealTime;
                let convertido = valBase * taxa;
                
                let div = document.createElement('div');
                div.className = "item-cambio";
                div.innerHTML = `<span>${m} (${simbolosMoedas[m]})</span><strong>${simbolosMoedas[m]} ${convertido.toFixed(2)}</strong>`;
                boxValores.appendChild(div);
            });
        }

        async function salvarDadosNoCloud() {
            if (usuarioAtualId && window.authEnv) {
                try {
                    await window.authEnv.setDoc(window.authEnv.doc(window.authEnv.db, "usuarios", usuarioAtualId), appState);
                } catch (e) { console.error(e); }
            }
        }

        function fazerLogout() { 
            if(window.authEnv && window.authEnv.signOut) {
                window.authEnv.signOut(window.authEnv.auth); 
            }
        }
    </script>
</body>
</html>