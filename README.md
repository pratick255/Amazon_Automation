Amazon Product Workflow Automation – Selenium TestNG
📌 Project Overview

This project demonstrates Selenium WebDriver automation for a real-world e-commerce workflow using Amazon.com.
It automates a product search flow and validates that the Product Details Page is successfully loaded by checking key UI elements.

The project is built to showcase:

Handling dynamic web elements

Proper use of explicit waits

Clean TestNG-based automation

Screenshot capture after validation

🎯 Automated Scenario

The following workflow is automated:

Navigate to Amazon homepage

Search for a product (example: Laptop)

Click on the first product from the search results

Validate that the Product Details Page is loaded
(by checking the presence of elements like Add to Cart / Buy options)

Capture a screenshot of the Product Details Page

🛠️ Tech Stack Used

Java

Selenium WebDriver

TestNG

Maven

ChromeDriver

📁 Project Structure
Amazon
├── screenshots
│    ├── ProductDetailsPage.png
│    └── FailureScreenshot.png
│
├── src
│    └── test
│         └── java
│              ├── daspratick.com
│              └── Test
│                   ├── Test1.java
│                   └── Test2.java
│
├── testng.xml
├── pom.xml
└── README.md

▶️ How to Execute the Test
Option 1: Run using TestNG XML (Recommended)

Open the project in IntelliJ IDEA

Right-click on testng.xml

Click Run 'testng.xml'

This will execute the Test2 class as configured.

Option 2: Run directly from Test class

Open Test2.java

Right-click → Run as TestNG Test

📸 Screenshots

ProductDetailsPage.png
→ Captured after successful validation of the product page (requirement-compliant)

FailureScreenshot.png
→ Captured only if the test fails, for debugging purposes

Screenshots are stored inside the screenshots folder at the project root.

⏱️ Wait Strategy Used

WebDriverWait (Explicit Waits) are used to handle:

Dynamic page loads

Search results rendering

Product page elements visibility

This ensures the script is stable and reliable.

👤 Author

Pratick
QA Automation Engineer
