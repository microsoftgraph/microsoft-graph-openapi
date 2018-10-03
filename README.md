# Microsoft Graph OpenAPI v3.0.1 description (preview)

## OpenAPI description for Microsoft Graph 
This repo has the OpenAPI representation for the resources and level 1 relationships in Microsoft Graph, for /v1.0 and /beta. Given the size of the Microsoft Graph API, this is not a full representation, but a starting point that works for most interoperability scenarios. At this point in time we can’t make it much bigger without breaking tools or usability. 
Our plans are to expose the OpenAPI descriptions for Microsoft Graph as part of the service itself, in a similar way that we expose the EDM at https://graph.microsoft.com/v1.0/$metadata endpoint. In the meantime we are making this preview version available in this repo for you to evaluate it and share feedback. 

## Microsoft Graph
Microsoft Graph is made up of resources connected by relationships. For example, a user can be connected to a group through a memberOf relationship, and to another user through a manager relationship. Your app can traverse these relationships to access these connected resources and perform actions on them through the API.
You can also get valuable insights and intelligence about the data from Microsoft Graph. For example, you can get the popular files trending around a user or get the most relevant people around a user.
Find more information at [Microsoft Graph](https://developer.microsoft.com/en-us/graph/docs/concepts/overview) site.

## OpenAPI specification
OpenAPI specification is an API description standard by the OpenAPI initiative. It allows an API to be described in a human and computer readable format. Find more information at [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) GitHub site.

## Mapping (OData -> OpenAPI mapping)
The OpenAPI representation for OData based Microsoft Graph has been done with the help of the [OpenAPI.Net.OData](https://github.com/Microsoft/OpenAPI.NET.OData) library. Based on the OASIS conventions defined for converting OData => OpenAPI, we used the openapi.net.odata lib to create the description for MS Graph. 

## Documentation and resources
Detailed documentation and other learning resources for Microsoft Graph can be found on the [Microsoft Graph](https://developer.microsoft.com/en-us/graph/docs/concepts/overview) site.

## Contribute
We value your feedback and contribution. Please report any issues at [Microsoft Graph OpenAPI issues](https://github.com/microsoftgraph/microsoft-graph-open-api-v3/issues)

## Terms Of Use
When you use the Microsoft Graph API, you agree to the [Microsoft Graph Terms of Use](https://aka.ms/msgraphtou) and the [Microsoft Privacy Statement](https://go.microsoft.com/fwlink/?LinkId=521839).

## Issues
To view or log issues, see [issues](https://github.com/microsoftgraph/microsoft-graph-open-api-v3).

## License
Copyright (c) Microsoft Corporation. All Rights Reserved. Licensed under the MIT [license](LICENSE).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
