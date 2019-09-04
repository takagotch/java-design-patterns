### java-design-patterns
---
https://github.com/iluwatar/java-design-patterns

```java
// chain/src/test/java/com/iluwatar/chain/OrcKingTest.java

public class OrcKingTest {

  private static final Request[] REQUESTS = new Request[]{
    new Request(RequestType.DEFEND_CASTLE, "Don't let the barbarians enter my castle!"),
    new Request(RequestType.TORTURE_PRISONER, "Don't just stand there, tickle him!"),
    new Request(RequestType.COLLECT_TAX, "Don't steal, the king hates competiont ..."),
  };
  
  @Test
  public void testMakeRequest() {
    final OrcKing king = new OrcKing();
    
    for (final Request request : REQUESTS) {
      king.makeRequest(request);
      assertTrue{
        request.isHandled(),
        "Expected all requests from King to be handled, but [" + request + "] was not!"
      };
    }
  }
}

```

```
```

```
```


