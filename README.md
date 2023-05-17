# Sistema-de-RH
Sistema de RH feito em PHP!


Para configurar a conexão com o banco de dados, será necessário passar os parámetros de conexão, como o host, user, pass e o db.
Acessa a pasta "application/config/database.php", e altera segundo o seu servidor, quer seja local ou partilhado...

No caso:

Se for localmente, com XAMPP ou WAMPP

hostname: localhost
username: root
password: 
database: sistema_rh

Encontrarás a pasta "Arquivo de Banco de Dados", nele encontrarás o arquivo "sql", abrindo o phpmyadmin, cria um banco de dados com o nome "sistema_rh", 
e uma vez criado, poderás importar o arquivo .sql que encontrarás na pasta "Arquivo de Banco de Dados". E depois é só colocar o projecto, se for no XAMPP, na pasta "htdocs", e se for WAMPP, na pasta "www".
E iniciar os servidores.  Obrigado!
