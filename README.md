```java
import java.util.Map;

public class JAFarrow extends Developer {
    
    public JAFarrow(String name, Map<String, String> contact, Map<String, String[]> languages, String[] interests) {
        super(name, contact, languages, interests);
    }
    
    public static void main(String[] args) {
        String name = "Justin Farrow";

        Map<String, String> contact = Map.of(
            "email", "f.justin@tutanota.com"
          );

        Map<String, String[]> languages = Map.of(
            "intermediate", new String[] {"java", "python", "javascript"},
            "learning", new String[] {"c#"}
          );

        String[] interests = {
            "web development",
            "rest api's",
            "protocols",
            "foss alternatives"
          };

        JAFarrow me = new JAFarrow(name, contact, languages, interests);
    }
}
```
