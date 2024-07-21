# Setting up the Demo project

The backend is written in AWS CDK and the frontend is in React 

# Setting up Backend
To deploy backed into your aws account from your local machine, use aws cli credentials 

Use following command to setup the aws credentials using aws cli 
### `aws configure`
Input your aws_access_key_id and aws_secret_access_key 

Make sure that you have aws-cdk installed or install aws-cdk V2 using following command
### `npm install -g aws-cdk`

Use the following command to deploy the resources
### `cdk deploy`

# Setting up Frontend
The frontend is not deployed in any server, you have to run it in your local

# Set up the API GateWay Endpoints
once backend is deployed, you will have the api endpoints for getpresignedURl and  storeFileynamodb APIs. save these api endpoints in your .env file
### `REACT_APP_API_GATEWAY_GET_PRESIGNED_URL=https://example.com/getPresignedUrl`
### `REACT_APP_API_GATEWAY_SAVE_TO_DYNAMODB=https://example.com/saveToDynamoDB`

Make sure that you have react installed and use the following command to run frontend in localhost 
### `npm start`




"# temp" 
