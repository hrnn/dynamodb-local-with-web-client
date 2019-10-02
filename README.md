The official local DynamoDB with a local web client

The web client is [yamitzky/dynamodb-admin](https://github.com/yamitzky/dynamodb-admin)

## Run it

    docker-compose up
   
Visit `http://localhost:8001`

## Using it alongside AWS SAM CLI

Read [Connecting to docker network
](https://github.com/awslabs/aws-sam-cli/blob/develop/docs/usage.rst#connecting-to-docker-network) but basically pass `--docker-network dynamodblocalwithwebclient_net`


Works on aws cloud9 as well, I just had to change the forwarder port from 8001 to 8080
