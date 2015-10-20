# How-to-Create-an-App-using-Covisint-Developer-Portal
User guide for developers to access Covisint Cloud Platform
Overview
	
	
The Developer Portal is the designated environment used for importing applications, staging, testing, and production. 
The Developer Portal requires an identity realm for managing companies and users with external and internal accounts.
Components of Covisint Developer Portal consist of:

● Platform Applications and APIs 
● Platform Application Services 
● Platform Administration (e.g. SDKs that provide application access to the platform libraries)

For more information: For more details: https://developer.covisint.com/learn/dp/-/bookdeveloper-portal_portal_solution_center.html
 

To create an application on Covisint Developer Portal the system requirements are:

Eclipse Luna
Java JDK version 8
Local Installation of Liferay 6.2
Maven Central archetype catalog configured



1.0 Setting Up a Solution Instance

Solution instances, also known as instances, allow grouping of platform resources run simultaneously. 
Each instance has its own portal and identity realm, which identifies the instance type and its behavior 
within a development, pre-production, or production environment. Instances are the target of deployments for 
releases and create multiple instances for a solution.Once your instance has been successfully provisioned, go back to the Instance page, 
and click on the instance name to note down the instance details. The admin login Id is always “[SOLUTION ALIAS-INSTANCE ALIAS_ADMIN]”. 
This is the SEED ACCOUNT for this solution instance 

For more information: https://s-platform-covs.portal.stg.covapp.io/learn/dp/-/book/developer-portal/managing_instances/manage_applications.html


2.0 Creating an Application using Covisint Developer Portal

2.1 How to configure your Application to the Developer Portal 



3.0 How to Access the SDK
The SDK will allow client access to the API at the endpoint. Key features of the Covisint Developer Solution Center 
include having the ability to build portlets, self-service deployments, instance management, logging/debugging, and monitoring within the solution, 
by selecting “new application”, identify the application name and description and “save” allowing customization of an application based upon requirement. 
The Covisint SDK dependencies file are available in the library on the Developer Portal.  You must create a solution instance in order to add applications that will provide 
the secret access The AppID, ClientID, and the client secret button will appear. 
The Class will populate the portlet by default. The SDK client (i.e. Person SDK, Service SDK, etc.) endpoint is created with Covisint API.

For more information: https://github.com/Covisint/samples/tree/master/http-api-clients

3.1 How to deploy the instance

3.2 Putting the App on the Developer Portal
