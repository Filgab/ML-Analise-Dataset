# # 1. Informações Básicas
# • Nome do dataset: Default of Credit Card Clients
# • Fonte: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
# • Dimensões: (30000, 25)
# • Tamanho em MB: ~3.7 MB

# # 2. Problema de Machine Learning
# • Tipo: [X] Classificação [ ] Regressão
# • Variável alvo (target): inadimplente (default payment next month)
# • Número de classes: 2 (0 = Não inadimplente, 1 = Inadimplente)
# • Distribuição do target:
#   - Classe 0: 23.364 (77,88%)
#   - Classe 1: 6.636 (22,12%)

# # 3. Qualidade dos Dados
# • % valores faltantes: 0% (dataset completo)
# • Tipos de variáveis:
#   - Numéricas contínuas: LIMIT_BAL, BILL_AMT1-6, PAY_AMT1-6
#   - Categóricas: SEX, EDUCATION, MARRIAGE, PAY_0-PAY_6
#   - Datas: Nenhuma
#   - Texto: Nenhuma

# # 4. Justificativa
# • Por que escolheram este dataset?
#   Dataset clássico e bem-estruturado para aprendizado de classificação binária, com aplicação prática no setor financeiro.

# • Qual problema real vocês querem resolver?
#   Prever a inadimplência de clientes para reduzir perdas financeiras e melhorar a gestão de risco de crédito.

# • Que insights esperam encontrar?
#   Identificar os principais fatores que levam à inadimplência (idade, educação, histórico de pagamentos, etc.)
#   e construir um modelo preditivo eficiente para classificação de risco.