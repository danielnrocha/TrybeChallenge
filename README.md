# TrybeChallenge – Processo Seletivo Data Scientist
## Daniel N. Rocha
Desafio: "Como predizer o desempenhos dos estudantes nas avaliações finais?"
O dataset utilizado foi do Open University Learning Analytics: https://analyse.kmi.open.ac.uk/open_dataset

<img src="https://github.com/danielnrocha/TrybeChallenge/blob/main/logo_ppt.png" width="700">

**Descrição**
- Modelo de previsão da nota final de alunos, usando dados demográficos, de atividades realização na plataforma de educação virtual e informações sobre as avaliações.

**Solução**
1. Com nosso modelo, é possível mapear os alunos com maior probabilidade de reprovação, de modo a ajudá-los antes de falharem na prova
2. A nossa solução também permite compreender quais os principais fatores que influenciam na probabilidade de reprovação, de modo a orientar os tomadores de decisão sobre possíveis melhorias na gestão da plataforma educacional

**Insights**
- Com base nas evidências coletadas, sugerimos 3 melhorias para otimizar a capacidade de aprovação dos alunos:
1. Redução do tempo de aplicação de prova: não esperar o curso avançar muito para aplicar avaliações
2. Aumentar a duração dos cursos: há indicativo de que cursos longos facilitam na fixação do conteúdo
3. Estimular a revisão no meio do curso: interagir com os materiais didáticos após haver transcorrido mais tempo desde o início do curso é um bom indicativo de sucesso nas avaliações

**Tecnologias**
- Modelo de Machine Learning CatBoost Regression
- SHAP para aumentar a interpretabilidade
- PyCaret para benchmark entre demais modelos
- Análise Exploratória de Dados (Seaborn, Matplotlib)
