# aws_lambda_websocket

#https://aws.amazon.com/blogs/compute/announcing-websocket-apis-in-amazon-api-gateway/


# SAM APPLICATION 
https://serverlessrepo.aws.amazon.com/applications/arn:aws:serverlessrepo:us-east-1:729047367331:applications~simple-websockets-chat-app



# GIT REPO
https://github.com/aws-samples/simple-websockets-chat-app

# UI LOGGER
WebSocket URL: wss://iwl4ls14zi.execute-api.ap-south-1.amazonaws.com/dev
Connection URL: https://iwl4ls14zi.execute-api.ap-south-1.amazonaws.com/dev/@connections

# RUN

```$ npm install -g wscat```

wscat -c wss://iwl4ls14zi.execute-api.ap-south-1.amazonaws.com/dev

```>{"action":"log", "data":"test log"}```

# FROM LOCALHOST

```npm install -g simple-https-server```
Then run simple-https-server in folder you wish to be served. Page will be hosted at https://localhost:8000 (don't forget the 's' httpS://)


