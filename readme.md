principal header change:

```
<meta name="robots" content="index, follow">
	<link rel="canonical" href="https://dennamo.github.io/ninacarducci/">
	<link rel="icon" href="favicon.ico" type="image/x-icon">
	<title>Photographie Shooting Albums Retouches</title>
	<meta name="description"
		content="Shooting Photo, Tout Evenements, Mariage, Concert, Vancance, Profil, Entreprise, Personnel . Je me déplace sur Bordeaux/Île-de-France.">

	<!-- CSP -->
	<meta http-equiv="Content-Security-Policy" content="
			default-src 'self';
			script-src 'self' https://code.jquery.com unsafe-eval;
			style-src 'self' https://fonts.gstatic.com https://fonts.googleapis.com 'unsafe-inline';
			img-src 'self' data:;
			font-src 'self' https://fonts.gstatic.com;
			connect-src 'self' https://fonts.gstatic.com data:;
		">

	<!-- Twitter/X -->
	<meta name="twitter:card" content="summary_large_image">
	<meta name="twitter:site" content="@YourTwitterHandle">
	<meta name="twitter:title" content="Photographie Shooting Albums Retouches">
	<meta name="twitter:description"
		content="Pour capturer vos moments les plus précieux et garder un souvenir impérissable. Je me déplace en Île-de-France pour réaliser vos photos avec un résultat professionnel.">
	<meta name="twitter:image" content="https://dennamo.github.io/ninacarducci/assets/images/cover.jpg">

	<!-- Facebook  -->
	<meta property="og:title" content="Photographie Shooting Albums Retouches">
	<meta property="og:description"
		content="Pour capturer vos moments les plus précieux et garder un souvenir impérissable. Je me déplace en Île-de-France pour réaliser vos photos avec un résultat professionnel.">
	<meta property="og:image" content="https://dennamo.github.io/ninacarducci/assets/images/cover.jpg">
	<meta property="og:url" content="https://dennamo.github.io/ninacarducci/">
	<meta property="og:type" content="website">
	<meta property="og:site_name" content="Nina Carducci Photography">
	<meta property="og:locale" content="fr_FR">
	<meta property="og:image:width" content="1200">
	<meta property="og:image:height" content="630">
    ```



    principal other change:
    HTML:
    -conversion .webp
    -loading="lazy"
    -ajout attribut ALT
    -balises h1,h2,h3 fix
    -Label formulaire fix
    -defer et async sur certains script, d'autres sont critique et bloqueront le chargement de la page
    
    CSS:
    -photo de nina carducci, width réduite en max-width 660px + object fit sur le slider
    -Modification de la couleur du texte actif de gallery

