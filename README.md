# packer
Using HashiCorp Packer to Automate AMI Creation in AWS
Download Packer binary and copy in /usr/bin or /usr/local/bin in PATH
Packer Download - Windows-64

Create build.json file and run the following command
build.json

  packer build build.json
  
For this example:
  packer build -var-file=variables.json apache.json
