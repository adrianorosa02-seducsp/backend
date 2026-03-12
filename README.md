EDUARDO LAZARO ROESLER DE OLIVEIRA <eduardooliveira01@prof.educacao.sp.gov.br>	11 de março de 2026 às 19:13
Para: Adriano Justino Rosa <adrianorosa02@prof.educacao.sp.gov.br>
```
1) Command Prompt:
"C:\Program Files\Python313\"python --version

2) Command Prompt:
"C:\Program Files\Python313\"python -m venv venv

3) bash~:
$ source venv/Scripts/activate

4) bash~:
pip freeze > requirements.txt

5)requirements.txt:
Flask=3.0.2

6)bash~:
pip install -r requirements.txt

7) bash~
python -m pip freeze > requirements.txt

import psycopg2

try:
    conexao = psycopg2.connect(
        host="git.inetz.com.br",
        port=5432,
        user="appuser",
        password="appsenha",
        dbname="appdb"
    )

    print("Conectado ao banco de dados PostgreSQL!")

    conexao.close()

except Exception as erro:
    print("Erro ao conectar ao banco de dados:")
    print(erro)

8) bash~:
python app.py


8.5) Devemos criar o banco:
create database / create table usuarios
```

9) Atualizar código:
import mysql.connector
