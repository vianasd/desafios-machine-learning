<h1>Meu programa foi feito no google colab em python</h1>

<b>Dessa maneira para acessá-lo:</b>

1º Se não possuir conta no google:

(Você conseguirá ver o código, porém não conseguirá executá-lo)
<ul>
<li>Você deve acessar o link  --> <a href="https://colab.research.google.com/drive/1qhkuYmejKcraI7PKgJyZodzgKewKiEci">Projeto</a></li>
</ul>

2º Se possuir conta no google, você pode acessar o link anterior, pois
habilitei a edição para a execução do código, ou se prefirir:
<ul>
<li>Entrar no google colab, link --> <a href="https://colab.research.google.com/notebooks/intro.ipynb">Colab.Google</a></li>

<li>Apertar na palavra File no canto superior esquerdo.</li>

<li>Apertar em upload notebook(Para tal será necessário estar logado em uma conta do google)</li>

<li>Apertar em upload.</li>

<li>Escolher arquivo.</li>

<li>Pegue o arquivo DeepLearning.ipynb.</li>
</ul>

A primeira sessão aborda informações detalhadas descrevendo como treinar/importar o dataset e rodar o programa, visto que é necessário
somente apertar botões em sequência da forma de um quadrado --> [ ]

<b>Com relação ao que eu fiz simplificadamente</b>


Eu busquei vários modelos para o treinamento para ter maior chance de achar um que mais se adaptasse ao conjunto
de dados sem ocorrer overfitting. Nesse aspecto, no pré-processamento fiz um tratamento nos dados que julguei necessário,
levando em consideração o dataset que eu possuía. Já no processamento, foquei minha verificação na accuracy, visto que 
um sistema preditivo de doença pode gerar incomodos se der tanto Falso-Positivo quanto Falso-Negativo. Todavia, calculei também
o recall e o f1 score caso seja interessante para a sua análise. Nesse âmago, verifiquei a accuracy tanto no sistema de 
treinamento quanto no de teste para verificar qual modelo havia se adaptado melhor ao modelo sem ser incapaz de prever novos
dados e para finalizar o processo de validação e testes, eu fiz uma pequena conclusão sob meu ponto de vista que obtive nesses
dias de estudo.

