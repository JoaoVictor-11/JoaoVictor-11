## Hi there 👋

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Perfil no GitHub</title>
   <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #333;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }
    .card {
      background: #fff;
      width: 90%;
      max-width: 500px;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 1rem;
    }
    .card h1 {
      font-size: 1.5rem;
      margin-bottom: .25rem;
    }
    .card p.bio {
      font-style: italic;
      margin-bottom: 1rem;
      color: #555;
    }
    .stats {
      display: flex;
      justify-content: space-around;
      margin-bottom: 1rem;
    }
    .stats div {
      text-align: center;
    }
    .stats div span {
      display: block;
      font-weight: bold;
      margin-top: .25rem;
    }
    .repos {
      text-align: left;
    }
    .repos h2 {
      font-size: 1.25rem;
      margin-bottom: .5rem;
      border-bottom: 1px solid #eee;
      padding-bottom: .25rem;
    }
    .repos ul {
      list-style: none;
    }
    .repos li {
      margin-bottom: .5rem;
    }
    .repos a {
      color: #0366d6;
      text-decoration: none;
    }
    .repos .stars {
      margin-left: .5rem;
      color: #888;
      font-size: .9rem;
    }
  </style>
</head>
<body>

  <div class="card">
    <!-- Avatar -->
    <img src="Foto-de-perfil.jpeg" alt="Avatar do usuário"/>

    <!-- Nome / Login -->
    <h1>JoaoVictor-11</h1>
    <!-- Biografia -->
    <p class="bio">Olá, meu nome é João Victor Andrade, tenho 18 anos e estou cursando o primeiro período de ciências da computação na Uniesp, e quero me tornar um excelente profissional!</p>

    <!-- Estatísticas -->
    <div class="stats">
      <div>
        <div>Seguidores</div>
        <span>1</span>
      </div>
      <div>
        <div>Seguindo</div>
        <span>3</span>
      </div>
      <div>
        <div>Repositórios</div>
        <span>1</span>
      </div>
    </div>

    <!-- Repositórios -->
    <div class="repos">
      <h2>Últimos repositórios</h2>
      <ul>
        <li>
          <a href="https://github.com/usuario/repo1" >repo1</a>
          <span class="stars">★ 30</span>
        </li>
        <li>
          <a href="https://github.com/usuario/repo2" >repo2</a>
          <span class="stars">★ 15</span>
        </li>
        <li>
          <a href="https://github.com/usuario/repo3" >repo3</a>
          <span class="stars">★ 8</span>
        </li>
        <!-- Adicione mais <li> conforme necessário -->
      </ul>
    </div>
  </div>

</body>
</html>
