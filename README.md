# CriarProjetoAngular
Projeto para demonstração de como criar o primeiro sistema utilizando Angular

# Requisitos
- Node.js
    - Gerenciado através do nvm
- nvm (node version manager)
    - https://github.com/coreybutler/nvm-windows

# Passos
## Instalação do nodejs através do nvm
- nvm install 18.13.0
    - Instalar uma versão do node.js através do nvm
- nvm use 18.13.0
    - Definir a versão instalada como a atual
    - Acesso negado? Abrir terminal como administrador
- Dica: nvm list
    - Lista as versões instaladas e qual versão está ativa

## Instalação do Angular
- Instalar Angular
    - npm install -g @angular/cli
- Habilitar opções de segurança necessárias
    - Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

## Repositório github
- Criar Repositório github
- Clonar repositório na máquina local

## Criar Projeto Angular
- ng new PrimeiroProjetoAngular

## Executar aplicação
- ng serve

## Commitar projeto para github
- git add -A
- git commit -m "Primeiro commit"
- git push

## PLUS
- Pode ser utilizado o angular material ou bootstrap para angular (ou ambos)
