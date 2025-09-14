# Oficina de Extração e Manipulação de Dados com API, Python e SQL

Este repositório contém exemplos práticos utilizados na **Oficina de Extração e Manipulação de Dados**, com foco em **APIs, Python e SQL**

## Como executar os exemplos

### 1. Crie um ambiente virtual

### 2. Instale as dependências
```
 pip install requests   
 pip install pandas
 pip install psycopg2 
```
### 3. Instale JupyterLab
* Instale o JupyterLab
* Após instalar o JupyterLab, Execute:
```
 jupyter lab                                                            
```

### 3. Configure o banco de dados
* Instale o PostgreSQL em sua máquina.
* Crie um banco de dados para testar os exemplos.
* Altere os parâmetros de conexão de banco de dados no arquivo **db.py**
```
"dbname": "seu_banco",
"user": "seu_usuario",
"password": "sua_senha",
"host": "localhost",
"port": "5432"
```