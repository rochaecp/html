# Formulários:

- action=página que receberá dados
- method=post(via transação pós HTTP) ou get(dados visíveis na URL)
- required=torna campo obrigatório
- disabled=desabilita campo
- autofocus=foca cursor
- pattern=para validar campo, por exemplo CEP pattern="\d{5}-?\d{3}" -->

~~~html
<form action="dados.php" method="post">
  <!-- Básicos: -->
  <h2>Inputs básicos:</h2>
  Nome: <input type="text" name="" id="" placeholder="texto" required><br />
  Senha: <input type="password" placeholder="senha" maxlength="5" value=""><br />
  Data de nascimento: <input type="date" min="1992-01-15" max="2192-01-15"><br />
  Quantidade: <input type="number" min="0" max="1000" step="10"><br />
  Quantidade: <input type="range" min="0" max="1000" step="10"> <br /><br />
  Arquivo: <input type="file" name="imagem"><br />

  <!--Radio-Button Checked já deixa marcado -->
  <h2>Radio-Button:</h2>
  <input type="radio" name="genero" value="male" checked> Male <br>
  <input type="radio" name="genero" value="female"> Female <br><br>

  <!--Checkbox -->
  <h2>Checkbox:</h2>
  <input type="checkbox" name="vehicle" value="Bike" checked>I have a bike<br>
  <input type="checkbox" name="vehicle" value="Car">I have a car <br /><br />

  <!--Select, o optgroup é opcional -->
  <h2>Select:</h2>
  <select>
    <optgroup label="Normais">
      <option value="terra">Terra</option>
      <option value="lua">Lua</option>
      <option value="marte">Marte</option>
    </optgroup>
    <optgroup label="Alternativos">
      <option value="outro" selected>Azectobrischptal</option>
    </optgroup>
  </select> <br /><br />

  <!-- Textarea -->
  <h2>Textarea:</h2>
  <textarea name="" rows="5" cols="30" spellcheck="true"></textarea><br>

  <!-- Button -->
  <h2>Button e input type="button":</h2>
  <button>Sou um button</button><br />
  <input type="button" value="Enviar"><br />
  <input type="submit" value="Enviar formtarget" formtarget="_blank"><br />
  <input type="submit" value="Enviar formaction" formaction="script.php"><br />
  <input type="submit" value="Enviar formmethod" formmethod="GET"><br />
  <input type="submit" value="Enviar formnovalidate" formnovalidate><br />

  <!-- Outros -->
  <h2>Outros:</h2>
  <input type="text" placeholder="text disabled" disabled> <br />
  <input type="hidden" name="id"> hidden <br />
  <input type="email" placeholder="email" autocomplete="on"> <br />
  <input type="text" placeholder="CEP com validação" required pattern="\d{5}-?\d{3}" /> <br />
  <input type="url" placeholder="url"> <br />
  <input type="search" placeholder="search" name="busca"> <br />
  <input type="tel" placeholder="tel" name="telefone"> <br />
  <input type="text" placeholder="fora do form" form="cadastro"> <br />

  <input type="time" name="hora"> <br />
  <input type="month"> <br />
  <input type="week"> <br />
  <input type="datetime-local"><br />

  <input type="color" name="cor"> <br />
  <input name="Lista" list="habilidades">
  <datalist id="habilidades">
    <option value="HTML5">
    <option value="CSS3">
  </datalist>
</form>
~~~
