<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PAGSYS - Sistema de Gerenciamento de Pagamentos e Matrículas</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f4f4f4;
      padding: 20px;
    }

    .container {
      max-width: 800px;
      margin: auto;
      background: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    h1 {
      text-align: center;
      color: #333;
    }

    h2 {
      color: #333;
    }

    p {
      margin-bottom: 20px;
      color: #666;
    }

    code {
      background: #f4f4f4;
      padding: 5px;
      border-radius: 5px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin-bottom: 10px;
    }

    a {
      color: #007bff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    pre {
      background: #f4f4f4;
      padding: 10px;
      border-radius: 5px;
      overflow-x: auto;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>PAGSYS - Sistema de Gerenciamento de Pagamentos e Matrículas</h1>
    <p>Um sistema web desenvolvido para facilitar o gerenciamento de pagamentos e matrículas em cursos ministrados por uma professora.</p>

    <h2>Visão Geral</h2>
    <p>Este sistema permite que a professora gerencie os pagamentos dos seus alunos, acompanhe relatórios financeiros, cadastre novos clientes e usuários, além de oferecer aos alunos a possibilidade de realizar matrículas em cursos oferecidos.</p>

    <h2>Tecnologias Utilizadas</h2>
    <ul>
      <li><strong>Banco de Dados:</strong> MySQL</li>
      <li><strong>Backend:</strong> Node.js com Express.js</li>
      <li><strong>Frontend:</strong> (adicione aqui se houver)</li>
    </ul>

    <h2>Pré-requisitos</h2>
    <p>Certifique-se de ter as seguintes tecnologias instaladas em seu sistema:</p>

    <h3>Windows</h3>
    <ul>
      <li><a href="https://nodejs.org/">Node.js</a> (inclui npm)</li>
      <li><a href="https://dev.mysql.com/downloads/installer/">MySQL</a></li>
    </ul>

    <!-- Incluir instruções para Linux e macOS aqui -->

    <h2>Configuração do Ambiente</h2>
    <ol>
      <li>
        <strong>Configurando o MySQL:</strong>
        <ul>
          <li>Crie um banco de dados com o nome <code>nome_do_banco</code>.</li>
          <li>Importe o esquema do banco de dados a partir do arquivo <code>schema.sql</code>.</li>
        </ul>
      </li>
      <li>
        <strong>Configurando o Node.js e Express.js:</strong>
        <ol>
          <li>Clone este repositório.</li>
          <li>Instale as dependências:</li>
        </ol>
        <pre><code>npm install</code></pre>
        <ol start="3">
          <li>Execute o servidor:</li>
        </ol>
        <pre><code>node server.js</code></pre>
        <p>O servidor estará rodando em <a href="http://localhost:3000">http://localhost:3000</a>.</p>
      </li>
    </ol>

    <h2>Funcionalidades</h2>
    <ul>
      <li><strong>Login:</strong> Os usuários podem fazer login como admin ou cliente.</li>
      <li><strong>Admin:</strong>
        <ul>
          <li>Acesso total ao sistema.</li>
          <li>Gerenciamento de pagamentos, relatórios, clientes e usuários.</li>
        </ul>
      </li>
      <li><strong>Cliente/Usuário:</strong>
        <ul>
          <li>Acesso aos meios de pagamento.</li>
          <li>Matrícula em cursos.</li>
          <li>Pagamentos.</li>
          <li>Cancelamento de matrículas.</li>
        </ul>
      </li>
    </ul>

    <h2>Licença</h2>
    <p>[Incluir licença aqui]</p>
  </div>
</body>
</html>
