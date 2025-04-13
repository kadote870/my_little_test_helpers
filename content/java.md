# Java

## Typy Danych

| Data Type | desc                                                    | example                                  |
|-----------|---------------------------------------------------------|------------------------------------------|
| byte      | -128 to 127                                             |                                          |
| short     | -32,768 to 32,767                                       |                                          |
| int       | -2,147,483,648 to 2,147,483,647                         |                                          |
| long      | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |                                          |
| float     | 6 to 7 decimal digits                                   | ```float myFloatNum = 5.99f;```  // 5.99 |
| double    | 6 to 7 decimal digits                                   |                                          |
| boolean   | true / false                                            |                                          |
| char      | single character/letter or ASCII values                 |                                          |
| String    | "String"                                                |                                          |

## Proste statystyki z warhammera

```java
public class warhammer {
    public static void main(String[] args) {

        final String character = "Sigmar";
        final int statWW = 50;
        final int statUS = 50;
        final int statINT = 50;
        final int statA = 50;

        System.out.println(character);
        System.out.println("WW: " + statWW);
        System.out.println("US: " + statUS);
        System.out.println("INT: " + statINT);
        System.out.println("A: " + statA);
    }
}
```

## [commituj jak człowiek a nie małpa ](how-to/intellij.md)

## Generowanie geterów i seterów w inteliji

* win: `alt`+`insert`
* mac: `control` + `n`
* Getter and Setter

## Problemy z lombok

* `Settings > Build, Execution, Deployment > Compiler > Annotation Processors`
* `[/] Enable annotation processing`
* `[/] Obtain processors from project classpath`
* Stosować powyzsze dla projektów, gdy na dwoch roznych komputerach lombok nie domaga 

## for (Java vs JavaScript)

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