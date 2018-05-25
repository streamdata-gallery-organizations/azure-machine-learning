---
swagger: "2.0"
x-collection-name: Azure Machine Learning
x-complete: 0
info:
  title: Azure Machine Learning API Web Services Patch
  description: Modifies an existing web service resource. The PATCH API call is an
    asynchronous operation. To determine whether it has completed successfully, you
    must perform a Get operation.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices/{webServiceName}
  : put:
      summary: Web Services Create Or Update
      description: Create or update a web service. This call will overwrite an existing
        web service. Note that there is no warning or confirmation. This is a nonrecoverable
        operation. If your intent is to create a new web service, call the Get operation
        first to verify that it does not exist.
      operationId: WebServices_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-put
      parameters:
      - in: body
        name: createOrUpdatePayload
        description: The payload that is used to create or update the web service
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Web Services
    get:
      summary: Web Services Get
      description: Gets the Web Service Definition as specified by a subscription,
        resource group, and name. Note that the storage credentials and web service
        keys are not returned by this call. To get the web service access keys, call
        List Keys.
      operationId: WebServices_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: region
        description: The region for which encrypted credential parameters are valid
      responses:
        200:
          description: OK
      tags:
      - Web Services
    patch:
      summary: Web Services Patch
      description: Modifies an existing web service resource. The PATCH API call is
        an asynchronous operation. To determine whether it has completed successfully,
        you must perform a Get operation.
      operationId: WebServices_Patch
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: patchPayload
        description: The payload to use to patch the web service
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Web Services
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---