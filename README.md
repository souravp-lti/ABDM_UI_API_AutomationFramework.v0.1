Instructions:

1. Download the latest allure commandline xip file and install it "https://repo.maven.apache.org/maven2/io/qameta/allure/allure-commandline/2.8.0/".
2. check the version using allure --version in cmd prompt.
3. Install apache-maven.
4. check the version using mvn --version in cmd prompt.
5. Add allure{version}\bin, apache-maven-{version}\bin and jdk-{version}\bin file paths in the Environment Variables > System variables(path variable).
6. Only the config.properties file present in the root should be edited for configuring the framework in ones system.
7. Do not delete categories.json, environment.xml and executor.json in allure-results folders(useful for customizing the allure report UI).
8. To see the trend details of the test cases which are ececuted multiple times in allure report copy the allure-report > history folder to allure-results > history folder
