# Challenge-Alura-Store
Nesse desafio,i rei analisar dados de vendas, desempenho e avaliações das 4 lojas fictícias da Alura Store. O objetivo é identificar a loja com menor eficiência e apresentar uma recomendação final baseada nos dados.
# Requisitos:

Analisar os dados das lojas:

Avaliar informações como faturamento, categorias mais vendidas, avaliações dos clientes, produtos mais vendidos e frete médio.

Criar gráficos para visualização:

Decidir quais tipos de gráficos usar para apresentar os resultados de maneira clara e visual.

Mínimo de 3 gráficos diferentes, que podem incluir gráficos de barras, pizza, dispersão, entre outros.

Apresentar uma recomendação:

Após as análises, escreva um texto explicando qual loja o Senhor João deve vender e por quê, com base nos dados apresentados.

🎯 Propósito da Análise
Este projeto tem como objetivo principal auxiliar o Senhor João, proprietário da rede Alura Store, na decisão de qual de suas 4 lojas fictícias deve ser vendida para viabilizar um novo empreendimento. A análise se baseia em dados de vendas, desempenho e avaliações de clientes, visando identificar a loja com a menor eficiência e fornecer uma recomendação fundamentada em dados.

📁 Estrutura do Projeto e Organização dos Arquivos
O projeto é composto por um único notebook Jupyter, que centraliza todo o processo de análise, visualização e geração da recomendação.

AluraStoreBr.ipynb: O arquivo principal do projeto, contendo o código Python para:
Carregar e manipular os dados de vendas das 4 lojas (CSV).
Realizar análises exploratórias de faturamento, categorias de produtos, avaliação de clientes, produtos mais/menos vendidos e frete.
Gerar visualizações gráficas para facilitar a compreensão dos dados.
Apresentar a recomendação final.
Dados: Os dados utilizados são carregados diretamente de URLs do GitHub, o que significa que não há arquivos CSV locais necessários para a execução, simplificando o setup.
📊 Exemplos de Gráficos e Insights Obtidos
A análise gera diversos gráficos e insights para fundamentar a decisão. Abaixo estão exemplos dos tipos de visualizações e as conclusões esperadas:

Faturamento Total por Loja (Gráfico de Barras):

Insight: Permite uma comparação direta do desempenho financeiro de cada loja. A loja com o menor faturamento é um forte candidato à venda.
Faturamento por Categoria de Produto por Loja (Gráfico de Barras Empilhadas):

Insight: Mostra quais categorias impulsionam as vendas em cada loja e se há alguma loja com um desempenho muito abaixo da média em categorias chave. Isso ajuda a entender a saúde do mix de produtos por unidade.
Distribuição Geral do Faturamento por Categoria de Produto (Gráfico de Pizza):

Insight: Oferece uma visão macro das categorias mais lucrativas para a Alura Store como um todo, validando se o foco das lojas está alinhado com a demanda geral.
Média de Avaliação dos Clientes por Loja (Gráfico de Barras):

Insight: Essencial para medir a satisfação do cliente. Lojas com avaliações significativamente mais baixas indicam problemas de qualidade, atendimento ou experiência de compra.
Frete Médio por Loja (Gráfico de Barras):

Insight: Ajuda a entender a estrutura de custos de frete de cada loja. Um frete muito alto pode impactar a competitividade, enquanto um muito baixo pode indicar vendas de produtos de menor porte ou eficiência na logística.
Com base nessas análises, será possível identificar a loja que demonstra menor eficiência, seja por baixo faturamento, insatisfação dos clientes, ou uma combinação de fatores, e justificar a recomendação de venda.

🚀 Instruções para Executar o Notebook
Para executar a análise e gerar a recomendação, siga os passos abaixo:

Pré-requisitos:

Ter o Python instalado (preferencialmente Python 3.x).
Ter o Jupyter Notebook ou JupyterLab instalado. Você pode instalá-los via pip:
Bash

pip install notebook pandas matplotlib
ou se estiver usando Anaconda/Miniconda:
Bash

conda install notebook pandas matplotlib
Download do Notebook:

Baixe o arquivo AluraStoreBr.ipynb para o seu computador.
Abrir o Jupyter Notebook:

Abra o terminal ou prompt de comando na pasta onde você salvou o arquivo AluraStoreBr.ipynb.
Execute o comando:
Bash

jupyter notebook
Isso abrirá uma nova aba no seu navegador com o ambiente Jupyter.
Executar a Análise:

No ambiente Jupyter, navegue até a pasta onde salvou o AluraStoreBr.ipynb e clique nele para abri-lo.
Para executar todas as células em sequência e gerar os resultados (incluindo os gráficos e a recomendação final), vá em Kernel -> Restart & Run All na barra de menu do Jupyter.
Alternativamente, você pode executar as células uma por uma clicando em cada célula e pressionando Shift + Enter.
