# Java - Array - List

```js
const nums = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

for (const element of nums) {
    console.log("test " + element)
}

```

```java
public class Tablica {
    public static void main(String[] args) {
        // 1
        int[] nums = new int[10];

        int iterator = 0;

        for (int element : nums) {
            element[iterator] = iterator;
            iterator++;
        }

        for (int element : nums) {
            System.out.println("test " + element);
        }

        // 2
        int[] numbers = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9};
        String[] names = {"Matthew", "Mark", "Luke", "John"};
        String testMessage = "hard-coded data ";


        for (int element : numbers) {
            System.out.println(testMessage + element);
        }
        for (String element : names) {
            System.out.println(testMessage + element);
        }
    }
}
```

{{ site.data.element.license }}