# Pratica2_PDS1

Um estatístico lhe procurou pois precisa de uma implementação em C de funções de densidade de probabilidade de três distribuições: Cauchy padrão, Gumbel e distribuição de Laplace. 

Exercício 1

Crie uma função que retorna a função de densidade de probabilidade  para cada uma dessas distribuições.

a) Cauchy padrão

b) Gumbel

c) Laplace

Considere usar as funções exp(x) para calcular e^x e fabs(x) para calcular |x| ambas funções encontradas na biblioteca math.h. 

Exemplos:

fabs(-5.3) retorna 5.3 

exp(3) retorna e^3 

Além disso, considere que pi = 3.141592 ou então use a constante M_PI da biblioteca math.h. Por fim, note que além de X as funções podem ter outros parâmetros de entrada. A função densidade de probabilidade da distribuição de Laplace, por exemplo, tem como parâmetros de entrada ,  e .


Exercício 2

Crie e compile um módulo que contenha as funções estatísticas implementadas no exercício anterior.


Exercício 3

Implemente um programa que use o módulo criado do exercício anterior para calcular e exibir a função densidade de probabilidade nos seguintes pontos:

cauchy(x=-2) 

[resultado para conferência: 0.063662]

gumbel(x=0, $\mu$=0.5, $\beta$=2)

[resultado para conferência: 0.177786]

laplace(x=-6, $\mu$=-5, $b$=4)

[resultado para conferência: 0.097350]


Resumo da obra:

Nesta prática você deve entregar três arquivos:

estatistica.h, que contém os cabeçalhos das funções cauchy, gumbel e laplace;

estatistica.c, que contém a implementação das funções cauchy, gumbel e laplace;

pratica2.c, que contém a função main e as chamadas das funções cauchy, gumbel e laplace.
