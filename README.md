# DrugClassificationRandomForest
Modelo de **random forest classifier**

# Objetivo:
Classificar a droga mais adequada para determinados pacientes.

# Explicação do modelo:
O modelo de machine learning escolhido para esse dataset foi a floresta aleatória, que é um método de aprendizado baseado em árvores de decisão. A floresta aleatória cria várias árvores de decisão a partir de subconjuntos aleatórios dos dados de treinamento e combina suas previsões por meio de votação. Esse método tem algumas vantagens, como:

- Não requer suposições sobre a distribuição dos dados ou a forma da função de decisão;
- É robusto a ruídos e outliers nos dados;
- Pode lidar com variáveis categóricas e numéricas;
- Pode estimar a importância das variáveis para a previsão.

O objetivo do modelo é prever qual tipo de droga é mais adequado para um paciente, com base em suas características. As variáveis independentes são:

- Age - Idade do paciente em anos;
- Sex - Gênero do paciente (masculino ou feminino);
- BP - Nível de pressão arterial do paciente (baixo, normal ou alto);
- Cholesterol - Nível de colesterol do paciente (normal ou alto);
- Na_to_K - Proporção entre sódio e potássio no sangue do paciente.

A variável dependente é:

- Drug - Tipo de droga recomendada para o paciente (drugA, drugB, drugC, drugX ou drugY).

O modelo foi avaliado usando os dados de teste, que correspondem a 30% do dataset original. Os resultados foram os seguintes:

- Acurácia: 100% - O modelo acertou todas as previsões nos dados de teste;

- Validação cruzada: 96% - O modelo teve uma média de 96% de acurácia, que é uma técnica para verificar a generalização do modelo em diferentes subconjuntos dos dados;

- Recall: 100% - O modelo identificou corretamente todos os casos positivos de cada classe de droga nos dados de teste.

Esses resultados indicam que o modelo tem um bom desempenho e pode ser usado para prever o tipo de droga mais adequado para um paciente, com base em suas características.

# Observação:
Este projeto tem fins apenas **educacionais** e não deve ser usado em casos reais, pois o modelo foi treinado usando **dados fictícios**.

Banco de dados utilizado: https://www.kaggle.com/datasets/prathamtripathi/drug-classification

# Qualquer dúvida entre em contato:
- Email: dev.venicius1912@gmail.com
- LinkedIn: www.linkedin.com/in/venicius-santana-lima
