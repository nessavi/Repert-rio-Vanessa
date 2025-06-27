<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfólio da Vanessa</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <img src="Foto_perfil.jpeg" alt="Avatar de Vanessa" class="avatar" />
    <h2>Eu sou Vanessa_</h2>
    <h1>Futura Médica Veterinária</h1>
    <p>
      Sou estudante do Ensino Médio e tenho o sonho de cursar Medicina Veterinária.
      Tenho paixão por animais, pelo cuidado com a natureza e gosto muito de aprender coisas novas.
      Esse portfólio mostra um pouco sobre mim.
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
      <div class="img-container">
        <img src="ALUNA_DESTAQUE.jpg" alt="Aluna Destaque" />
        <img src="oqsp.jpg" alt="Projeto escolar" />
        <img src="Foto_com_cachorro.jpg" alt="Com cachorro" />
      </div>
    </section>
  </main>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f8f8f8;
  color: #333;
}

header {
  text-align: center;
  padding: 30px;
  background-color: #e6f2f1;
}

.avatar {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #4db6ac;
  margin-bottom: 20px;
}

h1, h2, h3 {
  margin: 10px 0;
}

.skills {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 15px;
}

.skills span {
  background-color: #4db6ac;
  color: white;
  padding: 8px 12px;
  border-radius: 20px;
  font-size: 14px;
}

main {
  padding: 40px 20px;
  text-align: center;
}

.img-container {
  display: flex;
  justify-content: center;
  gap: 15px;
  flex-wrap: wrap;
  margin-top: 20px;
}

.img-container img {
  width: 180px;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}
