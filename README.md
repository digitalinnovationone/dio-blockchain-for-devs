

# dio-blockchain-for-devs

## Pré-requsitos

### Instalar o NodeJS com NPM:

- https://nodejs.org/en/download/

### Instalar o VS Code: 

- https://code.visualstudio.com/download

### Download do Ganache: 

- https://trufflesuite.com/ganache/

### Instalação do Metamask: 

- https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en

## Instruções

## O projeto

### Clonar o repositório e acessar o projeto:

- git clone https://github.com/digitalinnovationone/dio-blockchain-for-devs.git

- cd dio-blockchain-for-devs

### Instalar os pacotes do NPM: 

- npm i

### Instalar o Framework Truffle: 

- npm i -g truffle

## Configurações
 
 - Executar o Ganache
 
 ### No Metamask
 
  - Criar a nova carteira no Metamask e salvar a seed
  
  - Criar uma nova rede com a RPC URL: http://127.0.0.1:7545
  
  - O nome e o símbolo são personalizadas (DIOCoin) (DIO)
  
### Importando conta do Ganache no Metamask

 - Selecionar a chave privada de um dos endereços (no símbolo da chave) no Ganache
 
 - Importar conta no Metamask passando a chave privada

## Compilando o contrato

- truffle compile

## Deploy na blockchain

- truffle deploy

## Realizando transações

- Irão solicitar a aprovação da transação no Metamask




