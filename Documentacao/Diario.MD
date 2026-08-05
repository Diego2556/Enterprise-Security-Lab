# Diário do Projeto

## Dia 1 - 01/08/2026

- Organização das pastas do laboratório.
- Instalação do Git.
- Instalação do VirtualBox.
- Instalação do Extension Pack.
- Download do Windows Server 2022.
- Download do Windows 11 Enterprise.
- Criação do repositório no GitHub.
- Primeiro diagrama da topologia da rede.

## Dia 2 - Active Directory

### Atividades realizadas

- Configuração de IP fixo (192.168.100.10)
- Instalação da função Active Directory Domain Services (AD DS)
- Promoção do servidor para Controlador de Domínio
- Criação do domínio `empresa.local`
- Exploração inicial da ferramenta Active Directory Users and Computers

### Estrutura observada

- Builtin: grupos internos do Windows.
- Computers: computadores que ingressam no domínio.
- Domain Controllers: controladores de domínio.
- Users: usuários e grupos padrão.
- ForeignSecurityPrincipals: objetos de outros domínios.
- Managed Service Accounts: contas gerenciadas para serviços.

### Aprendizados

- O Active Directory centraliza usuários, computadores e políticas da empresa.
- O servidor SRV-01 agora é o Controlador de Domínio do ambiente `empresa.local`.

## Dia 2 - Active Directory
## Administração do Active Directory

### OUs criadas

- TI
- RH
- Financeiro
- Computadores
- Servidores

### Usuário criado

- Nome: Diego Pilon
- Login: diego.pilon

### Aprendizados

- OUs servem para organizar objetos do Active Directory.
- Usuários do domínio podem fazer login em qualquer computador que pertença ao domínio.
- O Active Directory centraliza a autenticação dos usuários.