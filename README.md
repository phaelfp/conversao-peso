# Project Conversão Peso

## Build Image of project

docker image build . --tag rfpereira/conversaopeso:v1

## Run Project

docker run -dp 8080:80 --rm --name conversaopeso rfpereira/conversaopeso:v1
