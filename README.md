# Projeto conversão de peso

### Sobre o projeto
O projeto conversão de peso é um projeto desenvolvido em C# com .NET Core 5.0. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando .NET.

### Observações do projeto
A aplicação é exposta usando a porta 80 

### Observação do build
Executar o docker build para geração da imagem, e então alterar na pasta k8s/deployment.yaml

### Observação do inicio do cluster
Executar kubectl apply -f k8s/

# Project temperature converter

### About the project
The project temperature weight is a project developed in C# with .NET CORE 5.0. The project goal is to be a example to environment creation with containers using .NET.

### Project observation
The application runs using PORT 80

### Build Observation
Execute docker build to generate the image, then changes the image name in the file deployment.yaml in k8s folder

### Cluster initialize Observation
Execute kubectl apply -f k8s/