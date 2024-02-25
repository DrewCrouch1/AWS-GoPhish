# AWS GoPhish Phishing Simulator Deployment

## Description:
This project focuses on deploying the GoPhish Phishing Simulator on AWS, leveraging various AWS services for networking and security.

![image](https://github.com/DrewCrouch1/AWS-GoPhish/assets/158229796/10983f12-339d-47ac-b67f-075c592aaf98)

## Features:

### VPC Creation:

Established a Virtual Private Cloud (VPC) to facilitate networking requirements for the GoPhish Phishing Simulator.

![image](https://github.com/DrewCrouch1/AWS-GoPhish/assets/158229796/69b0dd64-82d6-4960-b2bf-782f42d65f02)

### Subnet Configuration:

Utilized the VPC and set up a public subnet to enhance accessibility for the GoPhish Phishing Simulator.

![image](https://github.com/DrewCrouch1/AWS-GoPhish/assets/158229796/9ac90c64-cb99-44ba-b07a-6d533e83d8f4)

### Firewall Security Group:

Implemented a firewall security group that permits incoming connections from all IPs on specific TCP ports (3636, 80, 443, and 25) to enhance security while running the simulator.

![image](https://github.com/DrewCrouch1/AWS-GoPhish/assets/158229796/e2cff264-a8a1-4005-a8ff-bdcb6a64cd7d)


### RSA Key Pair Creation:

Generated an RSA key pair specifically for this project, ensuring secure authentication and communication.

![image](https://github.com/DrewCrouch1/AWS-GoPhish/assets/158229796/435ffbba-288e-4c81-a5a7-5b79367f625a)


### Instance Initialization Verification:

Checked and confirmed the successful initialization of the AWS instance, ensuring that it is currently running as expected.

![image](https://github.com/DrewCrouch1/AWS-GoPhish/assets/158229796/f25fb67b-2f03-429a-b6f9-817db8c5092b)


### GoPhish Login:

![image](https://github.com/DrewCrouch1/AWS-GoPhish/assets/158229796/fbc31643-cca2-45cc-a0ab-959403a62d3e)


Accessed the GoPhish Phishing Simulator interface over port 3636 (Unsecured) using the administrator account, providing a seamless login experience.
This project aims to showcase the deployment of a phishing simulation tool in a secure AWS environment, emphasizing best practices in networking, security, and access control.





