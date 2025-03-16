# js-function-bag

```js
export const diceRoll = {

    name: 'so much pain',
    dice_roll_explode: function (dice) {
        let rolls = [];
        let sum = 0;

        if (dice > 1) {
            for (let i = 0; ; i++) {
                rolls.push(Math.floor(Math.random() * dice + 1));
                if (rolls[i] < dice) {
                    break;
                }
            }
            for (let i = 0; i < rolls.length; i++) {
                sum = sum + rolls[i];
            }
            return sum;
        }
        if (dice === 1) {
            sum = 1;
            return sum;
        } else {
            return sum;
        }
    },

    dice_roll: function (dice) {
        let sum = 0;
        if (dice > 1) {
            return (sum = Math.floor(Math.random() * dice + 1));
        }
        if (dice === 1) {
            sum = 1;
            return sum;
        } else {
            return sum;
        }
    },

    roll_2d10_and_add_10: function () {
        return this.dice_roll(10) + this.dice_roll(10) + 10;
    },
    roll_2d10_and_add_20: function () {
        return this.dice_roll(10) + this.dice_roll(10) + 20;
    },
    roll_2d10_and_add_30: function () {
        return this.dice_roll(10) + this.dice_roll(10) + 30;
    },
}
```

{{ site.data.element.license }}