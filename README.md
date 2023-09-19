# AWS CloudFormation Template para WordPress

Este repositório contém um modelo AWS CloudFormation para implantar uma instância WordPress na AWS usando serviços como ECS, RDS, Elastic Load Balancing, entre outros.

## Descrição

O modelo cria os seguintes recursos:

- **Cluster ECS**
- **Instâncias EC2** para o cluster ECS
- **Instância RDS** para o banco de dados WordPress
- **Grupo de segurança** para ECS e EC2
- **Grupo de logs do CloudWatch** para logs de contêiner ECS
- **Balanceador de carga AWS** com um ouvinte e um grupo de destino
- (e muitos mais recursos)

## Pré-requisitos

- Uma chave EC2 existente
- Uma VPC e pelo menos duas subnets associadas à VPC
