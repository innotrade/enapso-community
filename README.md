# ENAPSO Community

ENAPSO is a powerful platform for building Knowledge Graph applications, providing a wide range of microservices through a standard REST API. Our SDK makes it easy for developers to create, manage, and query knowledge graph data, enabling you to build intelligent and highly-connected applications.

With the ENAPSO Community, you'll have access to the following microservices:

| Microservice    | Description                                                                                                                                                                                                                                                                                                                                                                                   |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Individual Management | Create, read, search, modify, and delete (CRUD) individuals and their relations in the Knowledge Graph.                                                                                                                                                                                                                                                                                            |
| Ontology Management  | Manage classes, properties, and annotations such as labels and comments, taxonomies, relations, and restrictions.                                                                                                                                                                                                                                                                                 |
| Graph Database Management | Manage repositories, named graphs, users, permissions, and roles, upload and download ontologies.                                                                                                                                                                                                                                                                                                              |
| SPARQL Assistant    | Generator for automatic generation of complex SPARQL query and update commands.                                                                                                                                                                                                                                                                                                                                      |
| API Assistant       | Manage the high-level routes for the REST API (CRUD endpoints) for classes and individuals, and OpenAPI generation.                                                                                                                                                                                                                                                                                      |
| Cache Management    | Class cache over multiple named graphs to speed up query generators and queries, cache distribution.                                                                                                                                                                                                                                                                                                         |
| View Management    | Coming soon 🔜                                                                                                                                                                                                                                                                                                        |
| Recommendation Assistant    | Coming soon 🔜                                                                                                                                                                                                                                                                                                         |
| Quality Management    | Coming soon 🔜                                                                                                                                                                                                                                                                                                         |

By using the SDK APIs, you'll be able to easily create, manage, and query your own knowledge graph data, making it possible to build intelligent and highly-connected applications, you'll have the tools you need to unlock the power of knowledge graph technology and take your applications to the next level.

## Getting Started

For an easy start into the development of your own semantic applications, a free Postman collection with all API calls is available for download in this repository.

In addition to the collection with the API calls, a consumer and a maintainer environment are available for Postman. The consumer environment configures a user with read-only rights, the maintainer environment configures a user with roles for write operations and administrative functions.

## Authentication and Authorization

Authentication is required before the first request is executed. In Postman, you first select the environment (Consumer). The token returned in the response is automatically stored in an environment variable, and ENAPSO is ready to process the first requests from Postman. 

**The Maintainer environment is available on request by contacting our support team at support@innotrade.com**

## Additional Resources

In addition to the API documentation and Postman collection provided in this repository, we have also created a comprehensive wiki to guide you through using the ENAPSO SDK. The wiki includes detailed explanations of each microservice, along with step-by-step instructions and screenshots to help you get started quickly and easily. Whether you're new to ENAPSO or an experienced developer, the wiki is a valuable resource for a deeper dive into the ENAPSO SDK's features and capabilities.


Please note that the consumer environment is configured with read-only rights, providing limited functionality of the APIs. For extended functionality or access to all the features of the SDK, please email us at support@innotrade.com. Our dedicated support team is ready to assist you and help you to utilize the full power of our platform to enhance your applications with knowledge graph technology. Also, we are open to hearing all your queries related to the SDK and its usage on local environments and partnership opportunities.
