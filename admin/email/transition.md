---
layout: post
title: "Changement de nom d'adresse mail"
author: service-informatique
rank: 4
summary: Comment faire lors du changement de nom d'une adresse mail CSSB
icon: uil-sync-exclamation
---

1. [Explications](#explications)
2. [Dénominations](#dénominations)
2. [Procédure](#procédure)

## Explications

Dans un objectif de **simplification** :partying_face:, certaines adresses mail peuvent être renommées avec des noms plus courts, comme par exemple `vicepresident.delegue.timbuktu@cssb.fr` =>`vicepresident.timbuktu@cssb.fr`.

Le changement n'est pas simple, et nécessite différentes manipulations, comme :

- la création d'une nouvelle adresse email (avec le nom simplifié), ainsi que du compte google associé à cette nouvelle adresse
- la migration des messages, dossiers et listes de contact de l'ancienne boite mail à la nouvelle
- le transfert des droits d'accès Google Drive de l'ancien compte google au nouveau
- le transfert automatique des mails reçus de l'ancienne adresse à la nouvelle adresse, avec un message d'avertissement (si possible)
- après une période de transition, la suppression de l'ancienne boite mail et du compte google associé.

_Afin que cette transition se fasse dans le plus de douceurs possible, voici les quelques étapes qui sont à suivre ..._ :innocent:

## Dénominations

- `old@cssb.fr` : l'ancienne adresse email
- `new@cssb.fr` : la nouvelle adresse email
- `le ReMI` : Référent Moyens Internet  

## Procédure

1. **Création de la nouvelle adresse mail** :fireworks:

`new@cssb.fr` est crée par le ReMI, 
et un mail pour l'initialisation du mot de passe est envoyé à `old@cssb.fr`. 
`new@cssb.fr` est ajoutée sur les mailings listes 
auquelles était inscrite `old@cssb.fr`, 
et un compte Google associé à `new@cssb.fr` est créé.

> :mega: Lorsque vous recevez le mail d'initialisation du mot de passe, pensez au plus simple : utiliser le même que celui de l'ancienne adresse mail :wink:

2. **Prise en main** :hammer_and_wrench:

Peut après la réception du mail d'initialisation de mot de passe sur `old@cssb.fr`, le ReMi envois un mail pour indique que l'étape 1 est finie, 
et donne par la même occasion le mot de passe du compte Google associé à `new@cssb.fr`.

Dès lors, le détenteur (ou la détentrice) de `old@cssb.fr` peut transférer les mails, dossiers et contacts sur `new@cssb.fr`, et se connecter au compte Google associé.
Aussi, il peut mettre en place [sa nouvelle signature](./signature.md) sur `new@cssb.fr`.

> :bell: Cette étape se fait assez facilement si vous utilisez Thunderbird, Outlook ou équivalent. Si vous ne savez pas trop comment faire, simplement prendre un RdV en visio avec le ReMI pour effectuer la manipulation ... 

3. **Transferts** :incoming_envelope:

Une fois `new@cssb.fr` et le compte Google pris en main par leur détenteur, le ReMI effectue les manipulations suivantes :

- transfert automatique des emails de `old@cssb.fr` à `new@cssb.fr`, avec si possible un message d'avertissement lorsque un mail est envoyé à `old@cssb.fr`.
- transfert des droits Google drive au nouveau compte, en particulier :
    - documents dont le ReMI est propriétaire => par le ReMI
    - documents dont `old@cssb.fr` est propriétaire => transférer la propriété à `new@cssb.fr`
    - documents dont un autre compte est propriétaire => demander le transfert des droits à la personne détenteur du compte propriétaire

> :warning: Noter quelque-part sur un document de transfert partagé (tableur administratif) l'état du transfert, et les documents encore non transférés

4. **Nettoyage** :coffin:

Après quelques mois pour l'étape 3, une fois que tout les transferts de droits Google ont été effectué et vérifié,
alors l'ancienne adresse peut être officiellement supprimée, ainsi que le compte Google associé :partying_face:.

Cette étape est effectuée par le ReMI, après validation du détenteur de `new@cssb.fr` et notification au président.