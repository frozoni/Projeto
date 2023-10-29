# **Links para COLAB, Google Driver**

**Projeto no COLAB (https://colab.research.google.com/drive/1M464foGO5HeDJUxONR4urt9T_jcsIpJm?usp=sharing)**

**Google Driver com os arquivos, COLAB (https://drive.google.com/drive/folders/1qM0RzFDwETJD9sVbOZb2V3gllZ9ZfuhW?usp=sharing)**

# **Descrição do Projeto SiCoop_DB**

  Nesse projeto, iniciei pela inclusão das tabelas dentro do SQl Server, o desenho do MER e a ingestão de dados (Não reais),
como não foi exposto um arquivo modelo (csv, xls) ou qualquer outro tipo de base, resolvi à partir do site generatedate.com para gerar esses dados para fazer a ingestão.
Acredito que um dos desafios foi criar os dados, pois não havia qualquer modelo de informação ou padrão a ser seguido, porém o tempo proposto para execução do projeto como um todo foi bem adequeado, visto que a ingestão, tratamento e entrega dos dados não foi de grande volume, conforme mencionava o desafio.

  Como não havia um provedor de Nuvem (Azure, AWS ou GCP) para salvar os dados nem o Banco de Dados, optei pelo uso no COLAB (**SiCoop_DB.ipynb**)e criar o banco de dados por la, usando o **SiCoop_DB.db** (Em anexo aqui no Git), por ele fiz todo o processo que faria no meu Notebokk local, Criei o Banco de Dados, Tabelas, ingestão dos dados, converti para pandas e posteriormete para Pyspark e fiz o Join para uma tabela unica modificando os nomes das colunas e salvei a nova tabela como **movimento_flat.csv**.
  
  Foram incluidos os arquivos **Diagrama_Sicoop_DB**, onde mostro o diagrama de MER feito no Microsoft SQL e o **Dados.jpg** é o print da tela do SMSS onde fiz um join com as tabelas criadas no SQL Server.

# **Projeto Notebook_Simulador**

  Aproveito aqui o GIT para deixar um outro projeto criado o **Noteboo_Simulador.ipynb**, que foi um projeto meu com dados também não reais com bases em .csv que estvam bem "sujas", fiz todo o processo de ETL no COLAB, os arquivos para executar o notebook, estão no google Drive a qual compartilhei a pasta no link acima , na pasta **Base_Case**.
