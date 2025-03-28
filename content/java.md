# Java

## Typy Danych

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

{{ site.data.element.license }}