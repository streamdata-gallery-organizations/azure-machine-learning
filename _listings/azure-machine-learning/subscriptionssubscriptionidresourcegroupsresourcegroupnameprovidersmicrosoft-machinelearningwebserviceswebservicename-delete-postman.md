{
  "info": {
    "name": "Azure Machine Learning API Web Services Remove",
    "_postman_id": "a83dba56-c997-4332-ae12-836ea70fe259",
    "description": "Deletes the specified web service.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "web services",
      "item": [
        {
          "id": "69394813-ba11-4e65-866f-e1401ff89e3f",
          "name": "WebServices_Remove",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified web service"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "089225be-6b4a-4ffb-8e8e-c2f8e3a30b02"
            }
          ]
        }
      ]
    }
  ]
}