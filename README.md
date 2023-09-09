# Shanjida Rahman : 011191216
# Selenium IDE Testing Report for Spring.IO Website


### Introduction
This provides an overview of the Selenium testing conducted on the Spring.IO website. The testing focused on four key test cases:
1. Load home page and it's contents
2. Change UI Theme
3. Scroll and browser through pages
4. Load Spring Initializer app
5. Validate input fields
6. Add & Remove dependencies
7. Execute Spring boot app generation 
8. Download generated zip file of Spring Boot application.

The purpose of this testing was to ensure the reliability, functionality, and performance of the Spring.IO website.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Test Descriptions](#test-descriptions)
- [Test Code](#test-code)
- [Contributing](#contributing)
- [License](#license)


### Test Environment
- Google Chrome browser : [116.0.5845.96]
- Selenium IDE Version: [3.17.2]
- Java [8 or above]
- Python [2 or above]
- Spring.IO Website URL: [https://spring.io/]
- Test Execution Date: [29-08-2023]


### Prerequisites

Before running the tests, ensure you have the following prerequisites installed:

- **Chrome/Firefox Web browser**: Ensure you have chrome of any other web browser installed on your PC.

- **Selenium IDE Extension**: Install Selenium IDE Extension on your browser of choice.

- **A stable internet connection**: Ensure stable internet connectivity.


### Installation

   1. Install any browser you want from the internet.
   2. For chrome or firefox go to extension manager and search for Selenium IDE extension. And add that extension to your favorite browsers
   3. Install Java SDK  [https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-do-I-install-Java-on-Windows]
4. Install python from  [https://realpython.com/installing-python/]
5. Clone the git repository [https://github.com/shanjidarahmanpromi/Spring-IO-Selenium-Testing.git]

## Test Cases

### 1. Load home page and it's contents:
    This test case verifies that the contents of the landing page and it's contents are loaded correctly.


- **Expected Results**:
    - The page loaded successfully
    - All the page contents including the links to the other pages and images etc. 


### 2. Change UI Theme:

    This test case ensures that the UI Theme change feature on the Spring.IO website works correctly.



- **Expected Results**:
    - The UI theme should change into light/dark color.


### 3. Scroll and browser through pages:
    This test case verifies the functionality of Spring.IO website dropdowns and loads all contents.


- **Expected Results**:
    - All the dropdowns should load and work perfectly.
    - The pages should have all the contents.


### 4. Load Spring Initializer app:
    This test case focuses on loading the Spring boot app Initializer page

- **Expected Results**:
    - The website should maintain reasonable response times under normal and heavy loads.
    - There page should load with all the input form fields and select menus.

### 5. Validate input fields:
    This test case focuses on validating if the input fields are working correctly and only accepting valid data as input.

- **Expected Results**:
  - The input fields should accept only valid inputs.



### 6. Add & Remove dependencies:
    This test case focuses on validating if the selected dependencies are added properly or removed properly.

- **Expected Results**:
  - The Add and Remove dependencies button should add or remove dependencies accordingly.



### 7. Execute Spring boot app generation:
    This test case focuses on validating if the Generate button starts generating Spring boot starter application properly. 

- **Expected Results**:
  - The Generate button should start generating Spring boot starter application instantly. 


### 8. Download generated zip file of Spring Boot application:
    This test case focuses on the download fundtion of  Spring boot starter application properly. 

- **Expected Results**:
  - After starter app generation the zip file should be generated and downloaded automatically.


# Test Steps (Using Selenium IDE):
  - Launch the Selenium IDE.
  - Load the Spring.io.side file into the extension by clicking on **Select Existing Project**.
  - Click on **Run ALl Tests**


# Test Steps (Using Python or Java Code IDE):
- Run the Java Code [FiledownloadTet.java] provided in the project root directory.
- Run the Python Code [test_filedownload.py] provided in the project root directory.

### Conclusion
The Selenium testing conducted on the Spring.IO website covered critical functionality and performance aspects. All test cases were executed successfully, and the website performed adequately. 