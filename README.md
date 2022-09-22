# Array funktioner

## Some

Du jobbar på en biograf och många utav era filmer har en åldergräns där man bara ett sällskap av människor bara få se en film ifall minst en utav dessa elever är 18 år eller äldre. Skapa en en funktion med namnet **canSeeMovie** som tar emot ett argument vilket är en array utav av personer som ska se en film, som exemplet nedan. Funktionen ska returnera **true** om minst en utav personerna är 18 år eller äldre annars ska den returnera **false**. Med array:n nedan ska din funktion returnera **true**

**Exempel data**

```js
const users = [
    { name: 'Adam', age: 12 },
    { name: 'Emma', age: 19 },
    { name: 'Fredrik', age: 15 },
]
```

## Every

Du jobbar på en klubb där många vängrupper brukar komma till klubben och vilja komma in men ibland är vissa i gruppen under 18 år vilket gör att ingen i gruppen får komma in. Skapa en en funktion med namnet **canEnterClub** som tar emot ett argument vilket är en array utav av personer som vill komma in, som exemplet nedan. Funktionen ska returnera **true** om alla personer är 18 år eller äldre annars ska den returnera **false**. Med array:n nedan ska din funktion returnera **false**

**Exempel data**

```js
const users = [
    { name: 'Adam', age: 12 },
    { name: 'Emma', age: 19 },
    { name: 'Fredrik', age: 15 },
]
```

## Reduce

Du har en tendens att köpa mycket strumpor från klädbutiker, och för att hålla koll på alla dina köp skriver du in hur mycket varje köp kostade samt datumet i en array. Du vill nu veta hur mycket du har spenderat på strumpor. Skriv en funktion med namnet **totalCost** som tar emot en array av köp och som returnerar summan av alla köps pris. Med array:n nedan ska din funktion returnera **250**

**Exempel data**

```js
const purchases = [
    { price: 10, date: 'June 15' },
    { price: 45, date: 'June 20' },
    { price: 195, date: 'December 18' },
]
```

## Filter

Du jobbar på marknadsföringsavdelningen på ett tech företag och du har en lång lista på användare runt om i värden, du vill kunna hitta alla användare som bor i en viss stad. Skriv en funktion med namnet **findUsersInCity** som tar emot **två** argument, en array av användare som ser ut som exemplet nedan och en string som ska repsentera vilken stad du letar efter. Med array:n nedan och **"Stockholm"** som det andra argumentet ska din funktion returnera

```js
[
    { name: 'Leo Pato', address: { city: 'Stockholm', zip: '195 58' } },
    { name: 'Moa Persson', address: { city: 'Stockholm', zip: '163 12' } },
]
```

**Exempel data**

```js
const users = [
    { name: 'Leo Pato', address: { city: 'Stockholm', zip: '195 58' } },
    { name: 'Steve Aoki', address: { city: 'Tokyo', zip: '12 345' } },
    { name: 'Kento Yamazaki', address: { city: 'Tokyo', zip: '12 391' } },
    { name: 'Gordon Ramsey', address: { city: 'London', zip: '91 456' } },
    { name: 'Moa Persson', address: { city: 'Stockholm', zip: '163 12' } },
]
```

## Map

Skriv en funktion med namnet **generateFullNName** som tar emot en array av användare som exemplet nedan och lägger till en ny **key**, **fullName**, på alla användare som ska komma ifrån att du kombinerar deras **firstName** och **lastName**. Med array:n nedan ska din funktion returnera:

```js
const users = [
    { fullName: 'Adam Harki', firstName: 'Adam', lastName: 'Harki' },
    { fullName: 'Emma Lindholm', firstName: 'Emma', lastName: 'Lindholm' },
    { fullName: 'Per Gustavsson', firstName: 'Per', lastName: 'Gustavsson' },
]
```

**Exempel data**

```js
const users = [
    { firstName: 'Adam', lastName: 'Harki' },
    { firstName: 'Emma', lastName: 'Lindholm' },
    { firstName: 'Per', lastName: 'Gustavsson' },
]
```
