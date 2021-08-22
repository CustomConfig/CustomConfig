```java
public class CustomConfig extends GitHubUser {
  public CustomConfig() {
    super("CustomConifg", "United Kingdom");
    this.addLanguage("Java", "Node.js");
    this.addExperience("PvPIslands", "TreacheryMC", "PvPGlobe");
  }
}
public abstract class GitHubUser {
  @Getter private final String username;
  @Getter private final String country;
  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();
  public GitHubUser(String username, String country) {
      this.name = username;
      this.country = country;
  }
  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```
![CustomConfigs's github stats](https://github-readme-stats.vercel.app/api?username=CustomConfig&count_private=true&show_icons=true&theme=dark&hide_border=false) ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=CustomConfig&theme=dark&count_private=true)

### ⌨️ Coding Languages/Operating Tools
![Notepad++](https://img.shields.io/badge/-Notepad++-0C1324?style=flat-square&logo=Notepad%2B%2B&&logoColor=ffffff)
![Java](https://img.shields.io/badge/-Java-0C1324?style=flat-square&logo=java&logoColor=ffffff)
![Node.js](https://img.shields.io/badge/-Node.js-0C1324?style=flat-square&logo=Node.js&logoColor=ffffff)
![Intelij](https://img.shields.io/badge/-Intelij-0C1324?style=flat-square&logo=jetbrains&logoColor=ffffff)
