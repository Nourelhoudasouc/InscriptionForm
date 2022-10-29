<!DOCTYPE html>
<html lang="fr">
<head>
	<meta charset="utf-8">
	<title>ex03</title>
	<meta name="keywords" content="web, html">
</head>
<body>
	<form method="GET" action="script.php">
		<fieldset>
			<legend><b>Candidat:</b></legend>
			<fieldset>
			<legend><b>Identité:</b></legend>
			<label>Sexe</label>
			<select name="SITUATION">
				<option value="f">Femme</option>
				<option value="h" selected>Homme</option>
			</select>
			<label>Situation</label>
			<select name="etat">
				<option value="m">marié(e)</option>
				<option value="c">célébataire</option>
			</select><br><br>
			<label>Non/prenom</label>
			<input type="text" placeholder="entrer votre non"><br><br>
			<label>Adresse</label><br>
			<textarea>Rue numero &#10boite postale
			</textarea><br><br>
			<label>Code Postale/ville</label>
			<input type="text" maxlength="5">
			<input type="text" value="Alger">
			<label>wilaya</label>
			<select name="wilaya">
				<option value="01">01 Adrar</option>
				
				<option value="16"selected>16 Alger</option>
			</select>
			</fieldset>
			<fieldset>
				<legend><b>Connaissance en informatique</b></legend>
				<label>Plateforme(s):</label>
				<input type="checkbox" checked>windows
				<input type="checkbox" >Mac
				<input type="checkbox" >LINUX
				
			</fieldset>
			<label>Envoyer votre cv detaillé</label>
			<input type="file" accept=".pdf,.docx">(pdf ou docx)
			</fieldset>
			<input type="submit" value="valider" >
			<input type="reset" value="effacer" >
	</form>
</body>
</html>
