# ENAPSO Community

ENAPSO is a powerful platform for building Knowledge Graph applications, providing a wide range of microservices through a standard REST API. Our SDK makes it easy for developers to create, manage, and query knowledge graph data, enabling you to build intelligent and highly-connected applications.

With the ENAPSO Community, you'll have access to the following microservices:

| Microservice | Description |
| --- | --- |
| Individual Management | Create, read, search, modify, and delete (CRUD) individuals and their relations in the Knowledge Graph. |
| Ontology Management | Manage classes, properties, and annotations such as labels and comments, taxonomies, relations, and restrictions. |
| Graph Database Management | Manage repositories, named graphs, users, permissions, and roles, upload and download ontologies. |
| SPARQL Assistant | Generator for automatic generation of complex SPARQL query and update commands. |
| API Assistant | Manage the high-level routes for the REST API (CRUD endpoints) for classes and individuals, and OpenAPI generation. |
| Cache Management | Class cache over multiple named graphs to speed up query generators and queries, cache distribution. |

By using the SDK APIs, you'll be able to easily create, manage, and query your own knowledge graph data, making it possible to build intelligent and highly-connected applications, you'll have the tools you need to unlock the power of knowledge graph technology and take your applications to the next level.

## Getting Started

For an easy start into the development of your own semantic applications, a free Postman collection with all API calls is available for download in this repository.

In addition to the collection with the API calls, a consumer and a maintainer environment are available for Postman. The consumer environment configures a user with read-only rights, the maintainer environment configures a user with roles for write operations and administrative functions.

## Authentication and Authorization

Authentication is required before the first request is executed. In Postman, you first select the environment (Consumer or Maintainer), and then execute the login call. The token returned in the response is automatically stored in an environment variable, and ENAPSO is ready to process the first requests from Postman.

## Additional Resources

In addition to the API documentation and Postman collection provided in this repository, we have also created a comprehensive [wiki](https://github.com/innotrade/enapso-community/wiki) to guide you through using the ENAPSO SDK. The wiki includes detailed explanations of each microservice, along with step-by-step instructions and screenshots to help you get started quickly and easily. Whether you're new to ENAPSO or an experienced developer, the wiki is a valuable resource for understanding and using the SDK to its full potential. So, head over to the wiki for a deeper dive into the ENAPSO Community SDK's features and capabilities.

For more information on the ENAPSO Community SDK and its capabilities, please visit the [INNOTRADE website](https://innotrade.com/). If you have any questions or need assistance, please reach out to our team by emailing support@innotrade.com. We're happy to help you get started with ENAPSO and start building your own Knowledge Graph applications.

