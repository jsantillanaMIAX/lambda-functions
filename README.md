# lambda-functions
Lambda functions use with dockers

Para s3

docker build -t s3_lambda -f dockerfiles/s3_lambda/Dockerfile .


aws ecr get-login-password --region eu-west-1 | docker login --username AWS --password-stdin 339712804222.dkr.ecr.eu-west-1.amazonaws.com