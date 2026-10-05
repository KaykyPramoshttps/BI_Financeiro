📊 DASH Mini Financeiro

Mini dashboard financeiro desenvolvido em Power BI, versionado no formato PBIP (Power BI Project), que permite acompanhar os principais indicadores financeiros de forma visual, rápida e interativa.

Mostrar Imagem Mostrar Imagem Mostrar Imagem

📌 Sobre o projeto

O DASH Mini Financeiro tem como objetivo centralizar e apresentar os dados financeiros em um painel simples e objetivo, apoiando a tomada de decisão.

✏️ Edite esta seção com 2 ou 3 linhas explicando o contexto: quem usa o painel, qual problema ele resolve e de onde vêm os dados.

🖼️ Preview
<!-- Salve um print do dashboard na pasta /images e ajuste o nome abaixo -->

Mostrar Imagem

🎯 Principais indicadores (KPIs)

✏️ Ajuste conforme os indicadores que existem no seu painel.

Indicador	Descrição
💰 Receita	Total de entradas no período
💸 Despesas	Total de saídas no período
📈 Resultado / Lucro	Receita − Despesas
🧮 Margem (%)	Resultado ÷ Receita
📅 Evolução mensal	Comparativo mês a mês
🧩 Visuais do dashboard
Cartões com os KPIs principais
Gráfico de evolução mensal (linhas/colunas)
Gráfico de despesas por categoria
Tabela detalhada de lançamentos
Filtros (segmentações) por período e categoria

🛠️ Tecnologias utilizadas
Power BI Desktop (formato PBIP)
DAX – medidas e cálculos
Power Query (M) – tratamento e transformação dos dados
Git/GitHub – versionamento

🗂️ Fonte dos dados

✏️ Descreva de onde vêm os dados (planilha Excel, CSV, banco de dados, dados fictícios etc.) e, se forem fictícios, deixe isso explícito.

📐 Exemplos de medidas DAX

✏️ Substitua pelos nomes reais de tabelas e colunas do seu modelo.

dax
Receita Total = SUM(Financeiro[Receita])

Despesa Total = SUM(Financeiro[Despesa])

Resultado = [Receita Total] - [Despesa Total]

Margem % = DIVIDE([Resultado], [Receita Total], 0)
🚀 Próximos passos
 Adicionar comparativo com o ano anterior
 Incluir metas e orçamento vs. realizado
 Criar página de fluxo de caixa
 Publicar no Power BI Service
👤 Autor

SEU NOME

LinkedIn GitHub
