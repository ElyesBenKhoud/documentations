## SKILL DEVELOPMENT

** GRAPHQL DOCS \***

> What is GraphQL ?

- GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data.
- GraphQL is a query language created by Facebook in 2012 which provides a common interface between the client and the server for data fetching and manipulations.
- GraphQL provides a complete and understandable description of the data in your API, gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools.

> How GraphQL is useful ?

- GraphQL helps where your client needs a flexible response format to avoid extra queries and/or massive data transformation with the overhead of keeping them in sync.

> What is the difference between GraphQL and REST API ?

- REST (Representational State Transfer) and GraphQL are both technologies for building APIs (Application Programming Interfaces) that allow clients to request data from servers. However, they have some key differences in their design and the way they work

  1. Over-fetching and under-fetching:
     REST APIs can sometimes suffer from a problem called "over-fetching", where the client receives more data than it needs, or "under-fetching", where the client needs to make multiple requests to get all the data it needs. In contrast, GraphQL allows the client to specify exactly what data it needs in a single request, reducing the need for multiple round trips to the server.
  2. Structure:
     REST APIs have a fixed structure, with a set of fixed endpoints (URLs) for each resource. In contrast, GraphQL APIs have a flexible structure, where the client can request exactly the data it needs, and the shape of the data is determined by the client rather than the server.
  3. Versioning:
     REST APIs often require a new version to be released every time the API changes, which can be a time-consuming and error-prone process. In contrast, GraphQL allows the server to add new fields and types to the API without requiring a new version, making it easier to evolve the API over time.

- REST APIs are a well-established and widely used technology, while GraphQL is a newer and more flexible alternative that is particularly well-suited to modern web and mobile applications.

> What are the core concept of GraphQL ?

    * Schema: A blueprint that defines the types of data that can be queried and the relationships between them.
    * Query: A request for specific fields of data from the schema.
    * Resolver: A function that is responsible for fetching the data for a specific field in the query.
    * Mutations: A way to make changes to the data in the schema, such as creating, updating, or deleting records.
    * Subscriptions: A way to subscribe to real-time updates to the data in the schema.

> Overall

- GraphQL is a query language and runtime that allows clients to request only the data they need, and makes it easy to request data from multiple sources in a single request. It gives the client more control over the data they receive, and allows them to easily retrieve related data without multiple round-trips to the server.

> What means query in GraphQL ?

- A query is a request made by the client to the server for specific data. The client specifies the fields and nested fields it wants to retrieve, and the server responds with the requested data in a JSON format. Queries are used to fetch data from the server and are one of the three main types of operation in GraphQL, along with mutations (used for creating, updating, and deleting data) and subscriptions (used for real-time data updates).

> What is mutation in GraphQL ?

- Mutation is a way to create, update, or delete data on the server. It is one of the three main types of operation in GraphQL, along with queries (used for fetching data) and subscriptions (used for real-time data updates). Mutations are defined on the server and can accept input arguments, just like a query. However, unlike queries, which are used to fetch data, mutations are used to change data. When a mutation is executed, it makes changes to the data on the server and returns a response, typically containing the updated data or a message indicating the result of the operation.
