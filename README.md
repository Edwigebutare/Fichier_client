<!DOCTYPE html>
<html>
<head>
<style>
body {
background-color: Pink;

}
input[type=submit]{
background-color: green;
border: inset;
color:white;
cursor:pointer;
}
h1 {
color: black;
text-align:center;
}
p {
font-family:"Times New Roman", Times, serif;
font-weight: bold;
font-size: 20px;
text-align: center;
}
</style
</head>
<body>
<h1> Fichier client</h1>
<form style="justify-content: center; display: flex;">
<table>
<tr>
<td><br>
Nom:
</td>
<td><br>
<input type="text" placeholder="Nom" name="">
</td>
</tr>
<tr>
<td><br> 
Prénom:
</td>
<td><br>
<input type="text" placeholder="Prénom" name="">
</td>
</tr>
<tr>
<td>
<label for="quantity"><br> Age:</label>
</td>
<td><br>
<input type="number" id="quantity" name="quantity"min="1">
</td>
</tr>
<tr>
<td><br>
Sexe: 
</td>
<td><br>
<input type="radio" name="Gender">Femme
<input type="radio" name="Gender">Homme
</td>
</tr>
<tr>
<td><br>
Email:
</td>
<td><br>
<input type="mail" name="">
</td>
</tr>
<tr>
<td><br>
Type d'achat:
</td>
</tr>
<tr>
<td>
<input type="radio" id="Informatique" name="type d'achat" value="Informatique">
  <label for="Informatique">Informatique</label></td></tr>
  <br>
  <tr><td><input type="radio" id="Alimentaire" name="type d'achat" value="Alimentaire">
  <label for="Alimentaire">Alimentaire</label></td></tr>
  <br>
  <tr><td><input type="radio" id="Vetements" name="type d'achat" value="Vetements">
  <label for="Vetements">Vetements</label></td></tr>
  <br>
  <tr><td><input type="radio" id="Bijoux" name="type d'achat" value="Bijoux">
  <label for="Bijoux">Bijoux</label></td></tr>
  <br>
</tr>
</td>

<tr>
<td><br>
<label for="quantity"> Montant d'achat:</label>
</td>
<td><br>
<input type="number" id="quantity" name="quantity"min="1" >
</td>
</tr>
<tr>
<td>
<label for="quantity"><br> Nombre de partage:</label>
</td>
<td><br>
<input type="number" id="quantity" name="quantity"min="1">
</td>
</tr>
<tr>
<td><br>
<input type="submit" value="Envoyer" >
</td>
</tr>
</table>
</form>

</body>
</html>
