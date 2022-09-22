# Lösningar

## Some

```js
function canSeeMovie(arr) {
    return arr.some((user) => user.age >= 18)
}
```

## Every

```js
function canEnterClub(arr) {
    return arr.every((user) => user.age >= 18)
}
```

## Reduce

```js
function totalCost(arr) {
    return arr.reduce((prev, current) => prev + current.price, 0)
}
```

## Filter

```js
function findUsersInCity(arr, city) {
    return arr.filter((user) => user.address.city === city)
}
```

## Map

```js
function generateFullNName(arr) {
    return arr.map((user) => ({
        ...user,
        fullName: `${user.firstName} ${user.lastName}`,
    }))
}
```
