# **Descrição do Projeto SiCoop_DB**

**Link para o Projeto no COLAB (https://colab.research.google.com/drive/1M464foGO5HeDJUxONR4urt9T_jcsIpJm?usp=sharing)**
**Link para PAsta do Google Driver com os arquivos, COLAB (https://drive.google.com/drive/folders/1qM0RzFDwETJD9sVbOZb2V3gllZ9ZfuhW?usp=sharing)**


Nesse projeto, iniciei pela inclusão das tabelas dentro do SQl Server, o desenho do MER e a ingestão de dados (Não reais),
como não foi exposto uma csv, xls, ou qualquer outro tipo de base, resolvi à partir do site generatedate.com para gerar esses dados para fazer a ingestão.
O maior desafio foram criar os dados, pois não havia qualquer modelo de informação ou padrão a ser seguido, O tempo proposto foi bem adequeado.
Como não havia um provedor de Nuvem para salvar os dados nem o Banco de Dados, optei pelo uso no COLAB e criar o banco de dados por la, usando o SiCoop_DB (Em anexo aqui no Git), por ele fiz a ingestão dos dados e o Join no final e salvando o movimento_flat como CSV.
Foram incluidos os arquivos Dados.jpg e o Diagrama_Sicoop_DB, onde mostro o diagrama de MER feito no Microsoft SQL e o Dados.jpg é o print da tela do SMSS onde fiz um join com as tabelas criadas no SQL Server.

Aproveito aqui o GIT para deixar um outro projeto criado o Noteboo_Simulador.ipynb, que foi um projeto meu mesmo com dados também não reais com bases em .csv que estvam bem "sujas", fiz todo o processo de ETL no COLAB.
