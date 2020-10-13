# aws_cli_1

1: aws ec2 create-key-pair --key-name MyKeyPair

2:  aws ec2 create-security-group --group-name MySecurityGroup --description "My security group"                                                                                                    

3:  aws ec2 run-instances  --image-id ami-0e306788ff2473ccb  --instance-type t2.micro  --count 1  --subnet-id subnet-0a49125ece097f3e3  --security-group-ids sg-06f7d2c96275975c8 --key-name MyKeyPair

4:  aws ec2 create-volume --volume-type gp2  --size 1 --availability-zone ap-south-1a                                                                                                                

5:  aws ec2 attach-volume --volume-id vol-036dda0f8f786e794  --instance-id i-0701d35a55c8ebec4 --device /dev/sdf                                                                                     
