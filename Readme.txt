npm install --save -dev cypress
npm install --save -dev cypress-dark
npm install --save -dev cypress-cucumber-preprocessor
npm install -D cypress-xpath
npm install --save-dev cypress-file-upload
npm install --save-dev @percy/cypress

//it will open the cypress console.
npx cypress open
//To execute the script from command line
npx cypress run --spec C:\Users\nalla\OneDrive\Documents\Cypress\CypressKarthik\cypress\integration\examples\eaapp.spec.js --browser chrome

//percy
set PERCY_TOKEN=439be6d654e89e1be15a7f6595c4d908cec542235e0db5bf479961efd04060f5
  npx percy exec --cypress run

//Dashboard
 npx cypress run --record --key b79a9e2d-8796-4836-83f2-689d8b55488c
  npx cypress run --record --key b79a9e2d-8796-4836-83f2-689d8b55488c --parallel 

Reports :
npx mochawesome-merge --reportDir cypress/reports/mocha > mochareports/reports.json
npx marge mochareports/*.json -f report -o mochareports
                         

Documents:
 https://www.cypress.io/
 https://github.com/TheBrainFamily/cypress-cucumber-preprocessor


 Plugins in vscode :
 Cucumber (Gherkin) Full Support
