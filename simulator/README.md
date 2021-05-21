## Descrição

Repositório do front-end feito com Golang (Backend)

**Importante**: A aplicação do Apache Kafka deve estar rodando primeiro.

## Configurar /etc/hosts

Adicionar a /etc/hosts (para Windows o caminho é C:\Windows\system32\drivers\etc\hosts):
```
127.0.0.1 host.docker.internal
```

## Rodar a aplicação

Executar os comandos:

```
docker-compose up -d
# Entrar no container
docker-compose exec app bash
# Rodar a aplicação Golang
go run main.go
```
