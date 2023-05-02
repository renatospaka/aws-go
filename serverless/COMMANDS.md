## Serverless
npm install -g serverless </br>
serverless create --template aws-go-mod </br>
chmod +x gomod.sh </br>
chmod +x Makefile </br>
</br>
serverless deploy </br>

## AWS
export AWS_PROFILE=<profile> </br>

### DynamoDB
aws dynamodb describe-table --table-name ProductsVideo --query 'Table.TableArn' </br>
