🔹 What is EC2?

EC2 (Elastic Compute Cloud) is a virtual server provided by Amazon Web Services

🔹 Steps
Login AWS
Go to EC2
Click "Launch Instance"

Select:
Ubuntu
t2.micro

Create key pair

Allow ports:
22 (SSH)
80 (HTTP)
Launch


🔹 Connect
ssh -i key.pem ubuntu@<public-ip>


🔹 Real Use
Hosting apps
Running Docker/Kubernetes