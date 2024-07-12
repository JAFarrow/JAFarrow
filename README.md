```java
public class JAFarrow implements Developer {
  private String name;
  private Map<String, String> contact;

  public JAFarrow(String name, Map<String, String> contact){
    this.name = name;
    this.contact = contact;
  }

  public static void main(String[] args){
    String name = "Justin Farrow";
    Map<String, String> contact = Map.of(
        "email", "f.justin@tutanota.com"
      )
    JAFarrow me = new JAFarrow(name, contact);
  }
}
```
