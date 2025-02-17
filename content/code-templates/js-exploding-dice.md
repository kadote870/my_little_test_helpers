# js-exploding-dice

## v1
```js
function explodingDice() {

    let dice = 10;
    let rolls = [];
    let sum = 0;

    if (dice > 1) {
        for (let i = 0; ; i++) {
            rolls.push(Math.floor(Math.random() * dice + 1));
            if (rolls[i] < dice) { break }
        }

        for (let i = 0; i < rolls.length; i++) {
            sum = sum + rolls[i];
        }
    }

    return sum
}

console.log(explodingDice())
```

## v2

```js
function explodingDice() {
    const dice = 10;
    let sum = 0;

    while (true) {
        const roll = Math.floor(Math.random() * dice) + 1;
        sum += roll;
        if (roll < dice) break;
    }

    return sum;
}

console.log(explodingDice());
```