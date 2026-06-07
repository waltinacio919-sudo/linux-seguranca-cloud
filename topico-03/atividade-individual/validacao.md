# Validação WordPress
## URL testado
`http://localhost/wp-admin/install.php` (Simulação de ambiente local)

## Resultado obtido
A estrutura de diretórios e ficheiros de configuração foi validada com sucesso via terminal.

## Relação entre WordPress, servidor web, PHP e base de dados
O WordPress assenta numa arquitetura de três camadas: O utilizador faz o pedido ao Nginx, que reencaminha os ficheiros .php para o PHP-FPM, que por sua vez consulta o MariaDB para montar a página.
