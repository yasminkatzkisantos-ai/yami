<!DOCTYPE html>
  <html lang="PT-BR">
      <head>
          <title>FrontEnd</title>
          <meta charset="utf-8">
          <link rel="stylesheet" type="text/css" href="">
          <script></script>
      </head>
      <style>
          .body{
            background-color: yellow;
            color:red;
          }
          .texto{
            color:purple;
          }
          .submit{
            background-color: green;
          }
          .foto{
            background-image: url("https://editorial.uefa.com/resources/0287-195e642735d8-f09b9f6da9f8-1000/topshot-fbl-award-ballon_d_or-2023.jpeg");
            width:300px;
            height:200px;
            background-size: 50%;
            background-repeat: no-repeat;
          }
      </style>
      <body class="body">
          Bom dia, esse é o primeiro codigo de html
        <form method="POST" action="index.php">
            <fieldset>
                <legend>
                  Login
                </legend>
                <br>
                <p class="texto">Usuario:</p> <input type="text" placeholder="Usuario" minlength="5" maxlength="10" required><br>
                <p class="texto">Senha:</p>   <input type="password" placeholder="Senha" minlength="5" maxlength="10" required><br>
                <input type="submit" value="Registrar" class="submit">
            </fieldset>
            <fieldset>
                <legend>Cadastro</legend>
                Nome <input type="text"><br>
                Sobrenome <input type="text"><br>
                Data de Nascimento <input type="date"><br>
                M <input type="checkbox"><br>
                F <input type="checkbox"><br>
                Observações<textarea></textarea><br>
                Canhoto <input type="radio"><br>
                Destro <input type="radio"><br>
                CPF <input type="number"><br>
                RG <input type="number"><br>
                Endereço <input type="text"><br>
                CEP <input type="number"><br>
                Arquivo <input type="file"><br>
                <h1>INTER, MELHOR TIME DO MUNDO</h1><br>
                <h2>INTER, MELHOR TIME DO MUNDO</h2><br>
                <h3>INTER, MELHOR TIME DO MUNDO</h3><br>
                <h4>INTER, MELHOR TIME DO MUNDO</h4><br>
                <h5>INTER, MELHOR TIME DO MUNDO</h5><br>
                <h6>INTER, MELHOR TIME DO MUNDO</h6><br>
            </fieldset>
        </form>
      </body>
  </html>
