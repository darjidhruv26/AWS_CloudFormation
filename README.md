# AWS_CloudFormation

![download](https://github.com/darjidhruv26/AWS_CloudFormation/assets/90086813/3ba42d31-d93d-455a-9c3f-72df17c717aa)

![images](https://github.com/darjidhruv26/AWS_CloudFormation/assets/90086813/cfb1c082-f544-456a-9df3-43ad573a6fcf)

- AWS CloudFormation is a service that allows you to define and provision your infrastructure resources in a declarative manner. It enables you to create a template that describes the desired state of your infrastructure, including virtual machines, storage volumes, network configurations, security groups, and more.

- AWS CloudFormation is a service that gives developers and businesses an easy way to create a collection of related AWS and third-party resources, and provision and manage them in an orderly and predictable fashion.
  
- With CloudFormation, you can create, update, and delete a collection of resources as a single unit, called a stack. The template, written in JSON or YAML format, defines the properties and dependencies of the resources, as well as any custom configurations or scripts required for deployment.

- By using CloudFormation, you can automate the provisioning and management of your AWS infrastructure, making it easier to maintain consistency and reproducibility across different environments. It provides a simple way to version control your infrastructure as code, allowing you to track changes and rollbacks efficiently.

- CloudFormation also offers capabilities such as parameterization, allowing you to customize your stack based on different environments or use cases. Additionally, it supports the use of intrinsic functions, conditions, and mappings, enabling you to define dynamic and conditional behavior within your templates.

- Overall, AWS CloudFormation simplifies the process of deploying and managing AWS resources, providing a scalable and efficient solution for infrastructure as code.

'''
aws cloudformation create-stack --capabilities CAPABILITY_IAM --stack-name ecs-core-infrastructure --template-body file://./cloud-infrastructure-setup.yaml
'''

'''
aws cloudformation create-stack --stack-name ecs-type-ec2 --capabilities CAPABILITY_IAM --template-body file://./ecs-ec2-cft.yaml
'''
