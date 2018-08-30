swagger: "2.0"
x-collection-name: Azure Machine Learning
x-complete: 1
info:
  title: Azure ML Web Services Management Client
  description: these-apis-allow-end-users-to-operate-on-azure-machine-learning-web-services-resources--they-support-the-following-operationsullicreate-or-update-a-web-serviceliliget-a-web-servicelilipatch-a-web-servicelilidelete-a-web-serviceliliget-all-web-services-in-a-resource-group-liliget-all-web-services-in-a-subscriptionliliget-web-services-keysliul
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
      - Machine Learning
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
      - Machine Learning
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
      - Machine Learning
      - Web Services
    delete:
      summary: Web Services Remove
      description: Deletes the specified web service.
      operationId: WebServices_Remove
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Web Services
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices/{webServiceName}/CreateRegionalBlob
  : post:
      summary: Web Services Create Regional Properties
      description: Creates an encrypted credentials parameter blob for the specified
        region. To get the web service from a region other than the region in which
        it has been created, you must first call Create Regional Web Services Properties
        to create a copy of the encrypted credential parameter blob in that region.
        You only need to do this before the first time that you get the web service
        in the new region.
      operationId: WebServices_CreateRegionalProperties
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicenamecreateregionalblob-post
      parameters:
      - in: query
        name: No Name
      - in: query
        name: region
        description: The region for which encrypted credential parameters are created
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Web Services Regional Properties
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices/{webServiceName}/listKeys
  : get:
      summary: Web Services List Keys
      description: Gets the access keys for the specified web service.
      operationId: WebServices_ListKeys
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicenamelistkeys-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Web Services Keys
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices:
    get:
      summary: Web Services List By Resource Group
      description: Gets the web services in the specified resource group.
      operationId: WebServices_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebservices-get
      parameters:
      - in: query
        name: $skiptoken
        description: Continuation token for pagination
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Web Services Resource Group
  /subscriptions/{subscriptionId}/providers/Microsoft.MachineLearning/webServices:
    get:
      summary: Web Services List By Subscription Id
      description: Gets the web services in the specified subscription.
      operationId: WebServices_ListBySubscriptionId
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-machinelearningwebservices-get
      parameters:
      - in: query
        name: $skiptoken
        description: Continuation token for pagination
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Web Services Subscription Id