# Lego II
Anotações leituras e aula Lego II - IESP/UERJ, Prof. Dr. Rogério Barbosa.

# Aula 10 - 14/10 - Ajustando curvas

**ML6:  Supor a normalidade dos ERROS individuais.**

Teste F: teste de múltiplas hipóteses lineares --> "teste global" do ajuste da regressão

O quadrado de uma distribuição normal padrão, é uma distribuição Qui-Quadrado com um grau de liberdade.


# Aula 11 - 21/10 - Forma funcional, uso de logs, interações

**Teste F e análise de variância (ANOVA)**

--> Queremos saber se o beta estimado é diferente de uma certa hipótese de interesse. Para isso, a gente mede quantos desvios-padrão há de distancia entre o valor estimado e nossa hipótese. No teste F, podemos testar múltiplas hipóteses de uma vez.  

--> Se um grupo tem uma variância muito grande, isso quer dier que ele não é tão informativo (variável explicativa de um fenômeno de interesse)


# Aula 13 - 04/11 - Probabilidade

--> Uma variável aleatória $X$ é uma função que mapeia alternativas do espaço amostral $\Omega$ para o conjunto dos números reais:  

$X : \Omega \to \mathbb{R}$

--> Espaço amostral $\Omega$ é o conjunto das alternativas possíveis de serem sorteados.  

### Funções de distribuição (funções paramétricas)

-->  Distribuição de Bernoulli, distribuição binomial;

-->  Distribuições paramétricas resumem uma tabela grande em um pequeno conjunto de parâmetros (i.e. números pré-definidos) e uma fórmula:

qual é a fórmula?   
qual é o valor pré-determinado dos parâmetros?  

### Distribuição de Poisson 

--> É uma distribuição com espaço amostral

$x : \mathbb{I}$ = {0, 1, 2, ...}

com um único parâmetro $\lambda$ que define, ao mesmo tempo o ponto central e a dispersão 

A função de probabilidade da distribuição de Poisson é dada por:

$$
f(x) = \frac{e^{-\lambda} \lambda^x}{x!}, \quad x = 0, 1, 2, \ldots
$$

--> Nas distribuições paramétricas os momentos* da distribuição são obtidos por meio de alguma função/transformação dos parâmetros  

* momento é um valor esperado de uma potência (centrada ou não) da distribuição

### Distribuição normal 

A função densidade de probabilidade da distribuição Normal é:

$$
f(x) = \frac{1}{\sigma \sqrt{2\pi}}
\exp\left(-\frac{(x - \mu)^2}{2\sigma^2}\right)
$$

Parâmetros:

* $\mu$ --> altera o lugar da distância;
* $\sigma^2$ --> altera a dispersão da distribuição.

### Distribuições discretas e contínuas

--> Discretas têm $\Omega$ enumerável, contável e é possível calcular a probabilidade. Cada valor do espaço amostral **exatamanete**.

--> Discretas contínuas têm $\Omega$ não contável, não numerável e a probabilidade de um valor específico é irrisória e não é de interesse. Calcular a probabilidade de **intervalos**.
