## Building Custom image for Apache Web Server Using Packer 

Goal: The purpose of this image is to install Apache Web Server on top of Amazon Linux 2

### Using Variables on the fly, Run the packer build command with -var

Building Packer Image
- `packer build -var "aws_access_key=xxxxx" -var "aws_secret_key=xxxxx" httpd.json`
