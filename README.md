```java
public class CustomConfig extends GitHubUser {
  public CustomConfig() {
    super("CustomConifg", "United Kingdom");
    this.addLanguage("Java");
    this.addExperience("Spawner.net", "TreacheryMC", "MineClouds");
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
