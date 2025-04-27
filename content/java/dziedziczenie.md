## Java - Dziedziczenie

```java
class Apple extends Fruit {

    public static final String TYPE = "jabłkowaty";
    private String variety;

    public Apple(double weight, String variety) {
        super(TYPE, weight);
        this.variety = variety;
    }

    public String getVariety() {
        return variety;
    }

    public void setVariety(String variety) {
        this.variety = variety;
    }

    @Override
    String getInfo() {
        return super.getInfo() + ", odmiana: " + variety;
    }
}
```

```java
class Fruit {
    private String type;
    private double weight;

    public Fruit(String type, double weight) {
        this.type = type;
        this.weight = weight;
    }

    public String getType() {
        return type;
    }

    public void setType(String type) {
        this.type = type;
    }

    public double getWeight() {
        return weight;
    }

    public void setWeight(double weight) {
        this.weight = weight;
    }

    String getInfo() {
        return "Waga: " + weight + ", typ: " + type;
    }
}
```

{{ site.data.element.license }}