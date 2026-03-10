Comparando Estratégias de Ensino com Teste Z

Criei este projeto para descobrir se uma nova estratégia de ensino (B) realmente traz resultados melhores do que a tradicional (A) nas notas de matemática. A ideia foi usar estatística para sair do "achismo" e ver se a diferença de notas é real ou apenas coincidência.

O que foi feito
Simulei notas de 100 alunos (50 para cada método) e apliquei um Teste Z. Meu objetivo era provar que a média da Estratégia B é maior que a da A, o que classifica o teste como unilateral à direita.

O que os dados mostraram
Média A: 71.41
Média B: 74.75
P-valor: 0.0634

Conclusão
Mesmo que a Estratégia B tenha tido uma média um pouco mais alta, o p-valor de 0.063 ficou acima do limite de 5% que defini.
Na prática: não dá para dizer com certeza que a Estratégia B é melhor. Essa diferença de pontos pode ter acontecido por puro acaso (variabilidade da amostra). Por enquanto, as duas estratégias são consideradas estatisticamente equivalentes.

Tecnologias
Usei Python com as bibliotecas NumPy para os dados, SciPy para o cálculo estatístico e Matplotlib para gerar o gráfico da curva normal que está no notebook.
