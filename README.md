# Playwright_setup
# Prerequisites
Node JS 
Run on your cmd 
npm --version / npm -v 
node --version / node -v

If not existing then download https://nodejs.org/en/download

IDE (VSCode easy to use and available some Playwright extensions)

Install using command as npm package

Step 1 - Create a new folder and open in VS Code
Step 2 - Goto Terminal and run command - npm init playwright@latest
Step 3 - Following will be added
  - package.json - node project management file
  - playwright.config.js - Configuration file
  - tests folder -  basic example test
  - tests-examples folder - detailed example tests
  - .gitignore - to be used during git commit and push
  - playwright.yml - to be used during ci cd pipeline (github workflows)
Step 4 - Check playwright added - npm playwright -v
Step 5 - Check playwright command options - npx playwright -h

(optional)Using VS Code extension 

Step 1 - Create a new folder and open in VS Code
Step 2 - Goto Extensions section and install Playwright extension from Microsoft
Step 3 - Goto View - Command Palette and type playwright - select install playwright
Step 4 - Select the browsers and click ok
Step 5 - It will install the libraries and create the project folders



Test Explorer in VS Code 
Ctrl + Shift + P --> 
