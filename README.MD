# ml-iris-prediction

A Flask API that consumes a prediction model trained by the Logistic Regression Classification algorithm. Deploy with IaC and Github Actions using Docker and Kubernetes on GCP.

# Deploy local:

1. Após executar o git clone execute os comandos abaixo na raiz do projeto:

```
python3 -m venv venv

source venv/bin/activate  # Unix/macOS
# ou
venv\Scripts\activate  # Windows

pip install -r requirements.txt

python3 app.py
```

Documentação em Swagger:

```
http://127.0.0.1:5000/apidocs
```

Obs: Após instalar uma dependência nova, para atualizar o arquivo requirements.txt execute o comando abaixo:

```
pip freeze > requirements.txt
```

# Deploy with Vercel:

1. Crie uma conta no vercel.com;
2. Crie um novo projeto;
3. Selecione o projeto do seu GitHub:
4. Agora é so clicar em Deploy.
5. Pronto aparecerá a mensagem Congratulation.
