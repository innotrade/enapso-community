![ENAPSO](https://i.postimg.cc/RVRg2dGv/community-4.png)



<div align="center">
  <h1><span style="font-weight:bold; color: #4299E1;">ENAPSO</span> Community</h1>
  
   <a href="https://www.npmjs.com/package/@innotrade/enapso-graphdb-client"><img src="https://img.shields.io/badge/ENAPSO-Client-green" /></a>
   <a href="https://www.npmjs.com/package/@innotrade/enapso-graphdb-admin"><img src="https://img.shields.io/badge/ENAPSO-Admin-blue" /></a>
   <a href="https://www.npmjs.com/package/@innotrade/enapso-graphdb-cli"><img src="https://img.shields.io/badge/ENAPSO-CLI-yellow" /></a>
  <a href="https://github.com/innotrade/enapso-graphdb-client/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202-blue" /></a>
  <a href="https://github.com/innotrade/enapso-graphdb-client/blob/main/CODE_OF_CONDUCT.md"><img src="https://img.shields.io/badge/code-Conduct-orange" /></a>
  <br />
  <br />
  <a href="https://www.innotrade.com/">Website</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://github.com/innotrade/enapso-community/wiki">Documentation</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://github.com/innotrade/enapso-community/issues">Discussion</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://www.facebook.com/InnotradeGmbH/">Facebook</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://twitter.com/innotrade?lang=en">Twitter</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://de.linkedin.com/company/innotrade-gmbh">LinkedIn</a>
  <br />
  <hr />
</div>

ENAPSO is a powerful platform for building Knowledge Graph applications, providing a wide range of microservices through a standard REST API. ENAPSO makes it easy for developers to create, manage, and query knowledge graph data, enabling you to build intelligent and highly-connected applications.

With the ENAPSO Community, you'll have access to the following microservices:

| Microservice    | Description                                                                                                                                                                                                                                                                                                                                                                                   |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 👤 Individual Management | Create, read, search, modify, and delete (CRUD) individuals and their relations in the Knowledge Graph. Understand the relationships and connections between individuals, and have full control over the data that represents them.                                                                                                                                                                                                                                                                                        |
| 📚 Ontology Management  | Manage classes, properties, and annotations such as labels and comments, taxonomies, relations, and restrictions. Create and manage your own ontologies, or use pre-built ones. Define the classes, properties, and relations in your knowledge graph, and ensure that your data is structured and organized in a meaningful way.                                                                                                                                                                                                                                                                                |
| 📈 Graph Database Management | Manage repositories, named graphs, users, permissions, and roles, upload and download ontologies.                                                                                                                                                                                                                                                                                                              |
| 🧩 SPARQL Assistant    | Generator for automatic generation of complex SPARQL query and update commands. Use the power of SPARQL to query your data, and use the generator to create complex queries easily, without having to worry about the syntax.                                                                                                                                                                                                                                                                                                                                                    |
| 🔧 API Assistant       | Manage the high-level routes for the REST API (CRUD endpoints) for classes and individuals, and OpenAPI generation.                                                                                                                                                                                                                                                                                   |
| ⚙️ Cache Management    | Class cache over multiple named graphs to speed up query generators and queries, cache distribution. Enhance the performance of your application by caching common queries and data, and ensure that your users always have a fast and responsive experience.                                                                                                                                                                                                                                                                                                     |
| 🔍 View Management    | We are excited to announce that this service will enable users to easily create and manage SPARQL templates, providing the ability to set custom variables for enhanced flexibility and customization. This will greatly simplify data management and pave the way for more efficient querying. We look forward to sharing this new development with you in the near future.                                                                                                                                                                                                                                                                                                      |
| 🔜 Recommendation Assistant    | Coming soon! - We are excited to announce that this service will allow users to create their custom models using their own data and domains, enabling them to receive tailored recommendations that align with their specific needs. This will greatly enhance the precision and effectiveness of recommendations. We look forward to sharing this new development with you in the near future                                                                                                                                                                                                                                                                                                         |
|🔜  Quality Management    | Coming soon! - Ensure the integrity and accuracy of your data with this service which will prevent insertion of incorrect data, ensuring that your data is always of the highest quality. We look forward to sharing this new development with you in the near future                                                                                                                                                                                                                                                                                                        |


## 🚀 Getting Started

To get started with ENAPSO, follow these simple steps:

1. Download our free Postman collection with all API calls from this [ENAPSO Postman Collection](https://raw.githubusercontent.com/innotrade/enapso-community/main/ENAPSO.postman_collection.json). To download, click on the link and then right-click select "Save As" to save the file to your computer's Downloads folder. You can also find it in the root directory of our GitHub page.

2. Select the appropriate environment based on your requirements:
    * If you want to test the functionalities of our platform, use the  [**Consumer Environment**](https://raw.githubusercontent.com/innotrade/enapso-community/main/ENAPSO-Cloud%20(Consumer).postman_environment.json)(open the link and then right-click select "Save As" to save the file). This environment provides read-only rights and is perfect for testing and evaluating ENAPSO before using it in your own applications. Note that this environment is running in our cloud.
    * If you want your own isolated tenant to work with your own data, fill out [this form](https://www.innotrade.com/enapso-tenant-registration) to request access to a tenant. Our support team will assist you in setting it up, and the tenant will be available as a 2-week trial for you to test the functionality. Note that this environment is also running in our cloud.
    * If you want to operate ENAPSO on-premises, such as running it locally in your own Docker instance or Kubernetes environment, contact us at support@innotrade.de, and we can provide you with the credentials to access the images through our container registry. To learn more about how you can deploy ENAPSO services locally, you can follow this [link](https://github.com/innotrade/enapso-community/wiki/ENAPSO-Platform-Services-on-On-Premises-Solutions-with-Kubernetes-and-Docker-Compose).

3. Authenticate yourself by executing the login call. The token returned in the response will automatically be stored in an environment variable.

4. You're all set! Start building your own intelligent and highly-connected applications using ENAPSO.

Note: If you need help with importing Postman collections and environments, you can refer to the documentation available in this [link](https://github.com/innotrade/enapso-community/wiki/Importing-Postman-Collections-&-Environments).

## 🔑 Authentication and Authorization

Authentication is required before you can use ENAPSO. To authenticate yourself, follow these steps:

1. Select the environment you want to use (Consumer or a custom one).
2. Execute the login call.
3. The token returned in the response will automatically be stored in an environment variable.

Please note that the Consumer environment is configured with read-only rights, providing limited functionality of the APIs. If you are looking to access all the features and extended functionality of ENAPSO, please fill out [this form](https://www.innotrade.com/enapso-tenant-registration) and request your own tenant. Our team will be happy to assist you and help you take full advantage of our platform which would be available as a 2-week trial for you to test the functionality.

For any queries related to ENAPSO's usage on local environments and partnership opportunities, contact us at support@innotrade.de

## 📙 Additional Resources
Along with API documentation and Postman collection available in this repository, We also have created a comprehensive wiki to guide you through the use of ENAPSO. The wiki includes detailed explanations of each microservice, along with step-by-step instructions and screenshots to help you get started quickly and easily. Whether you're new to ENAPSO or an experienced developer, the wiki is a valuable resource for understanding and using ENAPSO to its full potential.

## 📧 Contact Us
For more information on ENAPSO and its capabilities, please visit the INNOTRADE website. If you have any questions or need assistance, please reach out to our team by emailing support@innotrade.com. We're happy to help you get started with ENAPSO and start building your own Knowledge Graph applications. Also, we are open to hearing all your queries related to its usage on local environments and partnership opportunities."

