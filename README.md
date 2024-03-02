# Calma senhora é só Poisson

A eficiência operacional de um call center é fundamental para garantir um bom atendimento aos clientes. Neste artigo, vamos analisar o desempenho de um call center que recebe em média 100 chamadas por hora, utilizando conceitos de probabilidade e estatística.

## Distribuição de Poisson

A distribuição de Poisson é uma distribuição de probabilidade discreta que descreve o número de eventos que ocorrem em um intervalo fixo de tempo ou espaço, dado uma taxa média de ocorrência. Vamos usar a distribuição de Poisson para modelar o número de chamadas recebidas em um intervalo de 1 hora, com uma taxa média de 100 chamadas por hora.

A função de massa de probabilidade (PMF) da distribuição de Poisson é dada por:

\[ P(k; \lambda) = \frac{e^{-\lambda} \lambda^k}{k!} \]

onde \( k \) é o número de chamadas e \( \lambda \) é a taxa média de chamadas por hora.

## Probabilidades Específicas

1. **Probabilidade de receber exatamente 100 chamadas em uma hora:**
   \[ P(k=100) = \frac{e^{-100} \cdot 100^{100}}{100!} \]

2. **Probabilidade de receber menos de 90 chamadas em uma hora:**
   \[ P(k < 90) = \sum_{i=0}^{89} \frac{e^{-100} \cdot 100^i}{i!} \]

3. **Probabilidade de receber mais de 120 chamadas em uma hora:**
   \[ P(k > 120) = 1 - \sum_{i=0}^{120} \frac{e^{-100} \cdot 100^i}{i!} \]

## Probabilidade Condicional

Vamos calcular a probabilidade de receber mais de 120 chamadas em uma hora, dado que já recebemos mais de 100 chamadas. A probabilidade condicional é dada por:

\[ P(k > 120 | k > 100) = \frac{P(k > 120 \cap k > 100)}{P(k > 100)} \]

## Aproximação pela Normal

Para verificar se a distribuição de Poisson pode ser aproximada pela distribuição normal neste cenário, podemos usar a média e a variância da distribuição de Poisson para calcular a distribuição normal correspondente.

## Conclusão

A análise probabilística e estatística do número de chamadas recebidas em um call center pode fornecer insights importantes para otimizar a operação e melhorar a qualidade do atendimento. Neste artigo, aplicamos os conceitos de distribuição de Poisson, probabilidades específicas, probabilidade condicional e aproximação pela normal para analisar o desempenho de um call center que recebe em média 100 chamadas por hora.