# myPortfolio

go to ```https://charan1922.github.io/myportfolio/#home ```

# Code Deploy in aws steps
1. create 2 iam roles , 1 to have access for code deploy to perform operations on ec2 and 2nd to have access for ec2 on s3, code deploy
2. Install code deploy agent in ec2 machine u want to deploy
3. create code pipeline with source git hub data and code deploy
4. Make sure the shell scripts should be created or edited from visual studio not directly on git
6. Code will run on apache server

# Docker images
1. create a docker build , here nginx is created
2. create a custom image which shares the directory files to docker container
3. run docker build -t name .
4. run the container docker run -d --name contname -p 80:80 name
5. open up the ports in aws ec2
