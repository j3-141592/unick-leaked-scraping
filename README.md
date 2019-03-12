# unick-leaked-scraping
Web scraping of Unick Forex leaked page to build a CSV file

Os dados dos clientes da **Unick Forex** foram vazados no site: https://unickbgv.000webhostapp.com/

Cada cliente possui um código único, e os dados individuais podem ser acessados passando o parametro "x" pelo método GET, ou seja, acessando a URL https://unickbgv.000webhostapp.com/?x=CODIGO

O que esse robô faz é acessar todos os códigos individuais de cada cliente, varrendo os dados cadastrais e salvando em um arquivo texto em formato CSV (campos separados por ; para facilitar a importação).

Programa feito para fins de estudo. Favor não compartilhar o arquivo CSV.

Lembrando que o que esse robô faz é apenas compilar em um arquivo CSV os dados de um website público.
