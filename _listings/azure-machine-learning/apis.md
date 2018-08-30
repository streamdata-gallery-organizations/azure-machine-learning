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
x-alexaRank: "0"
tags: Azure Machine Learning
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/apis.md
specificationVersion: "0.14"
apis:
- name: Azure ML Web Services Management Client - Web Services Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-put
  description: Create or update a web service. This call will overwrite an existing
    web service. Note that there is no warning or confirmation. This is a nonrecoverable
    operation. If your intent is to create a new web service, call the Get operation
    first to verify that it does not exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com//
  tags: Machine Learning, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-put-openapi.md
- name: Azure ML Web Services Management Client - Web Services Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-get
  description: Gets the Web Service Definition as specified by a subscription, resource
    group, and name. Note that the storage credentials and web service keys are not
    returned by this call. To get the web service access keys, call List Keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com//
  tags: Machine Learning, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-get-openapi.md
- name: Azure ML Web Services Management Client - Web Services Patch
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-patch
  description: Modifies an existing web service resource. The PATCH API call is an
    asynchronous operation. To determine whether it has completed successfully, you
    must perform a Get operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com//
  tags: Machine Learning, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-patch-openapi.md
- name: Azure ML Web Services Management Client - Web Services Remove
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-delete
  description: Deletes the specified web service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com//
  tags: Machine Learning, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicename-delete-openapi.md
- name: Azure ML Web Services Management Client - Web Services Create Regional Properties
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicenamecreateregionalblob-post
  description: Creates an encrypted credentials parameter blob for the specified region.
    To get the web service from a region other than the region in which it has been
    created, you must first call Create Regional Web Services Properties to create
    a copy of the encrypted credential parameter blob in that region. You only need
    to do this before the first time that you get the web service in the new region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com//
  tags: Machine Learning, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicenamecreateregionalblob-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicenamecreateregionalblob-post-openapi.md
- name: Azure ML Web Services Management Client - Web Services List Keys
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicenamelistkeys-get
  description: Gets the access keys for the specified web service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com//
  tags: Machine Learning, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicenamelistkeys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebserviceswebservicenamelistkeys-get-openapi.md
- name: Azure ML Web Services Management Client - Web Services List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebservices-get
  description: Gets the web services in the specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com//
  tags: Machine Learning, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebservices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-machinelearningwebservices-get-openapi.md
- name: Azure ML Web Services Management Client - Web Services List By Subscription
    Id
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-machinelearningwebservices-get
  description: Gets the web services in the specified subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-simple-scalable-cutting-edge.jpg
  humanURL: https://azure.microsoft.com/en-us/services/machine-learning/
  baseURL: ://management.azure.com//
  tags: Machine Learning, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidprovidersmicrosoft-machinelearningwebservices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-machine-learning/master/_listings/azure-machine-learning/subscriptionssubscriptionidprovidersmicrosoft-machinelearningwebservices-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.logic.apps.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.machine.learning.stack.network
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