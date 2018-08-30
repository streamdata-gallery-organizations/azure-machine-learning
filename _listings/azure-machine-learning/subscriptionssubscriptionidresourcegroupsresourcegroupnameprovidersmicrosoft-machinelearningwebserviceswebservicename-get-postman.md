{
  "info": {
    "name": "Azure Machine Learning API Web Services Get",
    "_postman_id": "c2ff85c0-c267-4185-ac6a-eb5f775529ae",
    "description": "Gets the Web Service Definition as specified by a subscription, resource group, and name. Note that the storage credentials and web service keys are not returned by this call. To get the web service access keys, call List Keys.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "web services",
      "item": [
        {
          "id": "e64003a4-d092-45b7-9e73-bc8ec92bd822",
          "name": "WebServices_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.MachineLearning/webServices/:webServiceName"
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the Web Service Definition as specified by a subscription, resource group, and name"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d7ebcd7-1047-4232-bb58-106789388b6c"
            }
          ]
        }
      ]
    }
  ]
}