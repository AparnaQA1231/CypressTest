steps to run the cypress test on the local machine

You should have vs code installed on your local machine
Download the project from the given repo (main)
unzip the folder from Finder

prerequisites: 
You should have Cypress, node, and npm installed on your project level 

open the terminal and run the below cucumber commands to install cucumber plugins to the project
npm i -D cypress cypress-cucumber-preprocessor
npm install -save-dev cypress-cucumber-preprocessor
to run the cypress project use the following command "npx cypress open"
to see the report use the following command "node ./cypress/cucumberReport.js"
after running the above command
right click on index.js, select reveal on the folder, then double-click to see the HTML report on the browser 
