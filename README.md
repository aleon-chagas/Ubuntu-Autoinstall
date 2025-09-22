# Ubuntu-Autoinstall

Automação completa para instalação do Ubuntu 24.04 LTS, voltada para ambientes DevOps, SRE e uso workstation pessoal.

## Objetivo

Facilitar e padronizar a instalação do Ubuntu utilizando o recurso de autoinstall, realizando desde a configuração de pacotes, repositórios e aplicativos essenciais até ajustes de teclado, idioma, timezone, e automações pós-instalação.

## Recursos

- Instalação automática dos pacotes necessários para desenvolvimento, automação e produtividade
- Configuração de layout de teclado ABNT2 (br) e US International, com alternância via Alt+Shift
- Pré-configuração de timezone brasileiro, locale em pt_BR e drivers adicionais
- Instalação automatizada de:
  - Docker, Kubernetes, Terraform, AWS CLI, Azure CLI
  - Ferramentas DevOps e utilitários populares
  - Navegadores (Google Chrome, Vivaldi), editores e aplicativos de trabalho
  - Extensões GNOME e customizações do ambiente
- Scripts de pós-instalação para limpar pacotes, atualizar banco de arquivos, ativar terminal Tilix e configurar shell ZSH automaticamente

## Uso

1. Faça download do arquivo `autoinstall.yaml` e personalize conforme necessário (usuário, pacotes, scripts).
2. Insira o arquivo no instalador do Ubuntu via método oficial, disco externo ou pendrive com `user-data` ou usando `cloud-init`.
3. Siga as instruções do repositório para instalar e validar as configurações automáticas.

## Contribuições

Sugestões e melhorias são bem-vindas! Abra issues ou envie pull requests para adicionar novos pacotes, scripts ou automatizações.

---

> Este projeto visa agilizar ambientes DevOps, SRE e Workstation, reunindo modelos prontos para instalação sem intervenção manual.
