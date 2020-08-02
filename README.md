OpenJDK hack that accept (some) Emojis as identifiers
==========

This is just a fork joke, where I imagined what if we could do this?

```java
import java.util.Scanner;

class IsEven {
  static boolean 🤞(int 👏) {
    return 👏 % 2 == 0;
  }

  public static void main(String[] args) {
    Scanner 😄 = new Scanner(System.in);

    System.out.println("Enter a number: ");
    int 🙃 = 😄.nextInt();
    😄.close();

    if (🤞(🙃)) {
      System.out.println("Is even");
      return;
    }

    System.out.println("Isn't even");
  }
}
```

So, I hacked the lexer and added Emoji characters as valid for identifiers.

In order to build, follow the instructions in doc/building.md
