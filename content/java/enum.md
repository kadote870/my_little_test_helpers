# Java - enum

```java
    enum type {egzotyczny, jagodowy, jablkowaty}

enum ShirtSize {SX, S, M, L, XL}

public static void main(String[] args) {
    System.out.println(ShirtSize.S);
}
```

```java
enum Size {
    SMALL("Mały"), MEDIUM("Średni"), LARGE("Duży");

    private final String description;

    // Konstruktor
    private Size(String description) {
        this.description = description;
    }

    public String getDescription() {
        return description;
    }
}

```

{{ site.data.element.license }}