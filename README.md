#Análise de Dados de Jogadores de Futebol

#Este projeto analisa dados de jogadores de futebol, incluindo informações como nome do jogador, time, minutos jogados, gols marcados, assistências, e outros. 
#As seguintes análises foram realizadas:

#Análise de eficiência
Utilizando as colunas de minutos jogados, gols marcados e chutes no gol, foi criado uma coluna adicional para calcular a taxa de gols por chute no gol.
Foi criado um gráfico de barras para mostrar os 10 jogadores com a maior taxa de gols por chute no gol.
Utilizando a coluna de taxa de gols foi desconsiderado jogadores que só tem 1 gol marcado e jogadores que não marcaram nenhum gol.
Foi criado dois gráficos no seaborn, colocando o nome dos jogadores na horizontal, um para os 10 melhores e outro para os 10 piores

#Previsão
Utilizando o scikit-learn, foi criado um modelo de Random Forest para prever a performance do time Manchester United.
Foi utilizado a coluna de minutos jogados, gols marcados e assistências como variáveis de entrada e a coluna de gols sofridos como a variável de saída.
Foi calculado o erro absoluto médio entre as previsões e os valores reais.


#Conclusão
A análise de eficiência dos jogadores de futebol é uma forma importante de avaliar o desempenho dos jogadores e determinar quem é mais efetivo em marcar gols e fornecer assistências. Com essa análise, foi possível identificar os jogadores com as maiores taxas de gols por chute no gol e criar gráficos para visualizar esses dados. Além disso, foi possível criar previsões sobre o desempenho do time Manchester United e avaliar o erro absoluto médio dessas previsões.
Este projeto pode ser aprimorado com dados mais recentes e mais amplos para obter uma análise mais precisa e completa.
