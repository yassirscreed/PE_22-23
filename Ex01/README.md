Este conjunto de dados possui as seguintes variáveis: tempo (Data do registo); gcp (gastos de consumo pessoal, em biliões de dólares); pop (população total); tpp (taxa de poupança pessoal); ddesemp (duração mediana do desemprego, em semanas); ndesemp (número de desempregados, em milhares).

Considere as variáveis $X_1 = gcp$ e $X_2= ndesemp$ para os anos superiores ou iguais a **1968**.

Com recurso ao pacote ggplot produza um único gráfico que lhe permita fazer uma análise da evolução dessas duas variáveis para esses anos.

Uma vez que as variáveis podem não ter a mesma escala, antes de construir o gráfico proceda do seguinte modo:

1. Selecione os dados a usar.

2. Faça a seguinte transformação aos dados associados a cada variável

    $$X_k: z_{i k}=\frac{x_{i k}-\bar{x}_k}{s_{x_k}}, \quad i=1,2, \ldots, n$$

    onde n é o número de observações da amostra, $\bar{x_k}$ e ${s_{x_k}}$ correspondem, respectivamente, à média e desvio-padrão da amostra associada à variável $X_k$.
