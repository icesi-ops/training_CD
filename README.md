# training_CD
Continuos Delivery and Deployment training

Steps:
- Launch EC2 instance with Packer
- Apply configuration management to it
- Install the demo-app RPM we produced
- Install other required packages to turn it into a web server
- Test the applied configuration (using Serverspec)
- Produce an AMI out of the configured instance (using Packer)
- Launch an EC2 instance from the produced AMI
- Run additional tests against the new EC2 instance
