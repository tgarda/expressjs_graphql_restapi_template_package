# expressjs_graphql_restapi_template_package
A template for NodeJS ExpressJS projects to implement GraphQL and REST API endpoints 

Working GraphQL queries via graphiql:

{
  hello {
    text
    counter
  }
}

mutation {
  createUser(userInput: {email: "test@email.com", name: "testusername", password: "testpwd"}) {
    _id
  	email  
    password
  }
}

Working REST API endpoint:

/feed/posts
