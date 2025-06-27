<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <Meu Portfólio>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <img src="Foto_perfil.jpeg" alt="Avatar de Vanessa" class="avatar">
    <h2>Eu sou Vanessa_</h2>
    <h1>Futura Médica Veterinária</h1>
    <p>
      Sou estudante do Ensino Médio e tenho o sonho de cursar Medicina Veterinária. Tenho paixão por animais, pelo cuidado com a natureza e gosto muito de aprender coisas novas. Esse portfólio mostra um pouco sobre mim
    </p>
    <h3>Minhas habilidades</h3>
    <div class="skills">
      <span>Comunicação</span>
      <span>Trabalho em grupo</span>
      <span>Boa ouvinte</span>
      <span>Criativa</span>
    </div>
  </header>

  <main>
    <h2>Meus projetos</h2>
    <section class="projects">

      <div class="card">
        <img src="ALUNA_DESTAQUE.png" alt="Biblioteca">
        
        <p>Aluna destaque de ciências da natureza e matemática.</p>
      </div>

      <div class="card">
        <img src="oqsp.jpeg" alt="IA">
    
        <p>Medalista da OQSP BRONZE.</p>
      </div>

      <div class="card">
        <img src="Foto_com_cachorro.jpeg" alt="Universo">
        
        <p>Objetivo de ter sua própria clinica.</p>
      </div>

    </section>
  </main>
</body>
</html>
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background: #f6f9fc;
  color: #1a1a1a;
  text-align: center;
}

header {
  padding: 40px 20px;
}

.avatar {
  width: 100px;
  border-radius: 50%;
  margin-bottom: 15px;
}
