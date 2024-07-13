# Website_Automation_Testing
Conducted Automation Testing on an Ecommerce Website for QA using Selenium, WebDriver API, Cucumber and JUnit. 

## Short Description 

#### i.) Register functionality - Generated and automated 4 scenarios to test. 
Register.feature - Steps written to test for the all the scenarios. 
Register.java - Implementation of the steps to perform which are present in every scenarios.

#### ii.) Login functionality - Generated and automated 4 scenarios to test. 
Login.feature - Steps written to test for the all the scenarios. 
Login.java - Implementation of the steps to perform which are present in every scenarios.

#### iii.) Search functionality - Generated and automated 4 scenarios to test. 
Search.feature - Steps written to test for the all the scenarios. 
Search.java - Implementation of the steps to perform which are present in every scenarios.

#### iv.) Order functionality - Generated and automated 4 scenarios to test. 
Orders.feature - Steps written to test for the all the scenarios. 
Orders.java - Implementation of the steps to perform which are present in every scenarios.

#### v.) Pages Folder - Contain web elements of each respective pages and sections to perform automation using the specific scenarios. 

#### Other important files
Base.java - Declared all the Webdriver API into this file from framework level. <br/>
config.properties - For declaring all configurations once and use multiple times  <br/>
ConfigurationReader.java - For reading properties from the config.properties file. It is also an interface <br/>
PropertyFileReader.java -  used for implementing the methods present in the interface file ConfigurationReader.java  <br/>
(Note: the usage of this above file is to intialize the config.properties before performing any operation) <br/>
PathHelper.java - Used to append the User.dir(the project path) to the provided path. <br/>
Hooks.java- It contains the before and after method to be run on performing every scenario. It belongs to cucumber api <br/>
log4j.properties - Used for logging purposes. <br/>
TestRunner.java - To run the scenarios automatically and publish Junit results. 

