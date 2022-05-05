---
sidebar_position: 3
---

# Projet cinéma

## 1ere étape : Ouverture du cinéma

Ajouter des éléments dans l'App, un texte centré et une image.
```
function App() {
  return (
    <div className="App">
        {nom de votre cinéma}
        {image}
    </div>
  );
}
```

## 2eme étape : Choix types de tickets

Afficher un tableau de 5 éléments avec une map.
```
function App() {
  {déclarer le tableau}
  return (
    <div className="App">
        {étape 1}
        {afficher les éléments du tableau}
    </div>
  );
}
```

:::tip

A quoi sert map ?

:::

## 3eme étape : Ajouter les prix des tickets

Créer un composant qui ajoutera les prix de vos tickets.
```
{nouvelle fonction}

function App() {
  return (
    {étape 1 et 2}
  );
}
```

## 4eme étape : Rendre le code plus beau

Créer un composant pour chaques étapes que vous avez créer et appeler les dans l'App.
```
{composant étape 1}
{composant étape 2}
{composant étape 3}

function App() {
  return (
    {appelle composant 1}
    {appelle composant 2}
    {appelle composant 3}
  );
}
```

## 5eme étape : Ajouter les films

Utiliser l'API Allocine pour récuperer et afficher 10 films (image + nom).

:::info

https://wiki.gromez.fr/dev/api/allocine_v3

:::

## 6eme étape : Ajouter les infos des films

Utiliser l'API Allocine pour récuperer et afficher les infos des 10 films.

Vous ajouterer un bouton pour les affichers ou les cachers.

:::info

Vous pouvez utiliser des API, etc...

:::

:::tip

Qu'est ce qu'un hook ?
Qu'est ce qu'un state ?

:::

## 7eme étape : Banières

Faire une banière (header) en haut de la page et une autre en bas de la page (footer).

L'header sera composé à gauche du nom de votre cinéma et d'un logo. A droite de liens menant à d'autres pages.

Le footer de 3 textes Lorem Itum centrés. Chaque texte aura un alignement de texte différent.

## Bonus : Etape NRV

Appliquer éléctron à votre projet pour en faire une application.

**Et/Ou**

Ettoffer votre site avec des composants tel que la génération de graphiques ou autres.
(demander si vous n'avez pas d'idée)
