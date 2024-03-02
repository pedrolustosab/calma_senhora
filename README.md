# Calma Senhora é só Poisson!


Análise de Desempenho de um Call Center com a Distribuição de Poisson
A eficiência operacional de um call center é fundamental para garantir um bom atendimento aos clientes. Neste artigo, vamos analisar o desempenho de um call center que recebe em média 100 chamadas por hora, utilizando conceitos de probabilidade e estatística.

Distribuição de Poisson
A distribuição de Poisson é uma distribuição de probabilidade discreta que descreve o número de eventos que ocorrem em um intervalo fixo de tempo ou espaço, dado uma taxa média de ocorrência. Vamos usar a distribuição de Poisson para modelar o número de chamadas recebidas em um intervalo de 1 hora, com uma taxa média de 100 chamadas por hora.

A função de massa de probabilidade (PMF) da distribuição de Poisson é dada por:

�
(
�
;
�
)
=
�
−
�
�
�
�
!
P(k;λ)= 
k!
e 
−λ
 λ 
k
 
​
 

onde 
�
k é o número de chamadas e 
�
λ é a taxa média de chamadas por hora.

Probabilidades Específicas
Probabilidade de receber exatamente 100 chamadas em uma hora:
�
(
�
=
100
)
=
�
−
100
⋅
10
0
100
100
!
P(k=100)= 
100!
e 
−100
 ⋅100 
100
 
​
 

Probabilidade de receber menos de 90 chamadas em uma hora:
�
(
�
<
90
)
=
∑
�
=
0
89
�
−
100
⋅
10
0
�
�
!
P(k<90)=∑ 
i=0
89
​
  
i!
e 
−100
 ⋅100 
i
 
​
 

Probabilidade de receber mais de 120 chamadas em uma hora:
�
(
�
>
120
)
=
1
−
∑
�
=
0
120
�
−
100
⋅
10
0
�
�
!
P(k>120)=1−∑ 
i=0
120
​
  
i!
e 
−100
 ⋅100 
i
 
​
 

Probabilidade Condicional
Vamos calcular a probabilidade de receber mais de 120 chamadas em uma hora, dado que já recebemos mais de 100 chamadas. A probabilidade condicional é dada por:

�
(
�
>
120
∣
�
>
100
)
=
�
(
�
>
120
∩
�
>
100
)
�
(
�
>
100
)
P(k>120∣k>100)= 
P(k>100)
P(k>120∩k>100)
​
 

Aproximação pela Normal
Para verificar se a distribuição de Poisson pode ser aproximada pela distribuição normal neste cenário, podemos usar a média e a variância da distribuição de Poisson para calcular a distribuição normal correspondente.

Conclusão
A análise probabilística e estatística do número de chamadas recebidas em um call center pode fornecer insights importantes para otimizar a operação e melhorar a qualidade do atendimento. Neste artigo, aplicamos os conceitos de distribuição de Poisson, probabilidades específicas, probabilidade condicional e aproximação pela normal para analisar o desempenho de um call center que recebe em média 100 chamadas por hora.