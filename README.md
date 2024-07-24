# CODTECH-TASK2

Project Objective:
Automate the testing of an e-commerce web application using Selenium WebDriver to ensure seamless functionality from product selection to order confirmation. This project aims to validate critical user journeys and verify the application's behavior under various scenarios.

Key Activities:
Environment Setup:
-Configure Selenium WebDriver using WebDriverManager for managing browser drivers.
-Set up implicit waits and maximize the browser window for consistent test execution.
-Page Object Modeling (POM):

Implement Page Object classes (LandingPage, ProductCatalogue, CartPage, CheckoutPage, ConfirmationPage) to encapsulate web elements and actions for each page of the application.

Test Scenario Execution:
-Navigate to the landing page, log in with credentials, and access the product catalogue.
-Add a specific product (ZARA COAT 3) to the cart and verify its presence on the cart page.
-Proceed to checkout, select the country, and submit the order.
-Validate the confirmation message after placing the order.

Assertions and Reporting:
-Used TestNG assertions (Assert.assertTrue) to verify expected outcomes at various stages of the checkout process.
-Close the WebDriver instance (driver.close()) after completing the test.


Technology Used:
-Selenium WebDriver: Automates web browser interactions to simulate user actions on the web application.
-Java: Programming language used for writing test scripts.
-TestNG: Testing framework for organizing test cases and managing assertions.
-WebDriverManager: Simplifies management of WebDriver binaries (e.g., ChromeDriver).


Key Insights:
-Modular Test Design: By using Page Object Model (POM), the code achieves maintainability and reusability, enhancing test script scalability.
Efficiency through Automation: Automated tests reduce manual effort and time required for regression testing, ensuring consistent application behavior across releases.
-Integration Potential: Tests can be integrated into Continuous Integration/Continuous Deployment (CI/CD) pipelines for automated validation during software development cycles.
-Feedback Loop: Rapid feedback from automated tests allows early detection and resolution of issues, contributing to improved software quality and user experience.
