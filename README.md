# 🇧🇷
# 📶 Projeto Megaline – Análise dos Planos Surf e Ultimate

Neste projeto, atuei como analista da Megaline, uma operadora de telecomunicações que oferece dois planos pré-pagos: Surf e Ultimate. A missão foi entender o comportamento dos clientes e identificar qual dos planos gera mais receita, ajudando o time comercial a ajustar o orçamento de marketing.

Comecei estudando o conjunto de dados, que incluía informações de usuários, chamadas, mensagens e uso de internet ao longo de 2018. Em seguida, preparei os dados corrigindo tipos incorretos, tratando valores ausentes, removendo inconsistências e organizando tudo por mês e por usuário. Também calculei a receita mensal de cada cliente considerando limites de pacotes, excedentes e valores cobrados.

Com os dados limpos, analisei como os clientes de cada plano utilizam minutos, mensagens e dados. Calculei médias, variâncias e desvios padrão, além de construir histogramas para visualizar as distribuições e comparar o comportamento entre Surf e Ultimate.

A etapa final envolveu testes estatísticos para responder duas perguntas importantes:

Os planos geram receitas médias diferentes?

Usuários da região NY-NJ gastam mais que usuários de outras regiões?

Para isso, formulei hipóteses nula e alternativa, selecionei os testes adequados e interpretei os resultados para tirar conclusões claras.

No geral, foi um projeto completo, que reforçou a importância da limpeza de dados, da análise exploratória e do uso de métodos estatísticos para apoiar decisões de negócio. Documentei todo o processo no Jupyter Notebook, combinando código, visualizações e explicações ao longo do caminho.
# 🇺🇸
# 📡 Megaline Project – Revenue Analysis for Mobile Plans

In this project, I worked as a data analyst for Megaline, a telecom company that offers two prepaid mobile plans: Surf and Ultimate. The commercial team wanted to understand which plan generates more revenue so they could adjust their advertising budget accordingly.

The dataset included information from 500 customers, covering their demographics, call activity, text messages, internet usage, and the plan each customer subscribed to. My goal was to analyze customer behavior throughout 2018 and identify which plan is more profitable on average.

I started by loading and cleaning the data from five different tables. This included converting data types, fixing inconsistencies, removing errors, and preparing monthly usage summaries for each customer—such as total minutes, messages, and data consumed.

Once the data was ready, I calculated monthly revenue for each user. This required subtracting the free allowances included in each plan, applying the correct overage fees, and adding the base monthly plan price. With that completed, I compared usage patterns between Surf and Ultimate customers and explored their distributions through histograms and summary statistics.

The final step involved performing statistical hypothesis testing to determine whether the average revenue differs between the two plans, and whether the revenue for customers from the NY–NJ area differs from customers in other regions. I defined null and alternative hypotheses, selected appropriate statistical tests, and interpreted the results to support data-driven decisions.

Overall, this project combined data cleaning, feature engineering, exploratory analysis, statistical testing, and clear storytelling. It was a great opportunity to practice the full analytical workflow, from raw data to actionable insights.
