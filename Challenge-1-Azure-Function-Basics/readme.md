# Challenge 1 - Create and deploy your first Azure Function

In this challenge you will create your first serverless
function and deploy it into Azure.

## Prerequisites

[TODO: Refresh this content]

## Challenge

### Create a local function
Your first goal is to create and debug an HTTP
triggered Azure Function locally on your own development machine. This
function has the following requirements:

* **Verb**: GET
* **Input parameters**: A `productId` value is passed to it as a
query parameter or an HTTP route
* **Response**: "The product name for your product id
{`productId`} is Starfruit Explosion"

### Deploy to Azure
The second goal is to create an Azure Resource
Group in your Azure Subscription, and deploy the function to Azure. Test the
function after it has been deployed to verify that it works.

**Make sure to use different, unique Function App names!**

## Success Criteria

The following goals must be met to successfully complete this challenge:


* Demonstrate that you created an HTTP triggered
Azure Function locally that accepts a GET verb. Show that you
can call that function and receive a successful response with the right text
provided and the value of `productId` properly filled in.

* Show that you deployed that HTTP triggered
Azure Function to Azure. Call that deployed
function and receive a successful response.


## References

* [An introduction to Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)

* Review the [Supported Languages in Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/supported-languages)
  guide and go into the specific guide for the language you are using

* [Strategies for testing your code in Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-test-a-function)

* [Code and test Azure Functions locally](https://docs.microsoft.com/en-us/azure/azure-functions/functions-develop-local)

* [Azure Functions HTTP and webhook bindings](https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook)

## Next Challenge

Once you have your function working and deployed, proceed to the next challenge and begin - [Cosmos DB and Azure Functions](..//Challenge-2-Cosmos-DB-and-Azure-Functions/readme.md).