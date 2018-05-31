## a simple app using couchbase server's travel-sample database for learning ws_next tools
### setup server
1. `cd ./src/server`
1. run `yarn`
1. [setup couchbase server via docker](https://hub.docker.com/r/couchbase/server/)
   1. currently using the server sample database __travel-sample__
1. `npm run startserver`
### setup client
1. run `yarn`
1. `node ./fuse.js`
### tools/frameworks this app uses:
<!-- 1. gRPC -->
<!-- 1. ksql -->
1. graphql
1. rewire
1. couchdb
<!-- 1. kafka - _librdkafka_? -->
<!-- 1. kubernetes -->
<!-- 1. elasticsearch? -->
### todo:
* running client/server from one script?