[Code Coverage Tasks](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/test/publish-code-coverage-results?view=azure-devops)
* Code coverage is another term for test coverage.  Essentially ensuring that all of the functions of code have a test built in for them.  
* Examples for Java code coverage are below
    * Cobertura
    * JaCoCo
* You can also use tools that will publish code coverage data to the Pipeline
    * Visual Studio Test
    * .NET Core
    * Ant
    * Maven
    * Gulp
    * Grunt

[Java Code Checking utilities](https://docs.microsoft.com/en-us/azure/devops/java/standalone-tools?view=azure-devops)
* PMD
    * Static Code Analyzer/Source Code Analyzer
* Checkstle
    * Style Checks/Standards Check
* Findbugs
    * Find Bugs

[Maven Tasks](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/build/maven?view=azure-devops)
* Builds the java code during the pipeline. 
* Can run a variety of additional checks to ensure code passes the associated tests

[Gradle Tasks](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/build/gradle?view=azure-devops)
* Different flavor of Maven

[SonarQube](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarqube)
* Static code analyzer that can help find areas of improvement for your code.   
* Allows you to analyze technical debt in the project and keep track of it in the future. 
* Leverages a Service Connection within AzDo
    * Also called a Service Endpoint

[Black Duck](https://marketplace.visualstudio.com/items?itemName=black-duck-software.detect-for-tfs)
* Plugin for AzDo
* Identifies open source libraries, license compliance, and operational risks across apps and containers.  
