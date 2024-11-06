**Data-Driven Testing Using Selenium and Python**

Welcome to the Data-Driven Testing with Selenium and Python repository! This repository provides an example of how to perform data-driven testing for web applications, leveraging Selenium WebDriver and Python. Data-driven testing allows you to test application functionality with multiple sets of data, stored in files like .csv or .xlsx.

**Overview**
In this example, I've implemented a basic login functionality test with negative test cases. The test script reads data from a CSV file and executes the test for each data set automatically, simulating multiple login attempts with different credentials. This approach is ideal for efficiently testing how your application handles various inputs, improving coverage with minimal code repetition.

**Key Features**
1. Data-driven Testing: Execute the same test logic with different data sets, using external data files.
2. CSV Integration: Reads data from a CSV file, making it easy to modify and add test cases without editing code.
3. Selenium and Python: Built using Selenium WebDriver with Python, a powerful and flexible approach for web application testing.

**Requirements**
1. IDE: PyCharm (recommended for Python development and seamless CSV integration)
2. Testing URL: Rahul Shetty Academy Login Page
3. CSV File Plugins: Use the "CSV Reader" plugin or similar to manage and view your CSV test data conveniently within PyCharm.
   
**Getting Started**

1. Install Selenium: Ensure that Selenium is installed in your environment (pip install selenium).
2. System Path: Confirm that the path to the Selenium driver (e.g., chromedriver) is added to your system environment variables.

**Running the Test**
1. Place your test data in a .csv file (e.g., login_data.csv) in the project directory.
2. Open the project in PyCharm, edit the script as necessary, and run the test script. Each row in the CSV file will be used for a separate test iteration.
