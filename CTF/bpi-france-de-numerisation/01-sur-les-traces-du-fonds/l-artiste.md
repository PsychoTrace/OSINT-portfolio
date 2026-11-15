# L'artiste

## Consigne

> Depuis les débats autour de Chat Control, la présence numérique de cet individu semble avoir évolué.
>
> Ses profils habituels sont devenus silencieux. Quelques traces publiques subsistent pourtant et pourraient vous mener vers un compte sur lequel il semble toujours actif.
>
> **Quel est l’identifiant du compte sur lequel « THEREALBBKM » est désormais actif ?**
>
> Format : `123456789012345678`

## Pistes explorées

- La bio Instagram de **THEREALBBKM** renvoie vers « le seul vrai réseau de la vérité », ce qui mène à **Truth Social**.
- Le compte `@TheRealBBKM` est retrouvé, mais l’identifiant numérique demandé n’est pas directement visible sur le profil.
- Utilisation de l’endpoint public de l’API Truth Social permettant de rechercher un compte à partir de son nom :
  `api/v1/accounts/lookup?acct=TheRealBBKM`.
- La réponse JSON contient l’identifiant numérique du compte.

## Réponse

**117156193984881438**

## Liens

- [Profil Truth Social — @TheRealBBKM](https://truthsocial.com/@TheRealBBKM)
- [API Truth Social — account lookup](https://truthsocial.com/api/v1/accounts/lookup?acct=TheRealBBKM)
