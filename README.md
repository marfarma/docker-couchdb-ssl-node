# CouchDB SSL with Node

Available in the docker index as marfarma/couchdb-ssl-node

The CouchDB server is configured for secure (https) access, using a self-signed certificate by default.  See [the klaemo/docker-couchdb-ssl documentation](https://github.com/klaemo/docker-couchdb-ssl) details on using your own certificate for production use.

Node version 0.12
CouchDB version 1.6.1

## Instructions

    docker run -d --restart=always -p 6984:6984 marfarma/couchdb-ssl-node
