Software Architecture & Design
# API Documentation
In this exercise, you will work with OpenAPI specification language to study and experiment with the specification of a RESTful API of a simple PetStore service, use Swagger UI to generate interactive web-based documentation, and Swagger Codegen to generate a fully functional mock server.

1. [Familiarize Yourself with the Swagger Toolset](#familiarize-yourself-with-the-swagger-toolset)
2. [Use Swagger Editor & Learn Key Features of the Specification Language](#use-swagger-editor--learn-key-features-of-the-specification-language)
3. [Spin Up Your Own API Server from Swagger's Mock Servers](#spin-up-your-own-api-server-from-swaggers-mock-servers)

---

# Familiarize Yourself with the Swagger Toolset
https://swagger.io/

# Use Swagger Editor & Learn Key Features of the Specification Language
https://editor.swagger.io/

1. Invoke the /store/inventory API endpoint (get a screenshot).
2. Discover a valid PET ID using the /pet/findByStatus endpoint (get a screenshot).
3. Invoke the /pet/{petId} endpoint (using the PET ID from step "b" above) (get a screenshot).
4. Show an example JSON request payload from the endpoint /store/order (POST) (get a screenshot).

# Spin Up Your Own API Server from Swagger's Mock Servers
Try spinning up your own API server from the mock servers available in Swagger.

1. Generate and download a mock server of your choice using the “Generate Server” tab.
2. Swagger can generate various types of servers, including Java-based, Python-flask, nodejs-server, and many more.
3. The downloaded mock server contains a README file. Follow the instructions in the README file to run a local instance of the mock server. The server binds to a local port and can be used to invoke all functions specified in your API specification.
4. Observe the localhost URL in the address bar and the Swagger documentation in the browser viewer (get a screenshot).
