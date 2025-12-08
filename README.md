📘 Projeto de Machine Learning — Predição de Desempenho Acadêmico

Disciplina: Machine Learning
Professor: Durval Lins de Siqueira Neto
Curso: Análise e Desenvolvimento de Sistemas (ADS)
Período: 4º Período
Turma: C

👥 Integrantes

José Acácio Cavalcanti Leal – 01686766

José Marcio da Silva Vieira – 01708370

Vitor de Lima Silva – 01681385

📂 Dataset Utilizado

students_performance.csv
🎯 Objetivo do Projeto

Este projeto teve como objetivo desenvolver um modelo de Machine Learning capaz de prever o desempenho acadêmico dos estudantes, utilizando variáveis presentes no dataset students_performance.csv.

Entre as variáveis analisadas estão fatores como:

tempo de estudo,

frequência,

notas anteriores,

dados socioeducacionais,

e demais características associadas ao rendimento escolar.

O projeto contempla todas as etapas fundamentais de um pipeline de Machine Learning, incluindo análise exploratória dos dados (EDA), pré-processamento, modelagem, avaliação dos modelos e seleção da melhor abordagem preditiva.
🗂️ Estrutura do Repositório
.
├── README.md                 # Descrição geral do projeto
├── data/
│   ├── raw/                  # Dados originais
│   └── processed/            # Dados tratados após pré-processamento
├── notebooks/
│   ├── 01_EDA.ipynb          # Análise exploratória dos dados
│   ├── 02_Preprocessamento.ipynb # Limpeza e transformação dos dados
│   ├── 03_Modelagem.ipynb    # Treinamento dos modelos
│   └── 04_Avaliacao.ipynb   # Avaliação e validação dos modelos
├── models/
│   └── modelo_final.joblib   # Modelo final treinado
├── docs/
│   └── RELATORIO_FINAL.md    # Relatório técnico do projeto
└── requirements.txt          # Dependências do projeto

🛠️ Tecnologias Utilizadas

*Python 3.10 ou superior

*Pandas

*NumPy

*Scikit-learn

*Matplotlib

*Seaborn

*Joblib

*Jupyter Notebook
▶️ Como Executar o Projeto

1️⃣ Clonar o repositório
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO
2️⃣ Instalar as dependências
pip install -r requirements.txt
3️⃣ Executar os notebooks
jupyter notebook notebooks/
4️⃣ Executar os arquivos na seguinte ordem
01_EDA.ipynb
02_Preprocessamento.ipynb
03_Modelagem.ipynb
04_Avaliacao.ipynb

✅ Resultado Final

Após a avaliação de diferentes algoritmos de regressão, o modelo que apresentou melhor desempenho preditivo foi o Random Forest Regressor, considerando métricas como MAE, RMSE e R².

O modelo final foi salvo utilizando a biblioteca Joblib, permitindo seu carregamento e reutilização para previsões futuras de desempenho acadêmico.
📌 Conclusão

O projeto demonstrou a eficácia do uso de técnicas de Machine Learning para análise e previsão de desempenho acadêmico, evidenciando a importância de fatores educacionais no rendimento dos estudantes. A abordagem adotada segue boas práticas de ciência de dados, garantindo reprodutibilidade, organização do código e confiabilidade nos resultados obtidos.
