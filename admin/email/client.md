---
layout: post
title: "Utiliser un client mail"
author: service-informatique
rank: 4
summary: Gérer vos mails avec des logiciels comme Outlook, Thunderbird, ... et même votre smartphone !
icon: uil-monitor
---

Si vous avez plusieurs adresse mail (perso, pro, ...), vous utilisez peut-être déjà un logiciel (Outlook, Mail pour Mac ou Windows, ...) 
permettant de **récupérer** et **envoyer**  des mails sur votre ordinateur. 
Cette approche a de nombreux avantages, car elle permet (entre autre) :

1. de regrouper **toutes vos boîtes mails au même endroit**,
2. d'**enregistrer le mot de passe** (pas besoin de le rentrer à chaque fois),
3. d'accéder à tous vos **anciens mails sans accès internet**.

Si vous n'en n'utilisez pas encore, nous recommandons fortement :

- [**Thunderbird**](https://www.thunderbird.net/fr/) : un peu comme Outlook, mais gratuit, open-source, et surtout beaucoup moins source de problèmes.

Dans tout les cas, lors de la configuration initiale du compte, voici les réglages à utiliser :

## Configuration du serveur entrant

:scroll: _Pour recevoir les mails ..._

- type de serveur : **IMAP** (:warning: et **jamais POP** !!!)
- nom d'utilisateur : _[adresse mail @cssb.fr complète]_
- adresse du serveur : **mail.cssb.fr**
- n° de port : 993

## Configuration du serveur sortant (SMTP) 

:scroll: _pour envoyer des mails ..._

- nom d'utilisateur : _[adresse mail @cssb.fr complète (encore si demandé)]_
- adresse du serveur : **mail.cssb.fr**
- type de sécurité (si demandé) : **SSL/TLS**
- n° de port : 465

> :mega: Ce sont exactement ces mêmes réglages qui peuvent être utilisés pour récupérer vos mails sur smartphone, 
> par exemple via l'appli GMail (`Ajouter un autre compte / Autre ...`).


