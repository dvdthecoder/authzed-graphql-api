## graphql_mesh & gRPC
This repos contains configuration that is being use to generate a graphQL end point using the graphql_mesh gRPC handler for Authzed gRPC end-points(https://buf.build/authzed/api)

### Local Development
The definitions for generating the graphQL end-points uses *reflection* strategy , therefore we need a running instance of SpiceDB
- Clone following repo https://github.com/dvdthecoder/authzed-docker-compose-postgres get a docker instance of SpiceDB up and running
or
- Follow instructions https://github.com/authzed/spicedb 
- Clone the current repo
- Run `npm run dev` 

### Open Issue
- Currently this is not generating desired results becasue of issue with parsing relevant files . An issue has been raised https://github.com/protobufjs/protobuf.js/issues/1683 to seek a response on what is causing the problem. 

### Additional Notes
- It uses the latest release `@graphql-mesh/grpc@0.19.0-alpha-6234eb4f3.0` to resolve issues related to duplicate file dscriptors within a namespace