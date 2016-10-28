# syntaxCheck

# CSharp
```cs
using Newtonsoft.Json;
...
[JsonObject]
public class MyInput{
  [JsonProperty]
  public string name {get; set;}
  [JsonProperty]
  public string eyes {get; set;}
}
...
MyInput input = new MyInput();
input.name = "Fred Jones"
input.eyes = "blue";
```
