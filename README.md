  <h1 align='center'>:computer: :arrow_right_hook: Data Pipeline with Kafka</h1>
O pipeline de dados realiza a coleta dos Twitter trending topics, faz a conexão com um banco do Postgres, verifica se o registro
capturado ja consta na tabela, caso não haja o registro é realizada a inserção do mesmo.

  <h2>:clipboard: Pré requisitos</h2>
Para utilizar o projeto será necessário instalar o Python 3 caso não tenha instalado além das bibliotecas utilizadas no projeto
Instalação do Python
Se o seu SO for o linux o Python já estará instalado, caso esteja utilizando o SO Windows o Python pode ser baixado e instalado no <a href="https://www.python.org/downloads/windows/">site</a> acesse, baixe e siga as orientações de instalação.

  <h4>:books: Instalação das bibliotecas</h4>
Para instalar as bibliotecas utilize os comandos abaixo:

```
pip install pytrends
pip install psycopg2
```

  <h2>:hammer_and_wrench: Construído com</h2>
O pipeline de dados foi construido utilizando a linguagem de programação Python a IDE PyCharm e as bilbiotecas 

  <h2>:rotating_light: Possiveis Problemas</h2>

```
$ export PATH=/usr/lib/postgresql/X.Y/bin/:$PATH
```

  <h2>:black_nib: Autores</h2>
Projeto criado por Cristiano Oliveira

  <h2>:pushpin: Versão</h2>
Version: 1.0.0

 <h2>:book: Referências</h2>
<a href="https://pypi.org/project/pytrends/">Pytrends</a>
<a href="https://www.psycopg.org/docs/">Psycopg2</a>

