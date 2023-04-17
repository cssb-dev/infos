---
layout: post
title: "Signature officielle pour l'envoi d'email"
author: sdsi
short-description: Comment personaliser vos email avec une signature officiel CSSB
rank: 1
---

----

1. [Format pour les membres de compagnies](#format-pour-les-membres-de-compagnies)
2. [Format pour les membres du bureau national ou CSAO](#format-pour-les-membres-du-bureau-national-ou-csao)
3. [Utiliser la signature avec RoundCube ou un client mail](#utiliser-la-signature-avec-roundcube-ou-un-client-mail)

## Format pour les membres de compagnies

Dans la plupart des clients ou interface mail, il est possible d'ajouter une signature au format HTML pour les message envoyés. Voici le code de base qu'il faut utiliser :

```html
<div id="sig" style="min-height: 60px; 
	line-height: 17px; margin: 0; padding: 10px 0; 
	font-family: 'Lucida Grande', Verdana, Arial, Sans-Serif; 
	font-size: 12px; color: #03146e; min-width: 530px;" >
<img src="https://docs.cssb.fr/assets/logo-cssb.webp" 
    height="72" 
    style="float: left; padding: 0 10px 0 0;">
<strong style="color: #03146e; font-size:12px;">

<!-- A MODIFIER : Mettre ici votre identité : prénom, nom (en majuscule) et votre fonction -->
Prénom NOM | Fonction
<!-- Fin identité -->

</strong><br />
<!-- A MODIFIER : Mettre ici votre compagnie et ville -->
<i> Nième Compagnie "La Meilleure", Ville </i><br />
<!-- Fin compagnie -->
<i><strong> Compagnie Secouriste Sainte Barbe </strong></i><br />

<!-- A MODIFIER : Mettre ici le numéro de téléphone, ou un vide -->
T&eacute;l. 01 23 45 67 89 -
<!-- Fin numéro de téléphone -->

Suivez notre actualit&eacute; sur : <a 
    href="http://www.cssb.fr" 
    style="color:#b01809; 
        text-decoration:none; 
        border-bottom: 1px #333333 dotted;">
    www.cssb.fr</a>
</div>
```

Ajoutez les informations vous correspondant dans les parties `A MODIFIER`, à savoir :

1. **Identité** : `Prénom NOM | Function`, par exemple `Albert DUPOND | Secrétaire Délégué`. Notez le _nom de famille en majuscule_.
2. **Compagnie** : `Nième Compagnie "La Meilleure", Ville`, par exemple, `1ère Compagnie "De France", Paris`.
3. **Numéro de téléphone** (facultatif). 

> :bulb: Si vous ne souhaitez pas mettre votre numéro de téléphone dans la signature, supprimez simplement la ligne entre `<!-- A MODIFIER : ... -->` et `<!-- Fin numéro de téléphone -->`.

###### Exemple de rendu avec numéro de téléphone :

<div id="sig" style="min-height: 60px; 
	line-height: 17px; margin: 0; padding: 10px 0; 
	font-family: 'Lucida Grande', Verdana, Arial, Sans-Serif; 
	font-size: 12px; color: #03146e; min-width: 530px;" >
<img src="https://docs.cssb.fr/assets/logo-cssb.webp" 
    height="72" 
    style="float: left; padding: 0 10px 0 0;">
<strong style="color: #03146e; font-size:12px;">

<!-- A MODIFIER : Mettre ici votre identité : prénom, nom (en majuscule) et votre fonction -->
Prénom NOM | Fonction
<!-- Fin identité -->

</strong><br />
<!-- A MODIFIER : Mettre ici votre compagnie et ville -->
<i> Nième Compagnie "La Meilleure", Ville </i><br />
<!-- Fin compagnie -->
<i><strong> Compagnie Secouriste Sainte Barbe </strong></i><br />

<!-- A MODIFIER : Mettre ici le numéro de téléphone, ou un vide -->
T&eacute;l. 01 23 45 67 89 -
<!-- Fin numéro de téléphone -->

Suivez notre actualit&eacute; sur : <a 
    href="http://www.cssb.fr" 
    style="color:#b01809; 
        text-decoration:none; 
        border-bottom: 1px #333333 dotted;">
    www.cssb.fr</a>
</div>

###### Exemple de rendu sans numéro de téléphone :

<div id="sig" style="min-height: 60px; 
	line-height: 17px; margin: 0; padding: 10px 0; 
	font-family: 'Lucida Grande', Verdana, Arial, Sans-Serif; 
	font-size: 12px; color: #03146e; min-width: 530px;" >
<img src="https://docs.cssb.fr/assets/logo-cssb.webp" 
    height="72" 
    style="float: left; padding: 0 10px 0 0;">
<strong style="color: #03146e; font-size:12px;">

<!-- A MODIFIER : Mettre ici votre identité : prénom, nom (en majuscule) et votre fonction -->
Prénom NOM | Fonction
<!-- Fin identité -->

</strong><br />
<!-- A MODIFIER : Mettre ici votre compagnie et ville -->
<i> Nième Compagnie "La Meilleure", Ville </i><br />
<!-- Fin compagnie -->
<i><strong> Compagnie Secouriste Sainte Barbe </strong></i><br />

<!-- A MODIFIER : Mettre ici le numéro de téléphone, ou un vide -->
<!-- Fin numéro de téléphone -->

Suivez notre actualit&eacute; sur : <a 
    href="http://www.cssb.fr" 
    style="color:#b01809; 
        text-decoration:none; 
        border-bottom: 1px #333333 dotted;">
    www.cssb.fr</a>
</div>

<br>

## Format pour les membres du bureau national ou CSAO

Même idée que précedement, mais avec un code simplifié **sans information de compagnie** :

```html
<div id="sig" style="min-height: 60px; 
	line-height: 17px; margin: 0; padding: 10px 0; 
	font-family: 'Lucida Grande', Verdana, Arial, Sans-Serif; 
	font-size: 12px; color: #03146e; min-width: 530px;" >
<img src="https://docs.cssb.fr/assets/logo-cssb.webp" 
    height="72" 
    style="float: left; padding: 0 10px 0 0;">
<strong style="color: #03146e; font-size:12px;">

<!-- A MODIFIER : Mettre ici votre identité : prénom, nom (en majuscule) et votre fonction -->
Prénom NOM | Fonction
<!-- Fin identité -->

</strong><br />
<i> Compagnie Secouriste Sainte Barbe </i><br />

<!-- A MODIFIER : Mettre ici le numéro de téléphone, ou un vide -->
T&eacute;l. 01 23 45 67 89 
<!-- Fin numéro de téléphone -->

<br/>
Suivez notre actualit&eacute; sur : <a 
    href="http://www.cssb.fr" 
    style="color:#b01809; 
        text-decoration:none; 
        border-bottom: 1px #333333 dotted;">
    www.cssb.fr</a>
</div>
```

###### Exemple de rendu avec numéro de téléphone :

<div id="sig" style="min-height: 60px; 
	line-height: 17px; margin: 0; padding: 10px 0; 
	font-family: 'Lucida Grande', Verdana, Arial, Sans-Serif; 
	font-size: 12px; color: #03146e; min-width: 530px;" >
<img src="https://docs.cssb.fr/assets/logo-cssb.webp" 
    height="72" 
    style="float: left; padding: 0 10px 0 0;">
<strong style="color: #03146e; font-size:12px;">

<!-- A MODIFIER : Mettre ici votre identité : prénom, nom (en majuscule) et votre fonction -->
Prénom NOM | Fonction
<!-- Fin identité -->

</strong><br />
<i> Compagnie Secouriste Sainte Barbe </i><br />

<!-- A MODIFIER : Mettre ici le numéro de téléphone, ou un vide -->
T&eacute;l. 01 23 45 67 89 
<!-- Fin numéro de téléphone -->

<br/>
Suivez notre actualit&eacute; sur : <a 
    href="http://www.cssb.fr" 
    style="color:#b01809; 
        text-decoration:none; 
        border-bottom: 1px #333333 dotted;">
    www.cssb.fr</a>
</div>

###### Exemple de rendu sans numéro de téléphone :

<div id="sig" style="min-height: 60px; 
	line-height: 17px; margin: 0; padding: 10px 0; 
	font-family: 'Lucida Grande', Verdana, Arial, Sans-Serif; 
	font-size: 12px; color: #03146e; min-width: 530px;" >
<img src="https://docs.cssb.fr/assets/logo-cssb.webp" 
    height="72" 
    style="float: left; padding: 0 10px 0 0;">
<strong style="color: #03146e; font-size:12px;">

<!-- A MODIFIER : Mettre ici votre identité : prénom, nom (en majuscule) et votre fonction -->
Prénom NOM | Fonction
<!-- Fin identité -->

</strong><br />
<i> Compagnie Secouriste Sainte Barbe </i><br />

<!-- A MODIFIER : Mettre ici le numéro de téléphone, ou un vide -->
---
<!-- Fin numéro de téléphone -->
<br/>
Suivez notre actualit&eacute; sur : <a 
    href="http://www.cssb.fr" 
    style="color:#b01809; 
        text-decoration:none; 
        border-bottom: 1px #333333 dotted;">
    www.cssb.fr</a>
</div>

<br>

## Utiliser la signature avec RoundCube ou un client mail

:hammer_and_wrench: EN CONSTRUCTION :hammer_and_wrench:

- Utiliser la signature dans RoundCube
- Utiliser la signature dans Thunderbird
- Utiliser la signature dans Outlook
- Utiliser la signature avec un smartphone 