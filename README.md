# Cypress, do Zero à Nuvem

Projeto de Exemplo – Curso "Cypress: do Zero à Nuvem" (Talking About Testing)

## Pré-requisitos

Para clonar e executar este projeto, é necessário ter o Git, Node.js e npm instalados.

> Usei as versões 2.48.1, v22.14.0 e 10.9.2 do Git, Node.js e NPM, respectivamente. Sugiro que você use as mesmas versões ou versões posteriores.

## Instalação

Execute `npm install` (ou `npm i` para a versão curta) para instalar as dependências de desenvolvimento.

## Testes

Neste projeto, é possível executar os testes em uma janela de visualização para desktop ou dispositivos móveis.

### Desktop

Execute `npm test` (ou, de forma abreviada, `npm t`) para rodar os testes em modo headless, usando uma viewport de desktop (ou seja, sem abrir a interface gráfica do Cypress).

Se preferir visualizar os testes sendo executados, use o comando `npm run cypress:open` para abrir a interface do Cypress, também em modo desktop.

### Mobile

Execute `npm run test:mobile` para rodar os testes em modo headless, simulando a visualização em um dispositivo móvel (sem abrir a interface gráfica do Cypress).

Se quiser acompanhar a execução visualmente, use npm run `cypress:open:mobile` para abrir a interface do Cypress já configurada com uma viewport móvel.
