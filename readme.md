# Simulando um Ataque de Brute Force de Senhas com Medusa e Kali Linux

O objetivo deste projeto é a execução prática e a documentação formal de um exercício de segurança ofensiva. O foco principal é a utilização da distribuição Kali Linux e da ferramenta Medusa para simular ataques de força bruta em ambientes de teste controlados (Metasploitable 2, DVWA).

O propósito é duplo: entender a mecânica da intrusão e, subsequentemente, desenvolver e propor medidas de defesa eficazes.

## Etapas de Execução

O projeto deve ser conduzido de forma estruturada, seguindo os passos abaixo:

1. Configuração do Ambiente Virtual

    Infraestrutura: Utilizar o VirtualBox para hospedar as máquinas virtuais necessárias: o sistema operacional de ataque (Kali Linux) e o sistema-alvo vulnerável (Metasploitable 2).

    Conexão: É obrigatório estabelecer uma Rede Interna (Host-Only), garantindo que o ambiente de teste esteja isolado e que a comunicação entre as VMs seja gerenciada de forma segura.

2. Condução dos Ataques Simulados

    Aplicar a ferramenta Medusa para comprometer credenciais nos seguintes serviços:

    Protocolo FTP: Ataque de força bruta direcionado ao serviço File Transfer Protocol.

    Aplicações Web (DVWA): Automação de tentativas de login em formulário web presente na plataforma DVWA.

    Serviço SMB: Execução de ataque de password spraying no serviço Server Message Block, incluindo a etapa prévia de enumeração de usuários para otimização da lista de alvos.

3. Documentação e Análise de Segurança

A documentação é um componente essencial e deve ser apresentada de forma organizada:

    Registro de Procedimentos: Detalhamento das wordlists (listas de senhas) simples empregadas, além do registro exato dos comandos utilizados e da validação do acesso obtido.

    Recomendações Técnicas: Elaboração de propostas de mitigação para cada vetor de ataque explorado, visando o aumento da segurança dos serviços.

### Installation

A step by step guide that will tell you how to get the development environment up and running.

```
$ First step
$ Another step
$ Final step

```

### Branches

* Master;