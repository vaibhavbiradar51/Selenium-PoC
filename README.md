# Selenium-PoC
[![Selenium test](https://github.com/vaibhavbiradar51/Selenium-PoC/actions/workflows/test.yml/badge.svg)](https://github.com/vaibhavbiradar51/Selenium-PoC/actions/workflows/test.yml)

1. To add the above banner:
- Go to actions -> open any job -> click of the three dots at corner and select "Create status page"
- Copy the code and paste in the readme.md file.

2. /scripts/InstallChrome.sh contains the commands to install google chrome in the runner

3. SeleniumDemo.java contains the selenium test code which basically uses the chromedriver and searches the given text in google.com and also outputs the search URL which you can find in the github actions

4. pom.xml contains all configuration, dependencies, plugin integration and project setup instructions 

5. Github Workflow
- Uses Ubuntu as runner
- Install JDK
- Install Google Chrome
- maven test 





