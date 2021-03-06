---
description: A GraphQL binding for your Neo4j GraphQL API.
---

# Neo4j GraphQL Binding

## Overview

In your server setup, you use can `neo4jGraphQLBinding` to create a [GraphQL binding](https://www.npmjs.com/package/graphql-binding) to the schema used by your Neo4j instance. The binding is set into your server's context object at some key and accessed in your `resolvers` to delegate requests for any generated `query` or `mutation` or those which use a [@cypher directive](https://neo4j.com/developer/graphql/#_neo4j_graphql_extension).

The exports of this package are used to support various features in [neo4j-graphql-server](https://www.npmjs.com/package/neo4j-graphql-server). See this section explaining the [server setup process](https://neo4j-graphql-server.gitbook.io/docs/neo4j-graphql-server#strategy).

## Installation

```text
npm install -s neo4j-graphql-binding
```



