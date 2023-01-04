import javax.script.*;

public class Main {
  public static void main(String[] args) throws ScriptException {
    var m = new ScriptEngineManager();
    try (var e = m.getEngineByName("JavaScript")) {
      e.put("name", "John");
      String script = String.format("print('Hello, %s!')", name);
      e.eval(script);
    }
  }
}
