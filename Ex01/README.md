Este conjunto de dados possui as seguintes variáveis: tempo (Data do registo); gcp (gastos de consumo pessoal, em biliões de dólares); pop (população total); tpp (taxa de poupança pessoal); ddesemp (duração mediana do desemprego, em semanas); ndesemp (número de desempregados, em milhares).

Considere as variáveis X1=gcp e X2=pop para os anos superiores ou iguais a 1977. Com recurso ao pacote ggplot produza um único gráfico que lhe permita fazer uma análise da evolução dessas duas variáveis para esses anos.

Uma vez que as variáveis podem não ter a mesma escala, antes de construir o gráfico proceda do seguinte modo:

Selecione os dados a usar.

Faça a seguinte transformação aos dados associados a cada variável
![Equation](https://latex.codecogs.com/svg.image?\large&space;\bg{white}X_k:&space;z_{i&space;k}=\frac{x_{i&space;k}-\bar{x}_k}{s_{x_k}},&space;\quad&space;i=1,2,&space;\ldots,&space;n),
onde n é o número de observações da amostra, x¯k e sxk correspondem, respectivamente, à média e desvio-padrão da amostra associada à variável Xk.
