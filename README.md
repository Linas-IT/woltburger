# Cypress Test Scenario For Order Burger to Kaunas dokas offcie
# Installing Cypress and Launching Test Scripts
This guide provides step-by-step instructions on how to install Cypress for test automation and launch test scripts.

# Prerequisites
Before getting started, ensure that you have Node.js and npm installed on your system.

# Installation Steps
# Step 1: Download Node.js Installer
Visit the official Node.js website and download the Windows Installer (.msi) file.

# Step 2: Run the Installer
Double-click the downloaded .msi file to initiate the Node.js Setup Wizard.

# Step 3: Follow Setup Instructions
Follow the instructions in the setup wizard, including accepting the license agreement and selecting the installation location.

# Step 4: Complete the Installation
Once the installation is complete, Node.js and npm will be installed on your Windows system.

# Step 2: Open the Folder in Visual Studio Code or Any IDE
Open the project folder in your preferred text editor or integrated development environment (IDE).

# Step 3: Create package.json
In the project folder, create a package.json file using the following command in the terminal:

npm init -y
# Step 4: Install Cypress
To install Cypress locally as a dev dependency for your project, run the following command in the terminal:

npm install cypress --save-dev

# Direct download
If you're not using Node or a package manager (npm, pnpm or Yarn) in your project or you want to try Cypress out quickly, you can always download <a href="Cypress directly from our CDN.">(https://download.cypress.io/desktop)</a>
# Step 5: Open Cypress Test Runner
Once Cypress is installed, you can open the Cypress Test Runner by running the following command:

# npx cypress open or cypress open
After executing this command npx cypress open or cypress open, the Cypress Test Runner will launch, allowing you to select and run your test scripts.

# Running Test Scripts
To run a specific test file within the Cypress Test Runner, click on the desired test file in the Cypress interface.

Alternatively, you can run tests using the command line interface with the following command
