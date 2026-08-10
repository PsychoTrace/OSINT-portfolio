# Le bailleur inconscient

## Consigne

> Samir a reçu ce mail qu'il trouve un peu suspect. Il décide de l'analyser avec vous. Quelle est l'identité de la personne qui se cache derrière cet envoi de mail ?
>
> **Preuve insensible à la casse - Format :** prenom_nom - **Exemple :** edward_snowden

## Pistes explorées

- Une première tentative avec marie_dubois, un nom trouvé sur le site de l'agence, s'avère incorrecte.
- Le mail semble provenir de l'adresse contact@immo-location-pro.fr.
- La consultation de la page immo-location-pro.fr/about.html permet d'identifier plusieurs personnes liées à l'agence, mais aucun élément ne permet encore de déterminer précisément l'expéditeur.
L'analyse technique du mail révèle la présence d'une signature OpenPGP/PGP.
Cette signature est associée à l'identifiant de clé :
128EE0D2F6E04649
- Une recherche de cette clé via l'API publique de Keybase permet de récupérer la clé publique correspondante :
https://keybase.io/_/api/1.0/key/fetch.json?pgp_key_ids=128EE0D2F6E04649
- La réponse JSON contient notamment l'empreinte de la clé :
91caad14ac0d384b27d90116128ee0d2f6e04649
- Le bloc de clé publique OpenPGP contient également l'identité (UID) associée à cette clé : Jawad BENDAOUD <jawad.bendaoud93031@protonmail.com>
Cette information permet donc d'identifier la personne associée à la clé utilisée pour signer le message.


## Réponse

**jawad_bendaoud** - *(Jawad BENDAOUD, jawad.bendaoud93031@protonmail.com)*

## Preuve
![](../images/le-bailleur-inconscient.png)
