# Análise de Hábitos e Desempenho de Estudantes

Este repositório contém uma análise exploratória sobre hábitos de estudo e desempenho acadêmico. O objetivo é identificar quais fatores (horas de estudo, sono, uso de redes sociais, participação em atividades, entre outros) mais influenciam a nota do exame (`exam_score`) usando o conjunto de dados `student_habits_performance.csv`.

## Sobre o conjunto de dados
- Registros: 1000
- Colunas principais:
  - `student_id`, `age`, `gender`
  - `study_hours_per_day`, `social_media_hours`, `netflix_hours`
  - `part_time_job`, `attendance_percentage`, `sleep_hours`
  - `diet_quality`, `exercise_frequency`, `parental_education_level`
  - `internet_quality`, `mental_health_rating`, `extracurricular_participation`
  - `exam_score`

## Tecnologias
- Python 3
- pandas, matplotlib, seaborn
- Jupyter Notebook

## Estrutura do projeto
text
├── main.ipynb                     # Notebook principal com a análise
├── student_habits_performance.csv # Conjunto de dados
└── README.md                      # Este arquivo

## Como executar (Windows)
1. Clonar o repositório:
   - PowerShell:
     git clone https://github.com/seu-usuario/student-habits-analysis.git
2. Criar e ativar ambiente (opcional):
   - PowerShell:
     python -m venv .venv
     .\.venv\Scripts\Activate.ps1
3. Instalar dependências:
   - PowerShell/cmd:
     pip install pandas matplotlib seaborn jupyter
4. Abrir o notebook:
   - PowerShell/cmd:
     jupyter notebook main.ipynb

(Também funciona com `jupyter lab` ou em WSL.)

## Metodologia resumida
- Carregamento e limpeza dos dados
- Exploração inicial (tipos, valores ausentes, estatísticas)
- Visualizações de relação entre variáveis e `exam_score`
- Correlações e análises estatísticas
- Passos para modelagem preditiva (se aplicável)

## Resultados e próximos passos
- Análises detalhadas e gráficos serão adicionados no `main.ipynb`.
- Próximos passos: modelagem preditiva, análise de clusters e validação cruzada.

## Contribuições
Pull requests e issues são bem-vindos. Por favor, descreva mudanças e adicione exemplos ao notebook quando possível.

## Licença
Coloque aqui a licença desejada (por exemplo, MIT) ou remova se não aplicável.