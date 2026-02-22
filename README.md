Entrega-do-Desafio
Descrição
Este repositório contém materiais relacionados a ataques de força bruta, incluindo scripts, configurações e arquivos auxiliares para estudo e testes.

Objetivo
Descrever claramente o propósito:

Estudo de redes
Testes de segurança em ambiente controlado
Automação de tarefas
Estrutura do Projeto
/scripts → Scripts utilizados no projeto
/wordlists → Listas auxiliares para testes
Requisitos
Infraestrutura de Virtualização
VirtualBox
Rede configurada como Host-Only, isolada da internet
Sistemas Operacionais
Kali Linux, máquina utilizada para execução dos testes
Metasploitable 2, máquina vulnerável utilizada como alvo
Ferramentas Utilizadas
Medusa, para testes de autenticação
Serviços nativos expostos na Metasploitable 2, como FTP e SMB
Como utilizar
Clone o repositório: git clone https://github.com/seu-usuario/nome-do-repositorio.git

Acesse a pasta: cd Entrega-do-Desafio

Mitigação
Força Bruta: Desativar FTP simples e usar SFTP Limitar tentativas de login Implementar bloqueio por IP Senhas fortes com política obrigatória MFA quando possível SMB: Política de senha forte Bloqueio após tentativas falhas Monitoramento de autenticações distribuídas Restringir SMB apenas à rede interna Auditoria de contas antigas ou inativas

Aviso
Este projeto é destinado exclusivamente para fins educacionais e testes em ambientes autorizados.
