# Mot de passe faible

## Consigne

> Maintenant que nous connaissons l'adresse e-mail de Mélanie, vérifions si le mot de passe de ce compte mail a aussi fuité. Quel est le mot de passe de Mélanie associé à cette adresse mail ?
>
> **Preuve insensible à la casse - Format :** motdepasse - **Exemple :** 01032002

## Pistes explorées (avec échecs)

- Recherche dans **IntelX** avec l'adresse `melanie.lefevre@laposte.net` → résultat `mel2508` → incorrect.
- Découverte de 2 fuites (breach) distinctes associées à cette adresse : une de 2019 et une de 2025.
- Sur l'une des fuites, le mot de passe apparaît partiellement hashé/tronqué : `SHA1: 46f0cc6f10c22f356632eb69ccdb7a39aac76c75`, avec un caractère de plus que le guess initial "mel2508" → doute sur le nombre de caractères manquants.
- Lecture d'un article du blog Diariste : ["Qui se permet de piquer mon identité comme ça ?!"](https://www.diariste.fr/MelanieLefevre/posts/qui-se-permet-de-piquer-mon-identite-comme-ca) → indice textuel : *"le prénom de mon crush + 2017"*.
- Recoupement avec sa date de naissance trouvée sur Facebook : 4 juillet 2004.

## Réponse

**04072004** 
