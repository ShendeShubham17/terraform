# terraform
create instance


provider "aws"
{
    region = "us-west -1"
}

resource "aws_instance" "shubham" {
  ami           = "ami-005e54dee72cc1d00" # us-west-2
  instance_type = "t2.micro"
