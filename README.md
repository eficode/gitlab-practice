# Eficode Technical Task

---

This task involves the deployment of infrastructure using automation tools, updating system software, and configuring access for end users.

## Prerequisites

This task is aimed to test skills and knowledge on the following topics:

- **Git and Gitlab**: You should be familiar with Git for forking the repository, creating branches, and submitting pull requests. Knowledge of Gitlab is also required for configuring and updating the instance.

- **SSH Key Management**: You should understand how to generate an SSH key pair, including the public and private keys.

- **Infrastructure as Code (IaC)**: Basic knowledge of Infrastructure as Code tools such as Terraform or Ansible is required. You should be able to understand and manage the infrastructure configuration.

- **System Administration**: You should have experience with Linux system administration, including connecting to remote servers using SSH, performing system updates, and software installation.

- **Load Balancing**: Familiarity with load balancing concepts and tools are necessary to configure the access for end users.

- **Security Best Practices**: Adherence to security best practices is critical, especially when working with SSH, sensitive data, and infrastructure management.

## Task Overview

---

### SSH Key Submission

Submit your SSH public key via [eficrypto](https://eficrypto.eficode.com) to your contact person.

### Connectivity

The infrastructure includes two servers: Nginx and GitLab.
The Nginx server has a public IP address, while the GitLab server does not. SSH Access for both machines are opened and will accept the submitted SSH Key for managing them.

### Software Updates

Update the Ubuntu 20 server (Nginx) to Ubuntu 22.
Update the GitLab server from version 15.11 to 16.

### GitLab SSH Cloning

Configure the infrastructure to allow end users to clone Git repositories using SSH.

### Gitlab runner configuration

Enable a Gitlab runner to the instance and configure it to run on appropriate machine. Add a job that will build a container and store it into Gitlab Container Registry. 

### Gitlab Pages configuration

Enable a Gitlab Pages to the instance and configure it to run on appropriate machine. Add a job that will build a static website and store it into Gitlab Pages. Add a custom domain support to Gitlab and if you don't own a DNS send a examiner a request for DNS configuration and we will add a CNAME based on your request.

### Documentation

Draw an networking and logical architecture of the system you built. Document the process and automate the maintenance to proper level. 


### Helpful links

https://nginx.org/en/docs/
https://docs.gitlab.com/

---

## Support

If you encounter any issues or have questions, please reach out to the designated support contact for this task.