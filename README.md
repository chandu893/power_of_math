# power_of_math
step1:Navigate to aws amplify and connect github.
step2:Create a lambda function and paste the python original file.py
deploy and test the python code in output
{
    "base":2,
    "exponent":3
}
test the python code 
step4:dynamodb create the table and copy the arn 
step5:in lambda go to configurations , go to permissions click on the iam role link and configure with lambdarole-dynamo
step6:apigateway,goto restapi in public then create an apigateway then create a post method and deploy and the apigateway and copy the invoke url and paste in index file under fetch.
then test the amplify url give some inputs, output will be stored in dynamodb.