# Funda-oBradesco
Desenvolvidos no curso de HTML e CSS

<!DOCTYPE html> <!--listas-->
<html>
 <head>
  <meta charset="utf-8">
   <title>listas</title>
 </head>
<body bgcolor=#b22222></body>
<img src="./img/lucro-bradesco.jpg"alt="fundação bradesco" width="300"> 
<table border="1">
	<tr>
		<td>Fundação Bradesco</td>
		<td>Apostila</td>
	</tr>
	<tr>
		<td>HTML</td>
		<td>CSS</td>
	</tr>
</table>
<hr>

<form action=”/deixaremos-em-branco” method=”post”>
	<label> Text: </label>
	<input type=”text”>
	<label> Password: </label>
	<input type=”password”>
	<label> Textarea: </label>
	<textarea> </textarea >
	<input type="checkbox" name="opcao" value="selectA" checked>clique para selecionar o A<br>
	<input type="checkbox" name="opcao" value="selectB">clique para selecionar o B<br>
	<input type="radio" name="opcao" value="selectA"  checked>Masculino
	<input type="radio" name="opcao" value="selectB">Feminino

<hr>

<label>campo visivel</label>
<input type="text"><br>
<label>campo invisivel</label>

<hr>

	<select>
		<option value="verde">Verde</option>
		<option value="vermelho">Vermelho</option>
		<option value="azul">Azul</option>
		<option value="alpha">Alpha</option>	
	</select>


	<button type="submit">Cadastrar</button>
 
</form>
  
 <ul>
   <h1>listas desordenadas</h1>
	<li><a href="http://fundacao.bradesco/">Fundação</a></li> <!--inserção de links-->
	<li>Bradesco</li>
 </ul>
 <ol>
   <h2>listas ordenadas</h2>
	<li>fundação</li>
	<li>bradesco</li>
 </ol>
<dl>
	<dt>A fundação</dt>
	<dd>Fundação Bradesco, entidade filantrópica sem fins lucrativos</dd>
<dl>

</body>
</html>
