### Release 2016-12-21 08:00 UTC
* **Amazon.Lambda.Tools (1.0.4-preview1)**
  * Fix issue with zipping application bundles from paths that contain spaces
* **Amazon.Lambda.APIGatewayEvents (1.0.1)**
  * Added IsBase64Encoded property to APIGatewayProxyRequest
* **Amazon.Lambda.AspNetCoreServer (0.8.2-preview1)**
  * Added support for marshaling request body
* **Blueprints**
    * Updated EmptyServerless and DynamoDBBlogAPI to 1.0.1 of Amazon.Lambda.APIGatewayEvents
    * Updated all blueprints to version 1.0.4-preview1 of Amazon.Lambda.Tools

### Release 2016-12-16 01:36 UTC
* **Amazon.Lambda.Tools (1.0.3-preview1)**
	* Fix issue with quoted strings in users path while searching for the dotnet CLI
* **Blueprints**
	* DynamoDBBlogAPI: Change content-type to text/plain for AddBlogAsync which returns the ID of the new blog
    * Updated all blueprints to version 1.0.3-preview1 of Amazon.Lambda.Tools

### Release 2016-12-12 07:30 UTC
* **Amazon.Lambda.Tools (1.0.2-preview1)**
	* Add CAPABILITY_NAMED_IAM capability when performing serverless deployment
	* Add ability to disable capabilities for serverless deployment using the switch **--disable-capabilities**
* **Blueprints**
	* Updated DynamoDBBlogAPI to map GetBlogAsync in serverless.template
	* Updated all blueprints to version 1.0.2-preview1 of Amazon.Lambda.Tools

### Release 2016-12-07 17:30 UTC
* **Amazon.Lambda.Tools (1.0.1-preview1)**
    * Added PowerUserAccess as a managed policy used to create new IAM roles
    * Added support for setting dead letter target with new switch **--dead-letter-target-arn**
* **Blueprints**
    *  Added new "Detect Label Images" blueprint