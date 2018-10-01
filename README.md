# [AWS AppSync](https://aws.amazon.com/appsync/) Playground

learn and experiment with [AWS AppSync](https://aws.amazon.com/appsync/)

## Components

* GraphQL Schema
* Resolvers
    * resolver request/response [mapping templates](https://docs.aws.amazon.com/appsync/latest/devguide/resolver-mapping-template-reference.html)
* DataSources
    * DynamoDB, ElasticSearch, Lambda *(as of 2018-06-09)*

## Resource Types

* API
    * [AWS::AppSync::GraphQLApi](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-graphqlapi.html)
    * [createGraphqlApi](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/AppSync.html#createGraphqlApi-property)
* Schema
    * [AWS::AppSync::GraphQLSchema](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-graphqlschema.html)
    * [createType](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/AppSync.html#createType-property)
    * [startSchemaCreation](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/AppSync.html#startSchemaCreation-property)
* Resolver
    * [AWS::AppSync::Resolver](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-resolver.html)
    * [createResolver](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/AppSync.html#createResolver-property)
* DataSource
    * [AWS::AppSync::DataSource](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-datasource.html)
    * [createDataSource](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/AppSync.html#createDataSource-property)
* ApiKey
    * [AWS::AppSync::ApiKey](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-apikey.html)
    * [createApiKey](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/AppSync.html#createApiKey-property)

## Resources

* [AWS JavaScript SDK | AWS.AppSync](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/AppSync.html)
* [Build your own multi-user photo album app with React, GraphQL, and AWS Amplify](https://read.acloud.guru/build-your-own-multi-user-photo-album-app-with-react-graphql-and-aws-amplify-18d9cfe27f60)
* [gabehollombe-aws/react-graphql-amplify-blog-post](https://github.com/gabehollombe-aws/react-graphql-amplify-blog-post)
* [serverless-appsync-plugin](https://github.com/sid88in/serverless-appsync-plugin)
    * [example service](https://github.com/sid88in/serverless-appsync-plugin/tree/master/example)