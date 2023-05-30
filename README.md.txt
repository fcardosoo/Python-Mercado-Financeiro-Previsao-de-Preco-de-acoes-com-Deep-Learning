[![PyPI - Python](https://img.shields.io/pypi/pyversions/iconsdk?logo=pypi)](https://pypi.org/project/iconsdk)

<h1>Como prever o preço das ações no mercado financeiro com Python e Machine Learning usando redes neurais</h1> 

<p><b>Será que é possível ganhar dinheiro na bolsa com inteligência artificial?</b></p>

<p>Nos últimos anos, houve uma explosão no uso de aprendizado de máquina (<b>machine learning</b>), especialmente aprendizado profundo (<b>deep learning</b>), para prever os preços das ações. Embora existam muitas maneiras diferentes de abordar esse problema, uma abordagem popular é usar uma rede LSTM (<b>long short-term memory</b>).

As redes <b>LSTM</b> são um tipo de rede neural recorrente (RNN) que são adequadas para dados de <b>séries temporais</b>. RNNs são um tipo de rede neural que pode manipular dados sequenciais, como texto ou dados de séries temporais. A principal diferença entre uma RNN e uma rede neural tradicional é que uma RNN pode lembrar informações de entradas anteriores, o que é importante para lidar com dados de séries temporais.

As redes <b>LSTM</b> são um tipo especial de RNN que são particularmente adequadas para dados de séries temporais. As redes LSTM têm uma "memória" que pode lembrar informações por longos períodos de tempo. Isso é importante para prever os preços das ações, *porque os preços das ações são dados de séries temporais*.

Para treinar uma rede LSTM para prever os preços das ações, primeiro precisamos coletar dados. Existem muitas fontes de dados que podem ser usadas para essa finalidade, mas uma fonte popular é o Yahoo! Finance. Depois de coletarmos os dados, podemos usá-los para treinar a rede LSTM.

O processo de treinamento envolve alimentar os dados na rede LSTM e dizer a ela para prever a próxima etapa de tempo. Por exemplo, se tivermos dados de 60 dias, alimentaríamos os dados de 59 dias na rede e pediríamos para prever o preço das ações para o 60º dia. Em seguida, compararíamos o preço previsto com o preço real e ajustaríamos a rede de acordo. Este processo é repetido por várias épocas, até que a rede convirja em uma boa previsão.

Uma vez que a rede tenha sido treinada, podemos usá-la para prever os preços futuros das ações. Para fazer isso, simplesmente alimentamos os dados das etapas de tempo anteriores na rede e pedimos que preveja a próxima etapa de tempo. Por exemplo, se quisermos prever o preço das ações para o 61º dia, alimentaríamos os dados do 60º dia na rede e pediríamos para prever o preço do 61º dia.

Existem muitas maneiras diferentes de abordar o problema da previsão de preços de ações, mas o uso de aprendizado de máquina, especialmente aprendizado profundo, é uma ferramenta poderosa que pode fornecer previsões precisas.

<<<<<<<< HEAD:README.md.txt
Aqui nesse vídeo vamos utilizar o Python com os pacotes <b>Keras, Pandas, Numpy e Matplotlib</b> para criar o modelo que prevê o preço das ações. 
========
Aqui nesse vídeo vamos utilizar o Python com os pacotes **Keras, Pandas, Numpy e Matplotlib** para criar o modelo que prevê o preço das ações. 
>>>>>>>> 2b58cfdbdd49c70c182270c2eb592b4bb6de54f1:README2.md
