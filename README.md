# Mecânica Estatística - Tarefas Computacionais

Este repositório contém as tarefas computacionais desenvolvidas para a disciplina de Mecânica Estatística. As tarefas abordam desde a geração de sequências binárias e suas generalizações até a implementação do algoritmo de Metropolis para simulação do modelo de Ising.

## Lista 01 - Combinatória Computacionais

A Lista 01 explora a geração e contagem de sequências utilizando programação. Os exercícios incluem:

* **Geração de sequências binárias:** Implementação de um programa para gerar todas as possíveis sequências binárias de tamanho *n* e contar o total ($2^n$).
* **Generalização para alfabetos maiores:** Extensão do programa para gerar sequências com um alfabeto de *m* símbolos, obtendo um total de $m^n$ sequências.
* **Contagem de sequências com restrições:** Generalização do código para contabilizar apenas as sequências binárias que não possuem 1's consecutivos.
* **Reprodução de resultados analíticos:** Implementação de códigos para reproduzir computacionalmente resultados analíticos específicos.

## Lista 02 - Probabilidade

A Lista 02 foca em probabilidade, com exercícios analíticos e computacionais:

* **Cálculo de funções geradoras, médias e variâncias:** Determinação da função geradora, média e variância para variáveis aleatórias discretas como Bernoulli, binomial, Poisson e geométrica.
* **Cálculo de funções características, médias, variâncias e cumulantes:** Determinação da função característica, média, variância e cumulantes para variáveis aleatórias contínuas como uniforme, exponencial e gama.
* **Propriedades de média e variância:** Demonstração de propriedades como $\langle cX\rangle=c\langle X\rangle$, $\langle X+c\rangle=\langle X\rangle+c$, $var(X)=\langle X^{2}\rangle-\langle X\rangle^{2}$, $var(cX)=c^{2}var(X)$ e $var(X+c)=var(X)$.
* **Aplicação a um diodo:** Análise da corrente em um diodo sujeito a uma voltagem aleatória Gaussiana.
* **Transformação de Box-Muller:** Demonstração analítica de que a transformação de Box-Muller gera variáveis aleatórias independentes com distribuição normal padrão[cite: 13, 14].
* **Probabilidade em sequências binárias:** Cálculo de equações de recorrência para a probabilidade de sequências binárias com restrições (e.g., sem 1's consecutivos ou com número par de 1's).
* **Covariância:** Demonstração de que $cov(X,Y)=\langle X.Y\rangle-\langle X\rangle.\langle Y\rangle$ e que $cov(X,Y)=0$ se X e Y forem independentes, e também que $var(X+Y)=var(X)+var(Y)+2~cov(X,Y)$.
* **Geração de distribuições:** Implementação computacional para gerar e visualizar distribuições de probabilidade exponenciais e Gaussianas a partir de números uniformemente distribuídos, utilizando a transformação de Box-Muller para a Gaussiana.
* **Simulações estocásticas:** Desenvolvimento de simulações estocásticas para os problemas de sequências binárias com restrições, comparando os resultados empíricos com as soluções analíticas.

## Metropolis - Simulação do Modelo de Ising

Este trabalho implementa o algoritmo de Metropolis para simular o modelo de Ising, um método de Monte Carlo com cadeia de Markov.

* **Modelo de Ising:** Simulação de um sistema de spins em uma rede bidimensional com condições periódicas de contorno, utilizando o algoritmo de Metropolis.
* **Dinâmica da magnetização e energia:** Implementação do algoritmo para observar a dinâmica temporal da magnetização e da energia do sistema.
* **Transição de fase:** Construção de um gráfico da média do valor absoluto da magnetização de equilíbrio por partícula em função da temperatura para observar a transição de fase.
