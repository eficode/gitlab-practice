# Eficode Technical Task

---

This task involves deploying infrastructure using automation tools, updating system software, and configuring access for end users. The focus is on automating the process, documenting your work, and adhering to best practices. This should be considered as a production environment, so ensure all configurations and implementations are robust and secure.

## Prerequisites

To complete this task, you should be proficient in the following areas:

- **Git and GitLab**: Knowledge of Git is essential for forking repositories, creating branches, and submitting pull requests. Familiarity with GitLab is required for configuring and updating the instance.

- **SSH Key Management**: You should know how to generate an SSH key pair and understand the roles of the public and private keys.

- **Infrastructure as Code (IaC)**: Basic knowledge of IaC tools like Terraform or Ansible is needed to understand and manage infrastructure configuration.

- **System Administration**: Experience with Linux system administration, including connecting to remote servers using SSH, performing system updates, and software installation, is required.

- **Load Balancing**: Understanding load balancing concepts and tools is necessary to configure user access.

- **Security Best Practices**: Adherence to security best practices is critical, especially when working with SSH, sensitive data, and infrastructure management.

## Task Overview

### SSH Key Submission

Submit your SSH public key via [eficrypto](https://eficrypto.eficode.com) to your contact person.

### Connectivity

The infrastructure includes two servers: Nginx and GitLab. The Nginx server has a public IP address, while the GitLab server does not. Both servers will accept the submitted SSH Key for management.

### Software Updates

1. Update the Nginx server from Ubuntu 20 to Ubuntu 22.
2. Update the GitLab server to v17.0.2.

### GitLab SSH Cloning

Configure the infrastructure to allow end users to clone Git repositories using SSH.

### GitLab Runner Configuration

Enable a GitLab runner on the appropriate machine. Add a job to build a container and store it in the GitLab Container Registry.

### GitLab Pages Configuration

Enable GitLab Pages on the appropriate machine. Add a job to build a static website and store it in GitLab Pages.

### DNS

You will be given the necessary domain entries at the beginning of the task.

### Documentation

- Create a network and logical architecture diagram of the system you built.
- Document the process thoroughly.
- Automate the tasks to an appropriate level.

### Evaluation Criteria

- **Automation**: Utilize automation tools wherever possible to ensure consistency and repeatability.
- **Documentation**: Provide clear and comprehensive documentation for all steps, configurations, and processes. This includes commenting on code and scripts used for automation.
- **Security**: Adhere to security best practices throughout the task, particularly concerning SSH and sensitive data handling.
- **Completeness**: Ensure that all required steps of the assignment are fully completed.

### Additional Information

Keep in mind that this assignment is designed to evaluate your suitability for a role as a DevOps Expert at Eficode. Your solution should be easy to understand and reusable. Avoid over-engineering; often, the simplest solution is the best.

### Helpful Links

- [Nginx Documentation](https://nginx.org/en/docs/)
- [GitLab Documentation](https://docs.gitlab.com/)
- [Ansible Documentation](https://docs.ansible.com/)
- [Terraform Documentation](https://www.terraform.io/docs/)

## Support

If you encounter any issues or have questions, please reach out to the designated support contact for this task.