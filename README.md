# Firebird-JB-Soft
Para usar o sistema JB Suite (Cepil) com o Firebird rodando em um container Docker, basta rodar copiar este arquivo e rodar com o *docker-compose*

```
docker-compose -f "docker-compose.yaml" up -d --build 
```

Na configuração do caminho para o banco:

```
localhost:/firebird/data/NOME_DO_ARQUIVO.FDB
```
