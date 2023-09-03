README - Dashboard de Vendas
Este é um repositório contendo um aplicativo Streamlit para criação de um Dashboard de Vendas. O aplicativo permite a visualização de dados de vendas a partir de um conjunto de dados em formato Excel. A seguir, descreveremos os principais aspectos do aplicativo e como utilizá-lo.

Visão Geral
O Dashboard de Vendas é uma aplicação desenvolvida com Python e utiliza diversas bibliotecas, incluindo Pandas, Streamlit, Altair e Pillow (PIL), para criar visualizações interativas dos dados de vendas.

Funcionalidades
O aplicativo oferece as seguintes funcionalidades:

Seleção de Filtros: O usuário pode selecionar um vendedor, um produto e um cliente a partir de listas suspensas no painel lateral.

Tabelas de Dados: O aplicativo exibe diversas tabelas de dados com base nos filtros selecionados, incluindo a quantidade vendida por produto, vendas e margem para um produto específico, vendas por vendedor e vendas por cliente.

Gráficos Interativos: O aplicativo gera gráficos interativos para melhor visualização dos dados, incluindo gráficos de barras e gráficos de linhas.

Resumo de Vendas: Na página principal, é exibido um resumo das vendas totais, margem total e margem percentual.

Requisitos
Certifique-se de ter as seguintes bibliotecas instaladas para executar o aplicativo:

pandas
streamlit
altair
pillow (PIL)
Você pode instalá-las usando o comando pip:

bash
Copy code
pip install pandas streamlit altair pillow
Executando o Aplicativo
Para executar o aplicativo, siga estas etapas:

Clone este repositório para o seu ambiente local:

bash
Copy code
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Execute o aplicativo usando o Streamlit:

bash
Copy code
streamlit run dashboard_de_vendas.py
O aplicativo será executado localmente e abrirá uma janela do navegador padrão.

Use as opções no painel lateral para selecionar filtros e explorar os dados de vendas.

Configuração da Página
O aplicativo foi configurado para ter um título personalizado, um ícone de página, layout amplo e um menu com links úteis.

Créditos
Este aplicativo foi desenvolvido como parte de um curso e pode ser utilizado como base para a criação de painéis de controle personalizados para análise de vendas.

Ajuda e Suporte
Se você tiver dúvidas ou encontrar algum problema, sinta-se à vontade para entrar em contato pelo link de ajuda ou relatar um bug.
