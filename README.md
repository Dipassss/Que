# Prueba1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prueba 1</title>
    <link rel="stylesheet" href="main.css">
</head>
<body>

    <div class="header">
        <img class="pequeña" src="logo.png"/>
        <div class="header-right">
          <a href="Inicio">Inicio</a>
          <a href="#Servicios">Servicios</a>
          <a href="#Contacto">Contacto</a>
          <a href="#Ayuda">Ayuda</a>
          <a href="#Iniciar Sesión">Iniciar Sesión</a>
        </div>
      </div>

    <h1>Evaluacion Sumativa 1</h1><b></b>
    <h2>Aprendiendo CSS</h2>
    <p>hhbfgabfgshbhghhf</p>
<div>
    <button type="button">Aprender mas</button>
</div>

 </div>
</body>
</html>

*{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: rgba(114, 89, 255, 0.2);
}

img.pequeña{
border-radius: 4px;
    height: 100%;
    width: 10%;
    text-align: left;
    margin: 10px;
    font-size: small;
    background-color: aliceblue;
}
body{
    text-align: center;
}
.header {
    overflow: hidden;
    background-color:blueviolet;
    padding: 20px 10px;
    margin-bottom: 50px;
    
  }
  
 
  .header a {
    float: left;
    color: rgb(248, 245, 245);
    text-align: center;
    padding: 12px;
    text-decoration: none;
    font-size: 18px;
    line-height: 25px;
    border-radius: 4px;
  }
  
  .header a.logo {
    font-size: 25px;
    font-weight: bold;
  }
  
 
  .header a:hover {
    background-color: rgba(114, 89, 255, 0.2);
    color: rgb(194, 24, 194);
  }
  
  
  .header a.active {
    background-color: blueviolet;
    color: rgb(255, 255, 255);
  }
  

  .header-right {
    float: right;
  }
  button{
    background-color: blueviolet;
    text-align: center;
    padding: 12px;
    border-radius: 40px;
  }
  

  @media screen and (max-width: 500px) {
    .header a {
      float: none;
      display: block;
      text-align: left;
      cursor: pointer ;
    }
    .header-right {
      float: none;
    }
    button.active{
        float: none;
        display: block;
        text-align: left;
        cursor: pointer ;

    }
}
