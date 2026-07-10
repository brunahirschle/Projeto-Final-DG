Classificação de Score de Crédito com Machine Learning

Objetivo:

Desenvolver um modelo de Machine Learning capaz de classificar o score de crédito de clientes a partir de informações financeiras e comportamentais.

Perguntas Norteadoras:

- Quais variáveis podem ter maior relação com a capacidade de pagamento dos clientes?
- Qual perfil de cliente possui maior probabilidade de ser classificado como Score 'Poor'?
- Um modelo de Machine Learning consegue classificar o score de crédito dos clientes com boa performance?
- Como os resultados do modelo poderiam apoiar uma equipe de crédito na priorização de análises, concessão de crédito ou revisão de limites?
- Quais cuidados éticos e de negócio devem ser considerados antes de usar um modelo como esse em produção?

Dataset:

- Credit Score Classification (Kaggle)

Tecnologias:

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

Etapas do projeto:

- Análise Exploratória dos Dados (EDA)
- Limpeza e tratamento dos dados
- Engenharia de atributos
- Codificação de variáveis categóricas
- Treinamento dos modelos
  - Árvore de Decisão
  - Random Forest
- Avaliação dos modelos
- Análise da importância das variáveis

Resultados:

| Modelo | Acurácia |
|---------|---------:|
| Árvore de Decisão | 69,07% |
| Random Forest | 79,07% |

O Random Forest apresentou o melhor desempenho e foi selecionado como modelo final.

Estrutura do projeto:

Projeto-Final-DG/
├── .venv2 (ignorado pelo git)
│    └── .gitignore
│
├── .vscode
│    └── settings.json
│
├── dados/
│   ├── train.csv
│   └── test.csv
│
├── notebook/
│   └── projeto_final.ipynb
│
├── README.md
└── requirements.txt
