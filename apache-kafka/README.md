## Descrição

Repositório do Apache Kafka (Backend)

## Configurar /etc/hosts

A comunicação entre as aplicações se dá de forma direta através da rede da máquina.
Para isto é necessário configurar um endereço que todos os containers Docker consigam acessar.

Acrescentar em /etc/hosts (para Windows o caminho é C:\Windows\system32\drivers\etc\hosts):
```
127.0.0.1 host.docker.internal
```

## Rodar a aplicação

Execute os comandos:

```
docker-compose up
```

Quando parar os containers do Kafka, antes de rodar o **docker-compose up**, rodar o **docker-compose down** para limpar o armazenamento, senão lançará erro ao subir novamente.
