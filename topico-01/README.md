# Tópico 1 - Preparação do ambiente Linux

## Ambiente utilizado
Linux no browser através da plataforma Killercoda (Ambiente Ubuntu 24.04), executado através do Trilho B.

## Objetivo desta atividade
Preparar o ambiente Linux e organizar a primeira evidência técnica.

## Estrutura criada
A estrutura de diretórios criada para o projeto foi:
- linux-seguranca-cloud/
  ├── topico-01/
  │   ├── evidencias/
  │   ├── comandos-topico-01.txt
  │   └── README.md
  └── produto-final/

## Comandos executados
* `uname -a` - Identificação do sistema e kernel.
* `cat /etc/os-release` - Identificação da distribuição Linux.
* `whoami` - Consulta do utilizador atual.
* `pwd` - Exibição do diretório de trabalho.
* `df -h` - Verificação do espaço em disco.
* `free -h` - Análise da memória RAM do sistema.

## Diferença entre VM, VPS e infraestrutura em nuvem
* **VM (Máquina Virtual):** É uma emulação de um computador físico completo que corre isolada dentro de um servidor hospedeiro utilizando um hipervisor.
* **VPS (Virtual Private Server):** É um servidor virtual isolado e vendido como um serviço por provedores, onde uma máquina física é dividida em várias instâncias com recursos dedicados.
* **Infraestrutura em nuvem:** É um ecossistema mais amplo de recursos virtuais computacionais, redes e armazenamento interligados, permitindo escalabilidade elástica e pagamento sob demanda.

## Dificuldades encontradas
Instabilidade da máquina virtual temporária do Killercoda que expira por tempo de inatividade, exigindo processos repetidos de configuração e clonagem, além da digitação de comandos em ecrãs reduzidos de dispositivos móveis.

## Próximos passos
Armazenar e validar as credenciais de autenticação pessoal (Personal Access Token) do GitHub de forma persistente para automatizar os envios e iniciar as atividades práticas de gestão de utilizadores do Tópico 2.
