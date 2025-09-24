<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Morretes e Turismo</title>
    <!-- Fonte moderna -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        /* ===== RESET ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', Arial, sans-serif;
            background: #eef5f1;
            color: #333;
            line-height: 1.7;
            padding: 20px;
        }

        h1, h2, h3 {
            color: #2a7d46;
            margin-bottom: 15px;
        }

        h1 { font-size: 2em; }
        h2 { font-size: 1.6em; margin-top: 25px; }
        h3 { font-size: 1.3em; margin-top: 20px; }

        p, li { font-size: 16px; margin-bottom: 10px; }

        .highlight {
            color: #2a7d46;
            font-weight: 500;
        }

        .card {
            background: linear-gradient(145deg, #ffffff, #f0f8f4);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.12);
            margin-bottom: 25px;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 25px rgba(0,0,0,0.18);
        }

        ul, ul.step-list {
            margin-left: 20px;
        }

        ul li { margin-bottom: 8px; }

        ul.step-list { list-style-type: decimal; }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
            font-size: 15px;
        }

        th, td {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: left;
        }

        th {
            background: #2a7d46;
            color: white;
            font-weight: 500;
        }

        tr:nth-child(even) { background: #eaf7ef; }

        /* ===== RESPONSIVIDADE ===== */
        @media (max-width: 768px) {
            body { padding: 15px; }
            h1 { font-size: 1.8em; }
            h2 { font-size: 1.4em; }
            h3 { font-size: 1.2em; }
            p, li { font-size: 15px; }
            table, th, td { font-size: 14px; }
        }

        @media (max-width: 480px) {
            h1 { font-size: 1.5em; }
            h2 { font-size: 1.2em; }
            h3 { font-size: 1.1em; }
            p, li { font-size: 14px; }
            table, th, td { font-size: 13px; }
            .card { padding: 15px; }
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Por que os turistas ficam só 3,5 horas em Morretes?</h1>
        <p>
            Morretes é uma cidade histórica do Paraná, conhecida pelo famoso <span class="highlight">barreado</span> e pelo passeio de trem. 
            A maioria dos visitantes chega em passeios de um dia, geralmente vindos de Curitiba, 
            permanecendo em média apenas <span class="highlight">3,5 horas</span> na cidade.
        </p>
        <p>
            Esse tempo curto acontece porque os turistas descem do trem, passeiam rapidamente pelo centro, 
            almoçam o barreado e já retornam no mesmo dia. Assim, muitas atrações naturais e culturais 
            acabam ficando de fora da experiência.
        </p>
    </div>

    <div class="card">
        <h2>Soluções para aumentar o tempo de permanência</h2>
        <ul>
            <li>Divulgação de roteiros completos com trilhas, cachoeiras e passeios no rio Nhundiaquara.</li>
            <li>Eventos culturais: festivais, feiras de artesanato e música local.</li>
            <li>Hospedagem acessível e incentivo ao pernoite.</li>
            <li>Turismo de experiência: oficinas de barreado, degustação de produtos locais e visitas guiadas.</li>
            <li>Integração regional com Antonina e Parque Estadual do Marumbi.</li>
        </ul>
    </div>

    <div class="card">
        <h2>Iniciativas Relacionadas</h2>
        <table>
            <tr>
                <th>Área</th>
                <th>Problema</th>
                <th>Solução</th>
                <th>Local</th>
            </tr>
            <tr>
                <td>Turismo</td>
                <td>Baixo tempo de permanência: 3,5 horas</td>
                <td>Marketplace para as empresas locais venderem e divulgarem seus produtos</td>
                <td>Morretes</td>
            </tr>
            <tr>
                <td>Educação / Negócios</td>
                <td>Necessidade de digitalização</td>
                <td>Criar KPIs de negócio para estimar a digitalização de X% com os alunos da rede pública</td>
                <td>Morretes</td>
            </tr>
        </table>
    </div>

    <div class="card">
        <h2>Detalhamento das Soluções</h2>
        <h3>📌 Marketplace para empresas locais</h3>
        <ul>
            <li>Dar visibilidade a produtos típicos (barreado, cachaças, artesanato, doces e compotas).</li>
            <li>Gerar renda extra para empreendedores locais.</li>
            <li>Manter o vínculo do turista com Morretes mesmo após a visita.</li>
            <li>Criar promoções integradas (ex: pacote "experiência + produto local").</li>
        </ul>

        <h3>📊 KPIs de Digitalização dos Alunos da Rede Pública</h3>
        <ul>
            <li><span class="highlight">Percentual de alunos capacitados</span> em atividades digitais (ex: oficinas, cursos e workshops).</li>
            <li><span class="highlight">Número de alunos engajados</span> nas ações de digitalização.</li>
            <li><span class="highlight">% de conclusão dos treinamentos digitais</span> pelos alunos.</li>
            <li><span class="highlight">Participação em projetos práticos</span> ligados ao marketplace ou ferramentas digitais.</li>
            <li><span class="highlight">% de alunos que aplicam o aprendizado</span> em ações concretas na comunidade ou escola.</li>
        </ul>
    </div>

    <div class="card">
        <h2>Passo a Passo Prático no Odoo</h2>
        <ul class="step-list">
            <li>Instalar o Odoo e criar banco de dados.</li>
            <li>Ativar módulos: Website, CRM, Vendas, Projetos, Dashboard, Marketing.</li>
            <li>Criar Marketplace de produtos típicos.</li>
            <li>Configurar KPIs e dashboards para digitalização.</li>
            <li>Marketing e divulgação digital.</li>
            <li>Gerar relatórios e monitorar resultados.</li>
        </ul>
        
        <h3>1️⃣ Configuração Inicial</h3>
        <ul class="step-list">
            <li>Instalar o Odoo e criar um banco de dados para o projeto.</li>
            <li>Ativar módulos necessários:
                <ul>
                    <li>Website & eCommerce</li>
                    <li>CRM</li>
                    <li>Sales / Vendas</li>
                    <li>Project / Projetos</li>
                    <li>Spreadsheet & Dashboard</li>
                    <li>Marketing Automation</li>
                </ul>
            </li>
        </ul>

        <h3>2️⃣ Criando o Marketplace</h3>
        <ul class="step-list">
            <li>Website → Criar página “Morretes Marketplace”.</li>
            <li>Website → Produtos → Cadastrar produtos típicos (barreado, cachaças, artesanato, doces).</li>
            <li>Website → Configurar pagamento e entrega.</li>
            <li>CRM → Acompanhar turistas e clientes interessados.</li>
        </ul>

        <h3>3️⃣ Criando KPIs de Digitalização</h3>
        <ul class="step-list">
            <li>Project → Criar projeto “Digitalização em Morretes” e tarefas:
                <ul>
                    <li>Cadastrar empresas no marketplace</li>
                    <li>Capacitar alunos da rede pública</li>
                    <li>Divulgar eventos e produtos</li>
                </ul>
            </li>
            <li>Spreadsheet / Dashboard → Criar indicadores:
                <ul>
                    <li>Número de empresas cadastradas</li>
                    <li>Volume de vendas online</li>
                    <li>Tempo médio de permanência dos turistas</li>
                    <li>% de turistas que retornam</li>
                    <li>Engajamento dos alunos em oficinas</li>
                </ul>
            </li>
        </ul>

        <h3>4️⃣ Marketing e Divulgação</h3>
        <ul class="step-list">
            <li>Marketing Automation → Criar campanhas para divulgar produtos e experiências.</li>
            <li>Enviar promoções integradas para turistas e leads.</li>
        </ul>

        <h3>5️⃣ Relatórios e Dashboards</h3>
        <ul class="step-list">
            <li>Monitorar vendas, engajamento do marketplace e tempo de permanência.</li>
            <li>Gerar relatórios periódicos para avaliação do impacto das ações.</li>
        </ul>
    </div>
</body>
</html>
