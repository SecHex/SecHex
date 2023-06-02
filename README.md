```css
using System;
using System.Collections.Generic;

namespace Biografie
{
    class Attributes
    {
        public static Tuple<string> GetContactInfo()
        {
            string discord = "𝕴𝖛𝖆𝖗#5091";

            return Tuple.Create(discord);
        }

        public static Tuple<List<string>, int> GetLifeInfo()
        {
            List<string> languages = new List<string> { "German", "English" };
            int age = 18;

            return Tuple.Create(languages, age);
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
}
```



<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
  <h2>Welcome to my Github 👋</h2>
  <div style="width: 46%;">
    <img width="45%" src="https://github-readme-stats.vercel.app/api?username=SecHex&show_icons=true&theme=dark" />
    <img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SecHex&theme=dark&layout=compact" />
  </div>
</div>

![](https://komarev.com/ghpvc/?username=SecHex&color=grey)










