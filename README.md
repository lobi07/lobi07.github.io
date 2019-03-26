<!Doctype html>
<html lang="fr">
	<head>
		<title>Curriculum_Vitae</title>
		<meta name="keywords" content=" Biret, CV lorry"/>
		<meta name="description" content="Curriculum_Vitae"/>
		<meta charset="utf-8">
		<link href= "style_cv.css" rel="stylesheet">

	</head>

	<header>
		<div class="bandeau">
			<img src="C:\Users\utilisateur\Desktop\CV_Html\visage.jpg" class="photo">
			<img src="C:\Users\utilisateur\Desktop\CV_Html\mailIcone.png" class="imgMail">
			<p><a href="mailto:biretlorry@rocketmail.com" title="Mon adresse mail" class="	mail">biretlorry@rocketmail.com</a></p><br>

			<img src="C:\Users\utilisateur\Desktop\CV_Html\telIcone.png" class="imgTel">
			<p class="tel">(+687)80.02.88</p>	

			<h1 class ="titre">Curriculum Vitae</h1>

			
		</div>
	</header>

	<!-- Corp-->

	<body>
	
		

		<div class="info_perso">
			Lorry BIRET <br>
			22 ans<br>
			Yahoué, Mont-Dore<br>
			<strong>Permis B et véhicule</strong>
		</div>
	<div class="form_exp">
		<h2 class ="formation"><u>Formations</u>:</h2>
		<ul class="formation_list">
			<li>Niveau 2ème année de Licence Informatique (2018/UNC)</li>
			<li>Baccalauréat Scientifique (2015/Lycée Du Grand Nouméa)</li>
			<li>Brevet Des Collèges (2011/Collège De Thio)</li>
		</ul>

		<h2 class="exp-pro"><u>Expérience Professionelles</u>:</h2>
		<ul class="exp-pro_list">
			<li><strong>Equipier au McDonald</strong>(Mont-Dore (3 septembre - 3 novembre 2018) (CDD).<br>
			<u>Objectifs</u>:Préparation des produits McDonald, tenue des stocks.</li><br>
			<li><strong>Assistant Technicien</strong>(OPT Nouméa) (4 décembre - 30 décembre 2017) (Job d’été).<br>
			<u>Objectifs</u> : Dépannage, mise à jour des logiciels et remplacement du matériel informatique.</li><br>
			<li><strong>Aide Promoteur</strong> (GBNC Nouméa) (5 décembre – 30 décembre 2016) (Job d’été).<br>
			<u>Objectifs</u> : Mise en place de la publicité de l’entreprise dans des grandes surfaces, magasins et bars.</li><br>
			<li><strong>Pompiste</strong> (Shell Auteuil) (janvier 2015) (CDD).<br>
			<u>Objectifs</u> : Remplissage des réservoirs automobiles, contrôle des niveaux, gonflage des pneus.</li><br>
			<li><strong>Pompiste</strong> (Shell Tontouta) (novembre – décembre 2013) (Job d’été).<br>
			<u>Objectifs</u> : Remplissage des réservoirs automobiles, contrôle des niveaux, gonflage des pneus.</li><br>
			<li><strong>Vendeur</strong> (Supérette Vaiana - Thio) (novembre – décembre 2012) (Job d’été).<br>
			<u>Objectifs</u> : Agencement des rayons, contrôle des marchandises et des livraisons.</li><br>
		</ul>
	</div>
	<div class="list_info">
		<h2 class="compétences"><u>Compétences</u>:</h2>
		<ul>
			<li>Pratique du langage C</li>
			<li>SQL</li>
			<li>HTML/CSS</li>
			<li>Suite Microsoft</li>
		</ul>
		<h2 class="qualités"><u>Qualités</u></h2>
		<ul>
			<li>Ponctuel</li>
			<li>Motivé</li>
			<li>Volontaire</li>
			<li>Sociable</li>
		</ul>
		<h2 class="loisirs"><u>Loisirs</u></h2>
		<ul>
			<li>Basket-Ball</li>
			<li>Volley-Ball</li>
			<li>Pêche</li>
			<li>Mécanique auto/moto/vélo</li>
		</ul>
	</div>
	</body>
</html>

body{
	font-family: Calibri;
	display:block;
	margin-right: auto;
	

	
	
}

h1{
	color: yellow;
	float: right;
	bottom: 105px;
	right: 100px;
}

h2{
	color: yellow;
	font-style: italic;
	font-family: Calibri;
}


.photo{
	max-width: 130px;
	float:right;
	display: block;
	margin-right: 30px;
	margin-top: -7px;

}

.imgMail{
	width: 50px;
	float: left;
}

.mail{
	background-color: white;
	display: block;
	color: black;
	border-style: dashed;
	height:20px;
	width:200px; 
	margin-left: 47px;

	
}

.imgTel{
	width: 60px;
	float: left;
}

.tel{
	background-color: white;
	display: block;
	color: black;
	border-style: dashed;
	margin-left:50px;
	margin-right: 500px;
}


.bandeau{
	background-color: 255,30,50;
	display: block;
	border-style: solid;

	width: 740px;
}

.titre{
	display:block;
	text-align: center;
	position: relative;
	
}


.info_perso{
	display: block;
	border-style:solid;
	width: 250px;
	margin-top: 20px;	
}

.form_exp{
	display:block;
	border-style:solid;
	width: 475px;
	margin-left: 265px;
	margin-top: -82px; 
}


.list_info{
	display: block;
	border-style:solid;
	width: 250px;
	margin-top: -694px;
	height: 688px;	
}


