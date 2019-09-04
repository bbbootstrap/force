This is an example html app created.Additionally this example app is configured to run tests in various CI platforms. The tests are also heavily commented.

If you are looking for BitBucket Pipelines example, check out bitbucket.org/cypress-io/cypress-example-kitchensink.

Help + Testing
If you get stuck, here is more help:

Gitter Chat
Cypress Docs
1. Fork this repo
If you want to experiment with running this project in Continous Integration, you'll need to fork it first.

After forking this project in Github, run these commands:

npm start
The npm start script will spawn a webserver on port 8080 which hosts the html app.

You can verify this by opening your browser and navigating to: http://localhost:8080

You should see qhtml  up and running. We are now ready to run Cypress tests.

## launch the cypress test runner
npm run cy:open
shortcut: you can use command npm run local:open that uses start-server-and-test to start local server. When you close Cypress, the local server is stopped automatically. Similarly you can use npm run local:run to start the server, run Cypress tests headlessly and close the server.

2. Install & write
Follow these instructions to install and write tests in .

Contributing
Check out the Contributing Guideline.
