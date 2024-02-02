Jumia E-commerce Automation Documentation

This documentation provides an overview and explanation of the two Java classes, forgetpassward and jumiaproject, which are part of an automation project for the Jumia E-commerce website using Selenium WebDriver.

Class: forgetpassward
Purpose
The forgetpassward class demonstrates a basic Selenium script for navigating to the Jumia login page, clicking on the "Forgot Password" link, and entering an email address to initiate the password reset process.

Steps
Setting Up WebDriver:

The webdriver.chrome.driver system property is set to the path of the ChromeDriver executable.
WebDriver is instantiated as a ChromeDriver.
Navigation:

The script navigates to the Jumia login page.
User Interaction:

The "Forgot Password" link is clicked.
An email address is entered into the respective field.
The script clicks the button to proceed.
Class: jumiaproject
Purpose
The jumiaproject class demonstrates a more extensive Selenium script for navigating through the Jumia website, including login, product search, product selection, and the checkout process.

Steps
Setting Up WebDriver:

Similar to the forgetpassward class, WebDriver is configured.
Login:

The script navigates to the Jumia login page.
Email and password are entered, and the login button is clicked.
Product Search and Selection:

A product ("Headphone") is searched.
The first result is hovered over, clicked, and added to the cart.
Checkout Process:

The checkout process involves navigating through various steps.
Shipping address information is entered, including phone number, address, region, and city.
The script saves the address information, proceeds to the next step, and completes the order.
Cleanup:

After the process is completed, the script closes the browser.
Conclusion
These classes showcase basic and advanced interactions with the Jumia website using Selenium WebDriver. They cover actions such as navigation, form filling, clicking elements, and performing complex interactions like hovering over elements. These scripts can serve as a foundation for more comprehensive automated testing scenarios for the Jumia E-commerce platform.
