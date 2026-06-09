# Permissões aplicadas

## Ambiente utilizado
Linux no browser (Killercoda / Ubuntu 24.04).

## Utilizador e grupos
- **Utilizador:** root
- **Grupos:** root

## Permissões aplicadas
| Ficheiro | Permissão | Justificação |
|---|---:|---|
| publico.txt | 644 | Dono lê/escreve, grupo/outros apenas lêem. |
| restrito.txt | 640 | Dono lê/escreve, grupo apenas lê, outros sem acesso. |
| script.sh | u+x | Execução exclusiva para o utilizador dono. |

## Relação com o princípio do menor privilégio
Garante que cada utilizador ou processo tenha apenas o acesso estritamente necessário para a sua função, reduzindo a superfície de ataque caso o sistema seja comprometido.
