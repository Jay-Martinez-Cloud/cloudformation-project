# cloudformation-project
aws project using cloudformation
check out cf.yaml 
(cloudformation code to create VPC, Subnets, Internet Gatway, IGW attachment, Route Tables, Routes, Routes Assoc, Security Group, DB subnet group, Db instance, & EC2 instance)
Use AWS CLI to create AWS cloudformation stack 
(aws cloudformation create-stack --stack-name name-of-stack --template-body file://pathOfYamlFile)
Once cloudformation stack is created, ssh into your EC2.
ssh - i /path/to/your-key.pem ec2-user@your-ec2-public-ip
sudo yum update -y   (install latest updated)
sudo yum install -y httpd  (install apache web server)
sudo systemctl start httpd  (start apache service)
sudo systemctl enable httpd (apache start on boot)
sudo yum install -y php php-mysqli  (install php and mysql ext)
sudo systemctl restart httpd (apache to load php module)
echo "<?php phpinfo(); ?>" | sudo tee /var/www/html/index.php  (creates php info page)
open web browser and navigate to http://your-ec2-public-ip 






