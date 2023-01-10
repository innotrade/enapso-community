# ENAPSO Community

ENAPSO provides a variety of Knowledge Graph services via a standard REST API. The following table provides a quick overview of the different microservices offered:

| Microservice | Description |
| --- | --- |
| Individual Management | Create, read, search, modify, and delete (CRUD) individuals and their relations in the Knowledge Graph. |
| Ontology Management | Manage classes, properties, and annotations such as labels and comments, taxonomies, relations, and restrictions. |
| Graph Database Management | Manage repositories, named graphs, users, permissions, and roles, upload and download ontologies. |
| SPARQL Assistant | Generator for automatic generation of complex SPARQL query and update commands. |
| API Assistant | Manage the high-level routes for the REST API (CRUD endpoints) for classes and individuals, and OpenAPI generation. |
| Cache Management | Class cache over multiple named graphs to speed up query generators and queries, cache distribution. |

## Getting Started

For an easy start into the development of your own semantic applications, a free Postman collection with all API calls is available for download in this repository.

In addition to the collection with the API calls, a consumer and a maintainer environment are available for Postman. The consumer environment configures a user with read-only rights, the maintainer environment configures a user with roles for write operations and administrative functions.

## Authentication and Authorization

Authentication is required before the first request is executed. In Postman, you first select the environment (Consumer or Maintainer), and then execute the login call. The token returned in the response is automatically stored in an environment variable, and ENAPSO is ready to process the first requests from Postman.

## Additional Resources

For more information on the ENAPSO Community SDK and its capabilities, please visit the [INNOTRADE website](https://innotrade.com/). If you have any questions or need assistance, please reach out to our team by emailing support@innotrade.com. We're happy to help you get started with ENAPSO and start building your own Knowledge Graph applications.

