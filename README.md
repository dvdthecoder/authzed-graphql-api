## graphql_mesh & gRPC
This repos contains configuration that is being use to generate a graphQL end point using the graphql_mesh gRPC handler. Reference of gRPC end points is https://buf.build/authzed/api

### Configuration
Before running this code 
- By cloning following repo https://github.com/dvdthecoder/authzed-docker-compose-postgres get a docker instance of authzed up and running
- Clone the graphql_mesh repo
- npm run dev 

### Open Issue
- Currently this is not generating desired results becasue of issue with parseing relevant files . An issue has been raised https://github.com/protobufjs/protobuf.js/issues/1683 to seek a response on what is causing the problem. 
