# Previsão de vendas - Rossmann

## Problema de negócio
A Rossmann opera em mais de 3.000 drogarias em 7 países europeus. Atualmente, os gerentes das lojas da Rossmann têm a tarefa de prever suas vendas diárias com até seis semanas de antecedência. As vendas da loja são influenciadas por muitos fatores e são geridas por diferentes pessoas, gerando resultados diferentes para cada unidade e considerando somente suas condições individuais. Portanto, este projeto tem como objetivo obter uma previsão mais precisa das vendas de cada loja.


## Premissas do negócio
Foram utilizados três categorias nas hipóteses, que são elas: sobre as lojas, sobre os produtos e sobre o tempo. 

Nas hipóteses sobre as lojas considerei os seguintes itens: 
- o quadro de funcinários,
- a quantidade de estoque,
- o porte da empresa,
- os competidores e
- o sortimento.

Nas hipóteses dos produtos foram analizados:
- o investimento em marketing, 
- a exposição dos produtos nas vitrines,
- os preços e
- as promoções
  
Por fim, nas hipóteses de tempo:
- a abetura em feriados,
- as vendas ao longo dos anos,
- as vendas por semestre,
- as vendas após o dia 10 de cada mês,
- as vendas nos finais de semana e
- os feriados escolares

## Estratégias e soluções
Os dados foram obtidos do site do Kaggle, e foram realizados a limpeza e tratamentos do dataset. Logo em seguido realizei a análise exploratória para verificar a relação dos dados que estou trabalhando e testar as hipóteses citadas anteriormente.

Para selecionar as melhores variáveis foi utilizado o Boruta e com as features selecionados foram aplicados 6 tipos de modelos: average model, Linear Regression Model, Linear Regression Regularized Model - Lasso, Random Forest Regressor e o XGBoost Regressor.
 

## Conclusões
