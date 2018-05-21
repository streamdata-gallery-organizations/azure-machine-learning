{
  "info": {
    "name": "Azure Machine Learning API Web Services List By Resource Group",
    "_postman_id": "e0ee92eb-029b-4744-b372-0e7329b1274a",
    "description": "Gets the web services in the specified resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "web services resource group",
      "item": [
        {
          "id": "a38daf25-2c8a-4d18-9212-71d8dc0d2a8f",
          "name": "WebServices_ListByResourceGroup",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.MachineLearning/webServices"
              ],
              "query": [
                {
                  "key": "$skiptoken",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "No Name",
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the web services in the specified resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fd6a117-651b-4ded-afa2-eb615c2ef906"
            }
          ]
        }
      ]
    }
  ]
}