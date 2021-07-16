# Utilizando API's de Python, plotamos um gráfico e geramos imagens e QRCode

Para requisitar o link da URL, utilizamos a API de requests

A fonte de dados desse estudo é da API = url = 'https://api.covid19api.com/dayone/country/brazil'

As imagens foram geradas através de IPython.display e PIL

Para modificar as datas para serem plotadas no gráfico da forma que visualizamos normalmente, importamos também a biblioteca datatime

Para gerar o link do QRCode da imagem gerada do gráfico, utilizamos a biblioteca urllib e função .parse