steps to run the cypress test on local machine
you should have vs code installed on your local machine
download prejocet from given repo (main)
unzip the folder from finder
prerequists: You should have cypress, node and npm should install on your project level 
open terminal 
run the bolow cucumber commands to install cucumber plugins to project
npm i -D cypress cypress-cucumber-preprocessor
npm install -save-dev cypress-cucumber-preprocessor
to run cypress project use the following command "npx cypress open"
to see the report use the following command "node ./cypress/cucumberReport.js"
after ran the above command
right click on index.js, select reveal on folder, the double click to see html report on browser 
