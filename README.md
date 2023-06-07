
```css
public class Attributes
{
    public static Tuple<string> GetContactInfo()
    {
        string discord = "𝕴𝖛𝖆𝖗#5092";
        return Tuple.Create(discord);
    }

    public static Tuple<List<string>> GetLifeInfo()
    {
        List<string> languages = new List<string> { "German", "English" };
        return Tuple.Create(languages);
    }

    public static Tuple<Dictionary<string, List<string>>, List<string>> GetCodingInfo()
    {
        Dictionary<string, List<string>> languages = new Dictionary<string, List<string>>
        {
            { "expert", new List<string> { "python" } },
            { "intermediate", new List<string> { "c#", "c++" } },
            { "learning", new List<string> { "go", "java", "lua" } }
        };
        List<string> specialities = new List<string> { "software development" };
        return Tuple.Create(languages, specialities);
    }
}
```




![](https://komarev.com/ghpvc/?username=SecHex&color=grey)










