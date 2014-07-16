Get started with Top Dish
-----------------------------------

Welcome to Node JS Web Starter application that uses the IBM DataCache REST interface!

This sample application demonstrates how to write a Node JS application using the IBM DataCache REST interface and deploy it on Bluemix.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/#starters/BuildingWeb.html#install_cf).
2. [Download the starter application package](https://ace.ng.bluemix.net:443/rest/../rest/apps/2fde1c8e-274a-4d59-af19-167abf7bcf54/starter-download).
3. Extract the package and `cd` to it.
4. Connect to Bluemix:

		cf api https://api.ng.bluemix.net

5. Log into Bluemix:

		cf login -u rafamelo.oliveira@gmail.com
		cf target -o HomeGuard -s dev
		
6. Deploy your app:

		cf push Top Dish

7. Access your app: [http://topdish.mybluemix.net](http://topdish.mybluemix.net)
