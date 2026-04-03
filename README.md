📊 E-commerce Strategic Analysis | Olist Dataset
Este projeto apresenta uma análise estratégica de um e-commerce brasileiro, utilizando o conjunto de dados público da Olist. O objetivo foi transformar dados brutos em insights acionáveis sobre vendas, logística e comportamento de pagamento.

🚀 Visão Geral do Projeto
O dashboard foi desenvolvido para responder a perguntas críticas de negócio, como:

Quais categorias de produtos geram maior receita?

Qual o impacto dos diferentes métodos de pagamento no volume de vendas?

Como a sazonalidade afeta o desempenho mensal?

Qual a eficiência logística (prazo médio de entrega)?

🛠️ Tecnologias e Ferramentas
Python: Extração e limpeza de dados (ETL).

Power BI: Modelagem de dados, criação de medidas DAX e visualização.

Dataset: Olist E-Commerce Public Dataset (Kaggle).

📂 Processo de Desenvolvimento
1. ETL (Extração, Transformação e Carga)
Os dados passaram por um processo de limpeza para garantir a integridade das análises:

Tratamento de valores ausentes e duplicados.

Padronização de nomes de categorias de produtos.

Conversão de tipos de dados (datas e valores monetários).

2. Modelagem de Dados
Utilização do esquema Star Schema para otimizar a performance das consultas, relacionando tabelas de fatos (vendas) com dimensões (produtos, pagamentos, tempo).

3. Principais Insights
Dominância de Meios de Pagamento: O cartão de crédito representa 76,5% das vendas totais, seguido pelo boleto.

Liderança de Categoria: A categoria de Beleza e Saúde é o principal driver de receita, com 0,51 Mi em vendas.

Análise Logística: O prazo médio de entrega identificado foi de aproximadamente 120 dias (ajustar conforme seu filtro de data), indicando pontos de atenção na cadeia de suprimentos.

📈 Como visualizar o projeto
Baixe o arquivo .pbix presente neste repositório.

Certifique-se de ter o Power BI Desktop instalado.

Caso queira ver o código de tratamento de dados, acesse a pasta /scripts.

