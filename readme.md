O acesso está disponível apenas na porta 7070. As portas 81 e 82 foram desabilitadas para acesso, assim o acesso é somente por meio do balanceador.

## Pré requisitos

- Docker / Docker-Compose
- Git instalado

## Testar a Aplicação:

```bash
docker-compose up -d
```
Logs da Aplicação:

```bash
docker-compose logs -f
```

Acesso Web:
- http://localhost:7070 (Blog Wordpress)
- http://localhost:7070/haproxy_status (Estatísticas do HaProxy)