| Data Type | desc                                                    | example                                   |
|-----------|---------------------------------------------------------|-------------------------------------------|
| byte      | -128 to 127                                             |                                           |
| short     | -32,768 to 32,767                                       |                                           |
| int       | -2,147,483,648 to 2,147,483,647                         |                                           |
| long      | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |                                           |
| float     | 6 to 7 decimal digits                                   | ```float myFloatNum = 5.99f;```  // §5.99 |
| double    | 6 to 7 decimal digits                                   |                                           |
| boolean   | true / false                                            |                                           |
| char      | single character/letter or ASCII values                 |                                           |
| String    | "String"                                                |                                           |

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