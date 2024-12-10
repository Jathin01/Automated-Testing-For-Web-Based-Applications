**Automated Testing for Web-Based Applications**
This project combines Selenium, Java, TestNG, and Maven to automate the testing of the Best Buy online application. The Page Object Model (POM) architecture is used to ensure modular and maintainable code, streamlining the automation process.

**Features**
Page Object Model (POM): Enhances readability and maintainability by structuring the automation code.
TestNG Framework: Supports the creation of thorough test cases and scenarios.
Documentation: Includes an Excel spreadsheet that documents every test case and scenario for clear test coverage visualization.
HTML Reports: Generates HTML reports using Extent Reports for detailed insights into test execution results.
Cross-Browser Testing: Ensures compatibility and reliability by supporting tests on multiple browsers, such as Chrome, Firefox, and Edge.

**Prerequisites**
Before running this project, ensure the following are installed on your system:

**Java Development Kit (JDK): Latest stable version.**
Apache Maven: Latest stable version.
IDE: Visual Studio Code or another preferred IDE.
Browser Drivers: Ensure the required browser drivers (e.g., chromedriver, geckodriver) are downloaded and their paths are correctly set.

**Setup and Installation**
1. Clone the Repository
To get started, clone the repository to your local system:
git clone https://github.com/Kalyanreddy292/Automated-Testing-for-web-based-applications-BestBuy.git

**2. Navigate to the Project Directory**
Change the directory to the project folder:
cd Automated-Testing-for-web-based-applications-BestBuy
Understanding the Project Structure
pom.xml: Maven configuration file containing project dependencies and build instructions.
src/test/java: Directory containing the test cases written in Java.
src/main/java: Directory for reusable components or utilities.
testng.xml: TestNG configuration file defining the test execution suite.
target/test-classes: Contains compiled .class files generated after test execution.
Excel Folder: Contains an Excel file documenting the test cases and scenarios.
Reports Folder: HTML reports generated after test execution.

**Build the Project**
To resolve dependencies and build the project, run the following command:
mvn clean install
This command will download necessary dependencies and compile the project.

**Running the Tests**
Execute the test suite using Maven. Run:
mvn test -DsuiteXmlFile=testng.xml

**Test Results**
After the tests complete:
HTML Reports: Located in the Reports folder in the project directory.
Excel Reports: Test documentation is available in the Excel folder.
External JARs Used

**The following external libraries are used in this project:**
TestNG
Selenium
Extent Reports
log4j

**Troubleshooting**
1. Dependency Errors
If you encounter errors related to dependencies, update them with:
mvn clean install -U

2. Browser Driver Issues
Ensure the appropriate browser driver is downloaded and added to your system's PATH. 

3. Maven Not Found
Ensure Maven is installed and added to your system's PATH. Verify by running:
mvn -v
