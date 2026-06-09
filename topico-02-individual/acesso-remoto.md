# Acesso remoto por SSH

## Estado do serviço SSH
Serviço ativo e em execução na porta 22.

## Endereço identificado
Extraído com o comando hostname -I.

## Comando de ligação
```bash
ssh root@$(hostname -I | awk '{print $1}')
```

## Limitações encontradas
Isolamento de rede nativo do ambiente Killercoda.
