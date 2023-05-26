
# Documentação do Projeto Galeria

## Visão Geral
O projeto Galeria é uma aplicação web que permite aos usuários visualizarem e navegarem por uma coleção de imagens. A galeria é desenvolvida utilizando as seguintes tecnologias: Bootstrap, jQuery e Webpack.

## Requisitos
Antes de iniciar a instalação e execução do projeto, certifique-se de ter os seguintes requisitos instalados em seu ambiente de desenvolvimento:

- Node.js: versão 10 ou superior
- NPM (Node Package Manager): versão 6 ou superior

## Instalação
Siga os passos abaixo para instalar e configurar o projeto Galeria:

1. Clone o repositório do projeto para o seu ambiente local:

   ```shell
   git clone <URL do repositório>
   ```

2. Navegue até o diretório do projeto:

   ```shell
   cd galeria
   ```

3. Instale as dependências do projeto utilizando o NPM:

   ```shell
   npm install
   ```

4. Após a conclusão da instalação, o projeto está pronto para ser executado.

## Execução
Para executar o projeto Galeria, siga os passos abaixo:

1. No diretório do projeto, execute o seguinte comando:

   ```shell
   npm run start
   ```

2. Aguarde até que a compilação seja concluída e o servidor de desenvolvimento seja iniciado.

3. Abra um navegador da web e acesse a seguinte URL:

   ```
   http://localhost:3000
   ```

4. A aplicação da Galeria será carregada no navegador, e você poderá começar a navegar pela coleção de imagens.

## Estrutura do Projeto
O projeto Galeria possui a seguinte estrutura de diretórios e arquivos principais:

- `src/`: Diretório principal do código-fonte da aplicação.
  - `index.js`: Arquivo de entrada do aplicativo, responsável por inicializar a aplicação e carregar os recursos necessários.
  - `components/`: Diretório que contém os componentes reutilizáveis da aplicação.
  - `styles/`: Diretório que contém os arquivos de estilo da aplicação.
- `public/`: Diretório que contém os arquivos estáticos da aplicação, como imagens e ícones.
- `webpack.config.js`: Arquivo de configuração do Webpack, que define como os arquivos do projeto devem ser compilados e empacotados.

## Personalização
Caso deseje personalizar a aparência ou o comportamento da aplicação Galeria, você pode fazer as seguintes modificações:

- Editar os arquivos de estilo em `src/styles/` para alterar a aparência visual da galeria.
- Modificar ou adicionar novos componentes em `src/components/` para personalizar o comportamento da aplicação.

Certifique-se de reconstruir e reiniciar o projeto após fazer qualquer modificação relevante.

## Conclusão
A documentação acima fornece uma visão geral do projeto Galeria, incluindo informações sobre a instalação, execução, estrutura do projeto e personalização. Agora você está pronto para utilizar a aplicação e adaptá-la de acordo com suas necessidades.
