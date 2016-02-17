# Mendix Starter for IBM Bluemix

This is a basic starter application to deploy Mendix to [IBM Bluemix](http://bluemix.net).

##### Deploy to Bluemix

Option 1 (launch this app directly from this repo):

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/mendix/ibmboilerplate)

Option 2 (deploy from your local machine):

1. Open a terminal prompt to the directory of your application.
2. If you don't have a Bluemix account, [create a free one here](https://console.ng.bluemix.net/registration/).
3. Set your Cloud Foundry CLI tool's API endpoint to Bluemix: `cf api https://api.ng.bluemix.net `
4. Login to Bluemix via the command line: `cf login`
5. Create the MongoDB service on Bluemix: `cf create-service elephantsql turtle mendix-db`
6. Push your app to bluemix with `cf push`
