The official local DynamoDB with a local web client

## Run it

    docker-compose up
   
Visit `http://localhost:8001`

## Using it alongside AWS SAM CLI

Read [Connecting to docker network
](https://github.com/awslabs/aws-sam-cli/blob/develop/docs/usage.rst#connecting-to-docker-network) but basically pass `--docker-network net`
