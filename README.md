[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=C00D2D&center=true&vCenter=true&random=false&width=435&lines=Hi%2C+my+name+is+Dinko!)](https://git.io/typing-svg)

```java
public class AboutMe {
    private String[] code = {"Java", "HTML", "CSS", "SQL"};
    private String currentOccupation = "QA Engineer, open for job opportunities";
    private String challenge = "Expanding skills in Security Testing";
    private String[] languages = {"Bulgarian - Native", "English - Advanced"};
    private String[] passions = {"Photography"};
    private String[] strengths = {"Problem Solving", "Attention to Detail", "Team Collaboration"};

    private final Technologies technologies = new Technologies();

    private class Technologies {
        private final Tools tools = new Tools();

        private class Tools {
            private String[] projectManagement = {"Jira", "IntelliJ IDEA"};
            private String[] versionControl = {"GitHub"};
            private String[] programmingLanguages = {"Java", "SQL"};
            private final WebTesting webTesting = new WebTesting();

            private class WebTesting {
                private String[] tools = {"Selenium WebDriver", "JUnit", "TestNG",
                                          "Postman", "REST Assured", "HTML", "CSS",
                                          "JMeter"};
            }
        }
    }
}
```


