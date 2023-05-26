Projeto Node.js com Express

Este é um projeto Node.js desenvolvido para atender aos requisitos do desafio de Desenvolvimento Back-end II. A aplicação utiliza o framework Express e tem como objetivo criar endpoints que respondem a requisições HTTP.

Configuração e Instalação

Para executar este projeto, você precisará ter o Node.js instalado em sua máquina. Em seguida, siga as etapas abaixo:

1- Clone o repositório do GitHub para o seu ambiente local.
2- Navegue até a pasta raiz do projeto.
3- Execute o comando npm install para instalar as dependências do projeto, incluindo o Express, o Eslint e o Express Generator.

Estrutura de Arquivos
A estrutura de arquivos do projeto é organizada da seguinte forma:

├── node_modules/          # Pasta contendo as dependências do projeto

├── app.js                 # Arquivo principal da aplicação

├── package.json           # Arquivo de configuração do projeto

├── package-lock.json      # Arquivo de controle de versão das dependências

├── .eslintrc.json         # Arquivo de configuração do Eslint

└── README.md              # Este arquivo README


Endpoints Disponíveis

A aplicação possui os seguintes endpoints:

1- GET /: Endpoint raiz da aplicação.

2- GET /clientes: Endpoint para obter informações dos clientes.

3- POST /clientes: Endpoint para criar um novo cliente.

4- PUT /produtos: Endpoint para atualizar informações de um produto.

5- DELETE /produtos: Endpoint para excluir um produto.

Executando a Aplicação

Após a instalação das dependências e a configuração do projeto, você pode executar a aplicação usando o seguinte comando: node app.js

Isso iniciará o servidor na porta padrão 3000. Você pode acessar os endpoints mencionados acima usando um cliente HTTP, como cURL ou um navegador web.
