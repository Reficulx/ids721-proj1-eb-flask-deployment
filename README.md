# ids721-proj1-eb-flask-deployment
This repository deploys a simple flask application on AWS Elastic Beanstalk platform. 
![image]("./img/eb.png")
The working structure of the Elastic Beanstalk is shown above. The reference for this image is shown in the Reference section. 
## Implementation 
1. Install and Configure the Elastic Beanstalk Comand Line Interface (EB CLI) through [EB CLI](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install.html). 
2. After the installation and configuration is Done. Clone the repository and unzip it. Change the working directory to the unzipped file.
3. Use the following command to create EB environment, open the flask application, and terminate EB environemt after completing using the application.  
Create an environment on EB. You can determine the name. Note that this process might take a long time since EB will create a list of necessary components to do the computation, security, load balance, and etc. 
`eb create {your-env-name}`  
Open the deployed Flask Application. 
`eb open`  
Terminate the Environment. 
`eb terminate {your-env-name}`
## Reference 
1. [Image](https://dev.to/frosnerd/deploying-an-http-api-on-aws-using-elastic-beanstalk-5dh7)
