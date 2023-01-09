■Set-Up
1. Create S3 for tfstate
ex)example-dev-alb-accesslog-bucket

2. Generate public and private key

■Resources
EC2(web) x 2
EC2(db) x1
ALb x 1(HTTP & HTTPS Listener)
Route53
ACM

■Deploy
1. Move dev directory
2. terraform init
3. terraform plan
4. terraform apply