### Hi there 👋

public class AboutMe {
    private String[] code = {"Java", "HTML", "CSS", "SQL"};
    private String currentOccupation = "QA Engineer, open for job opportunities";
    private String challenge = "Expanding skills in Security Testing";
    private String[] languages = {"Bulgarian - Native", "English - Advanced"};
    private String[] passions = {"Photography"};
    private String[] strengths = {"Problem Solving", "Attention to Detail", "Team Collaboration"};

    private Technologies technologies;

    public AboutMe() {
        this.technologies = new Technologies();
    }

    public static class Technologies {
        private Tools tools;

        public Technologies() {
            this.tools = new Tools();
        }

        public static class Tools {
            public String[] projectManagement = {"Jira", "IntelliJ IDEA"};
            public String[] versionControl = {"GitHub"};
            public String[] programmingLanguages = {"Java", "SQL"};
            public WebTesting webTesting;

            public Tools() {
                this.webTesting = new WebTesting();
            }

            public static class WebTesting {
                public String[] tools = {"Selenium WebDriver", "JUnit", "TestNG", "Postman", "REST Assured", "HTML", "CSS", "JMeter"};
            }
        }
    }
}


