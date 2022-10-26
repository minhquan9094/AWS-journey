# AWS Lab

### Resource
https://beginaws.awsstudygroup.com/2-vpc-setup/1-create-vpc/5-build-simple-lab/


### Lab Rule:

- Naming method for AWS resource: **lab_{resource}_name**

  Ex: 
    lab_vpc_quandm
    
    lab_ec2_01_quandm
    
    lab_ec2_02_quandm
    
    lab_sub_01_quandm
    
    .....
    
- Tagging resource:


  env: lab
  
- Using free tier or minimum resource specs

https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all

- VPC Classless inter-domain routing block using range: 10.0.0.0/8
  Ex: 
    vpc_user1: 10.1.0.0/16
    vpc_user2: 10.2.0.0/16
    .....
    
    
    
   
