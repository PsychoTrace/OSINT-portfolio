# Hit and run

## Consigne

> Les éléments recueillis montrent que Boris a progressivement centralisé les fonds des investisseurs.
>
> Peu après, les retraits deviennent impossibles et le dispositif cesse brutalement de fonctionner, tandis que Boris disparaît.
>
> Ce mode opératoire s’apparente à un exit scam : après avoir collecté les fonds, l’organisateur met fin au dispositif et repart avec les actifs accumulés.
>
> **Selon le taux de clôture de l’ETH retenu par HSOV le jour de l’exit scam, quelle était la valeur des ETH récupérés par Boris ?**
>
> Format : `X XXX XXX.XX USD`

## Pistes explorées

- La transaction de fuite identifiée précédemment transfère précisément **733.2624421490227238 ETH** vers le portefeuille destinataire de Boris.
- Consultation du document **EXPLICATION_FONDS_HORIZON_SOUVERAIN_2035.pdf**, qui précise que les cours utilisés par HSOV sont indexés sur **Ethplorer.io**.
- La transaction ayant eu lieu le **01/10/2026**, recherche du cours de clôture de l’ETH correspondant à cette date.
- Le cours de clôture retenu est de **2 705.54 USD**.
- Application de la règle du challenge avec un montant de **733.26 ETH** :
  `733.26 × 2 705.54 = 1 983 864.2604 USD`.

## Réponse

**1 983 864.26 USD**

## Liens

- [Transaction de fuite](https://sepolia.etherscan.io/tx/0x9e64a8964176ac7d2025840c37fa8f9dcaafa74a1fdc2fea14950284fe702036)
- [Ethplorer](https://ethplorer.io/)
- [Document HSOV](http://jcunjisfnw6zaf5onfg6m5p73aygvetw7x4b42ivj7qothtu4zkv5gad.onion/EXPLICATION_FONDS_HORIZON_SOUVERAIN_2035.pdf)
