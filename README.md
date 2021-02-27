public class Cody extends GitHubUser {

  public Custom() {
    super("CustomConfig", "United Kingdom");

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
