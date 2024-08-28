# Data-Analise-With-Excel
A partir de tabelas no excel utilizar python para gerar análises mais precisas acerca das informações
Para rodar este código será necessário importar a biblioteca pandas e a biblioteca matplotlib.pyplot
para importar a tabela neste código foi utilizado o drive e o google colab desta forma:
from google.colab import drive
drive.mount('/content/drive')
Assim seu drive ja foi importado, mas para acessar o seu arquivo é necessário especificar o arquivo com seu diretório
e definir sua database, desta forma:
file_path = '/content/drive/My Drive/Rossmann.xlsx'
database = pd.read_excel(file_path)
Esses são os requisitos para rodar o código na sua máquina.
