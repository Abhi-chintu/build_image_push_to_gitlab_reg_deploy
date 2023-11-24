# build_image_push_to_gitlab_reg_deploy

**Here we are deploying the application on EC2 instance in AWS, We use 2 instances for Gitlab Runner and Deployment**

Pre-requisite 

- EC2 Instance
- Self maanaged Gitlab runner, running on EC2 instance

# How to Configure gitlab runner

<a href="https://github.com/Abhi-chintu/gitlab-high-level/blob/master/Gitlab%20Overview/README.md">Setup self-managed gitlab-runner</a>

# We need to setup the private key as variable (type:file) 

- Goto project setting --> CI/CD --> Variables. 
- Select type as file --> key = SSH_PRIVATE_KEY --> Value = paste the key



