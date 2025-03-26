module "ec2" {
  source         = "./terraform-modules/ec2"
  ami_id         = "ami-0abcdef1234567890"  # Change this to a valid AMI ID
  instance_type  = "t2.micro"
  key_name       = "my-key-pair"
  subnet_id      = "subnet-12345678"  # Change this to your subnet
  instance_name  = "my-ec2-instance"
}
