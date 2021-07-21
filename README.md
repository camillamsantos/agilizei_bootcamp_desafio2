
# Projeto Chapter 2 - Bootcamp Cypress - Turma 6 - Desafio do Chapter #2

# Bootcamp Agilizei - Desafio 02


![N|Solid](https://www.cypress.io/static/33498b5f95008093f5f94467c61d20ab/59c46/cypress-logo.webp)



Projeto desenvolvido para o bootcamp turma 6 agilizei - https://agilizei.com/agilizei-bootcamp/

# Tecnologias

  - Cypress @ 7.7.0
  - NodeJS @ v14.17.3
  - NPM @ 7.19.2

# Dependências

  - faker js
  - mocha: @ 9.0.2
  
# Desafio

  - Criar teste para cadastrar novo usuário
  - Criar teste para login do usuário cadastrado
  - Criar teste para criar e publicar um artigo
  - Implementar page objects
  - Adicionar asserções nas specs usando rotas e validações em tela
  - Organizar o código da cadastro.spec.js separando:
        Em etapas (Preparação, Ação e Validação) - conceito AAA (Arrange/ Action/ Assert)
        Em responsabilidades (Page Objects)
        Avaliar se é necessário usar ou cadastrar uma nova rota


# Passos para executar o projeto

  - Clonar o repositório
  - Dentro da raiz do projeto, executar o comando [npm install]
  - Executar os comandos a seguir para rodar os testes em modo headless nos navegadores:
  
    - Electron: [npm run cy:run:electron]
    - Chrome: [npm run cy:run:chrome]
    - Firefox: [npm run cy:run:firefox]
    - Edge: [npm run cy:run:edge]


Caso deseje visualizar a reprodução dos vídeos após executar os testes em modo headless, basta acessar o diretório cypress/videos. 
A seguir seguem gifs com testes executados em modo headless via console do VScode. 

  - Testes em modo headless via console do VsCode ![headless](https://user-images.githubusercontent.com/84816792/125380001-ea7b0700-e367-11eb-9ab9-2ece372d9c0d.gif)
  
  - Testes executados no Azure DevOps ![agilizei_bootcamp_desafio2_azure]()

  - Vídeo da página de Cadastro ![cadastro](https://user-images.githubusercontent.com/84816792/125380392-8278f080-e368-11eb-836b-d1015fae3d13.gif)

  - Vídeo da página de Login ![login](https://user-images.githubusercontent.com/84816792/125380580-c7048c00-e368-11eb-94a5-804b6c9e6fd5.gif)

  - Vídeo da página de Artigos ![artigos](https://user-images.githubusercontent.com/84816792/125380708-016e2900-e369-11eb-8a15-f42cb4b36523.gif)
  

### Azure Pipeline + Reports

O projeto está configurado para rodar em uma pipeline da azure.

https://dev.azure.com/camillamsantossm/Agilizei%20Bootcamp%20N%C3%ADvel%202/_build/results?buildId=4&view=results


