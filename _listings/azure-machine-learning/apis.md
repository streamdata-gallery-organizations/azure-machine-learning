---
name: Azure Machine Learning
x-slug: azure-machine-learning
description: Azure Machine Learning lets you easily design, test, operationalize,
  and manage predictive analytics solutions in the cloud. Azure Machine Learning was
  designed for applied machine learning. Use best-in-class algorithms and a simple
  drag-and-drop interface&mdash;and go from idea to deployment in a matter of clicks.
  Try it free. If youre a developer who wants the data science built in, check out
  our APIs and Azure Marketplace.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Machine Learning
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Machine Learning API Web Services Create Or Update
  x-api-slug: azure-machine-learning-api
  description: Create or update a web service. This call will overwrite an existing
    web service. Note that there is no warning or confirmation. This is a nonrecoverable
    operation. If your intent is to create a new web service, call the Get operation
    first to verify that it does not exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices/{webServiceName}
  tags: Web Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicename-put-openapi.md
- name: Azure Machine Learning API Web Services Get
  x-api-slug: azure-machine-learning-api
  description: Gets the Web Service Definition as specified by a subscription, resource
    group, and name. Note that the storage credentials and web service keys are not
    returned by this call. To get the web service access keys, call List Keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices/{webServiceName}
  tags: Web Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicename-get-openapi.md
- name: Azure Machine Learning API Web Services Patch
  x-api-slug: azure-machine-learning-api
  description: Modifies an existing web service resource. The PATCH API call is an
    asynchronous operation. To determine whether it has completed successfully, you
    must perform a Get operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices/{webServiceName}
  tags: Web Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicename-patch-openapi.md
- name: Azure Machine Learning API Web Services Remove
  x-api-slug: azure-machine-learning-api
  description: Deletes the specified web service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices/{webServiceName}
  tags: Web Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicename-delete-openapi.md
- name: Azure Machine Learning API Web Services Create Regional Properties
  x-api-slug: azure-machine-learning-api
  description: Creates an encrypted credentials parameter blob for the specified region.
    To get the web service from a region other than the region in which it has been
    created, you must first call Create Regional Web Services Properties to create
    a copy of the encrypted credential parameter blob in that region. You only need
    to do this before the first time that you get the web service in the new region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices/{webServiceName}/CreateRegionalBlob
  tags: Web Services Regional Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicenamecreateregionalblob-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicenamecreateregionalblob-post-openapi.md
- name: Azure Machine Learning API Web Services List Keys
  x-api-slug: azure-machine-learning-api
  description: Gets the access keys for the specified web service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices/{webServiceName}/listKeys
  tags: Web Services Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicenamelistkeys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebserviceswebservicenamelistkeys-get-openapi.md
- name: Azure Machine Learning API Web Services List By Resource Group
  x-api-slug: azure-machine-learning-api
  description: Gets the web services in the specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.MachineLearning/webServices
  tags: Web Services Resource Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebservices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftmachinelearningwebservices-get-openapi.md
- name: Azure Machine Learning API Web Services List By Subscription Id
  x-api-slug: azure-machine-learning-api
  description: Gets the web services in the specified subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.MachineLearning/webServices
  tags: Web Services Subscription Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidprovidersmicrosoftmachinelearningwebservices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidprovidersmicrosoftmachinelearningwebservices-get-openapi.md
- name: Azure Machine Learning API
  x-api-slug: azure-machine-learning-api
  description: Azure Machine Learning lets you easily design, test, operationalize,
    and manage predictive analytics solutions in the cloud. Azure Machine Learning
    was designed for applied machine learning. Use best-in-class algorithms and a
    simple drag-and-drop interface&mdash;and go from idea to deployment in a matter
    of clicks. Try it free. If youre a developer who wants the data science built
    in, check out our APIs and Azure Marketplace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com//
  tags: Azure Machine Learning
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/machine-learning/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/machine-learning/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/machine-learning/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/machine-learning/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---