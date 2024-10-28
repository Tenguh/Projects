# project
Creating an Amazon Linux 2 VM instance and call it "Jenkins"
instance type:t2-large
security group(open) port 22 to 0.0.0.0,8080,9100
keypair: select or create a new key pair
attach jenkins server with IAM role having "adminstrator access"
user data : use the following userdata
launch instance
after lauching the server attach a tag as key=Application and value=jenkins
