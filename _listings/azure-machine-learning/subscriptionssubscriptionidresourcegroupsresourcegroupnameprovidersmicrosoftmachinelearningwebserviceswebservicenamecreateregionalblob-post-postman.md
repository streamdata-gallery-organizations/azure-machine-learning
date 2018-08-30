{
  "info": {
    "name": "Azure Machine Learning API Web Services Create Regional Properties",
    "_postman_id": "099b025e-3970-4127-b19f-ddb71d9a07c5",
    "description": "Creates an encrypted credentials parameter blob for the specified region. To get the web service from a region other than the region in which it has been created, you must first call Create Regional Web Services Properties to create a copy of the encrypted credential parameter blob in that region. You only need to do this before the first time that you get the web service in the new region.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "web services regional properties",
      "item": [
        {
          "id": "d93772b0-da89-41fa-b958-fed9313a9b13",
          "name": "WebServices_CreateRegionalProperties",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.MachineLearning/webServices/:webServiceName/CreateRegionalBlob"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "region",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                },
                {
                  "id": "webServiceName",
                  "value": "webServiceName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an encrypted credentials parameter blob for the specified region"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4563669a-f055-45c3-937a-14081f024110"
            }
          ]
        }
      ]
    }
  ]
}