# Github Repo for [Serverless DERN TODO App]()  

This is the source code repo for the completed setup of [Fully Serverless DERN Stack TODO App Pt. 1](https://dev.to/adamkatora/fully-serverless-dern-stack-todo-app-pt-1-dynamodb-express-react-node-3dlc).

Setup:  
* Make sure you have Claudia.js installed globally on your machine
```bash
npm install -g claudia
```

* Use Claudia Create to provision the neccessary resources in AWS us-east-1
    * You'll also need valid [AWS credentials configured](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html) in order for the AWS deployment to work
    * I've already generated the serverless express proxy configuration file
```bash
claudia create --handler lambda.handler --deploy-proxy-api --region us-east-1
```