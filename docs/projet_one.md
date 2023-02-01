---
sidebar_position: 2
---

# Project cinema

## 1st step : Open your cinema

Add elements in App, a centered text and an image.

```
function App() {
  return (
    <div className="App">
        {name of your cinema}
        {image}
    </div>
  );
}
```

## 2nd step : Chose your types of ticket

Display an array of 5 string with map.

```
function App() {
  {declare the array}
  return (
    <div className="App">
        {step 1}
        {display array elements}
    </div>
  );
}
```

:::tip

What is map used for?

:::

## 3rd step : Add ticket prices

Create a component that will add the prices of your tickets.

```
{new function}

function App() {
  ...
  return (
    {step 1}
    {step 3}
  );
}
```

## 4th step : Make the code more beautiful

Create a component for each step you created and call them in the App.
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

## 5th step : Get movies

Use the OMDb API to retrieve 10 movie names.

:::info

https://www.omdbapi.com/

You need to create a free account and generate a "API Key"

:::

:::tip

How can I see movie's data without displaying them ?

:::

## 6th step : Add movies

Display the name and some information of each film.

Each film (name + data) must be separete in differente box.

## 7th step : The evil buton

Add a button to display or hide film's data.

:::tip

What is a hook?
What is a state?

:::

## 8eme étape : Bruce

Make a banner (header) at the top of the page and another at the bottom of the page (footer).

The header will be composed :
  - on the left : the name of your cinema and a logo.
  - on the right : links leading to other pages.

The footer of 3 centered Lorem Itum texts. Each text will have a different text alignment.

## Bonus : NRV

Expand your site with components such as graphics generation or others.

**And/Or**

Create your Back-end API

**And/Or**

Apply electron to your project to make it an app.
