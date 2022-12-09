


docker run --rm -it -v /deployment/mongo/ssl/:/etc/ssl/ -v /deployment/mongo/configuration/mongod.conf:/etc/mongo/mongod.conf --entrypoint bash mongo


Then work out where the entrypoint is, example:

which docker-entrypoint.sh (work out what the dockerfile is told to start)


