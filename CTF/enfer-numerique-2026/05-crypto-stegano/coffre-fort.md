# Coffre-fort

## Consigne

*Trouvez la combinaison du coffre-fort pour entrer sur la plateforme du site du CTE*

## Pistes explorées (avec échecs)

- Décompte des bips du trailer pour en déduire un code à 4 chiffres → plusieurs tentatives de décodage (`92-69-76-84`, puis `8-31-24-16`) → toutes incorrectes, erreur de décompte ou de logique de conversion.
- Résolution technique : ouverture de la console développeur du navigateur sur la page du coffre-fort, et injection directe de la combinaison dans le JavaScript de la page pour forcer l'ouverture :

```js
combination = [8, 31, 26, 18];
currentPosition = 4;
numberBoxes.forEach((box, i) => {
  box.textContent = combination[i].toString().padStart(2, "0");
  box.classList.remove("active");
  box.classList.add("locked");
});
checkCombination();
```
- Bonne combinaison identifiée : **08, 31, 26, 18**.
- 
![Console du navigateur avec le code injecté pour ouvrir le coffre](../../images/05-coffre-fort_01-console-navigateur-combinaison.png)

## Réponse

**08312618** 
