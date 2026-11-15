# Qui ose gagne

## Consigne

> Dans ses publications, Boris promet l’indépendance financière, l’accès à un cercle privé et une occasion à ne pas manquer.
>
> Mais derrière ce discours, une transaction bien réelle se dessine : les investisseurs envoient des ETH et reçoivent en échange des jetons HSOV dont personne ne semble pouvoir établir la valeur.
>
> **Quelle est la valeur d’un jeton HSOV en ETH, arrondie au millième supérieur ?**
>
> Format : `X.XXX ETH`

## Pistes explorées

- Analyse des transactions d’un portefeuille investisseur : `0xA1BB598e523A4746204d0EdAf0E2EaCAf375BCC7`.
- Ce portefeuille envoie **8.2385 ETH** vers le portefeuille collecteur `0xd54ad725...`.
- Environ une minute plus tard, il reçoit **129.611927 HSOV** depuis la réserve `0x573890...`.
- Calcul du prix unitaire : `8.2385 ÷ 129.611927 ≈ 0.06356 ETH`.
- Vérification du même ratio sur plusieurs autres transactions investisseurs.
- Arrondi au millième supérieur : **0.064 ETH**.

## Réponse

**0.064 ETH**

## Liens

- [Portefeuille investisseur](https://sepolia.ethplorer.io/address/0xA1BB598e523A4746204d0EdAf0E2EaCAf375BCC7)
- [Portefeuille collecteur](https://sepolia.ethplorer.io/address/0xd54ad725b81052bb90d548ceef62fe5cf7891173)
- [Réserve HSOV](https://sepolia.ethplorer.io/address/0x573890664ff43a407dc7a721fdd35a9625837c61)
