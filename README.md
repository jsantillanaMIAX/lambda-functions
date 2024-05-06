# lambda-functions
Lambda functions use with dockers

Para s3

docker build -t s3_lambda -f dockerfiles/s3lambda/dockerfile .
docker tag s3_lambda:latest 339712804222.dkr.ecr.eu-west-1.amazonaws.com/s3_lambda:latest
docker push 339712804222.dkr.ecr.eu-west-1.amazonaws.com/s3_lambda:latest