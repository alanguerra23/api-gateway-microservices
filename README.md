# Api Gateway com Kong

**Crie a rede para o kong**

```bash
docker network create kong-net
```

**Inicie o Banco de Dados do Kong**

```bash
cd kong/
docker-compose up -d db
docker-compose ps
```

Assim que o banco de dados iniciar, execute o kong e o konga

```bash
docker-compose up -d
docker-compose ps
```
**Inicie os Micro Serviços em Go Lang**

```bash
docker-compose up -d
```
