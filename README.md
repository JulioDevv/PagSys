# Pagsys - Sistema de Gerenciamento de Pagamentos e Matrículas

O Pagsys é um sistema web desenvolvido para facilitar o gerenciamento de pagamentos e matrículas de cursos ministrados por uma professora. Ele oferece funcionalidades para administração de usuários, clientes, pagamentos, relatórios e muito mais.

## Funcionalidades

### Admin:

- Login com acesso total ao sistema.
- Gerenciamento de usuários e clientes (cadastrar, alterar, excluir).
- Visualização de relatórios e mensalidades.
- Acesso a todas as funcionalidades do sistema.

### Cliente/Usuário:

- Login com acesso restrito a funcionalidades específicas.
- Matrícula em cursos.
- Gerenciamento de usuários dependentes.
- Acesso aos meios de pagamento.

## Tecnologias Utilizadas

- Backend: MySQL, Node.js, Express.js.
- Frontend: [Em branco por enquanto].

## Configuração do Ambiente

### Windows:

1. **Node.js**: Baixe e instale o Node.js a partir do site oficial: [Node.js](https://nodejs.org/).
2. **Express.js**: Após instalar o Node.js, abra o terminal e execute o seguinte comando para instalar o Express.js globalmente:

    ```
    npm install -g express
    ```

3. **MySQL**: Baixe e instale o MySQL a partir do site oficial: [MySQL](https://www.mysql.com/).

### Linux:

1. **Node.js**: Abra o terminal e execute os seguintes comandos para instalar o Node.js:

    ```
    sudo apt update
    sudo apt install nodejs
    sudo apt install npm
    ```

2. **Express.js**: Após instalar o Node.js, execute o seguinte comando para instalar o Express.js globalmente:

    ```
    npm install -g express
    ```

3. **MySQL**: Para instalar o MySQL, execute os seguintes comandos no terminal:

    ```
    sudo apt update
    sudo apt install mysql-server
    ```

### macOS:

1. **Node.js**: Baixe e instale o Node.js a partir do site oficial: [Node.js](https://nodejs.org/).
2. **Express.js**: Após instalar o Node.js, abra o terminal e execute o seguinte comando para instalar o Express.js globalmente:

    ```
    npm install -g express
    ```

3. **MySQL**: Baixe e instale o MySQL a partir do site oficial: [MySQL](https://www.mysql.com/).

## Configuração do Projeto

1. Clone o repositório do projeto:

    ```
    git clone https://github.com/seu-usuario/pagsys.git
    ```

2. Instale as dependências do projeto:

    ```
    cd pagsys
    npm install
    ```

3. Configuração do Banco de Dados: [Instruções de configuração do MySQL aqui].

4. Execute o servidor:

    ```
    node app.js
    ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir pull requests ou criar issues para discutir novas funcionalidades, problemas ou melhorias.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).
