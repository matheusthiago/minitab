## Imagem 1 
No arquivo **exp-qbXrr.csv** existe as seguintes colunas: "i	policySchedule	algorithm	time	gapLength	elapsedTime	reqTime	rmse	server	rate	policyGapFill	location	x". 
Para imprimir a seguinte imagem: 
![image](https://github.com/matheusthiago/minitab/assets/17621475/eaeeb907-65c1-4e4f-ab53-70dda010fa03)
Foi utilizado a coluna "x" para indicar o momento de lançamento da requisição, ou seja o eixo X.
Já no eixo Y, foi utilizado a coluna "time" e a cor é dada pela coluna "server". 
Por último a facet_grid foi utilizada como rate~policySchedule. Ou seja, o tipo de escalocamento em X e a taxa de envio em Y. 

## Planejamento de experimentos
Para os resultados do planejamento de experimentos foram utilizados os arquivos **minitab_QB_RR.csv** e  **minitab_QB_min.csv** que tem os resultados dos experimentos. O primeiro arquivo é do Q-Balance com o Round-robin, o segundo é do Q-Balance com o Min-Load.
Ambos contam com as seguintes colunas: "Algoritmo de Balanceamento","Algoritmo de Imputação","Taxa de Envio de Requisição","Localização dos Recursos","x","i","Tempo de resposta"
Os fatores utilizados foram: Algoritmo de Balanceamento, Algoritmo de Imputação, Taxa de Envio de Requisição e Localização dos Recursos. A variável observada foi Tempo de resposta. 
