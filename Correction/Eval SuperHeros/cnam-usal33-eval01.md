# USAL33 - HTML / CSS - Evaluation 1

Pour cette première évaluation, vous allez devoir réaliser en HTML / CSS un petit site de quatre pages.

## Consignes :

* La partie HTML doit rester fonctionnelle sans CSS
* Je dois pouvoir prendre votre projet, le placer sur un serveur et pouvoir naviguer à travers les pages
* Les polices sont à ajouter avec Google Font
* Les images ne doivent pas être déformées
* Si vous n'avez pas d'informations précises sur un point, faîtes au mieux en vous basant sur les imprimes écrans.
* L'utilisation de fonctionnalités avancées de CSS (variables, unités relatives...) n'est pas obligatoire mais un plus

---

## La police 

- Open Sans en 400 et 700 

## Les couleurs

- Arrière-plan de toutes les pages : #fbf7f0
- Les menus : #9d9d9c
- Le menu actif (page courante) : #383937
- Les bordures entre les menus et en dessous des titres de page : #e0dfdc
- Les liens : #383937
- Le fond du bouton : #2e302e
- Le fond Deadpool : #b05a58
- Le fond Spiderman : #073466
- Le fond Hulk : #638346

## Les images de la page les super-héros

Largeur du bloc parent : 340px
Hauteur du bloc parent : 300px

Pour obtenir un bon ratio, utiliser le code suivant pour l'élément html img :

```css
img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
```

## L'image d'arrière plan

À faire en dernier.

- Opacité de 0.1
- Largeur et hauteur de 400px
- Positionné en fixe toujours en bas à gauche de la page