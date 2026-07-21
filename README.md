# AWS EC2 Web Hosting Lab

## Student Details
- Name: Pranathi G N
- Branch: CSE

## College Vision
To be a premier institution in Technology and Management through excellence in education, innovation, research, incubation and ethical values.

## College Mission
- Provide quality technical education.
- Promote research and innovation.
- Encourage entrepreneurship.
- Develop socially responsible professionals.

## Department
Computer Science & Engineering

## Department Vision
To be a globally recognized center for imparting quality technical education through innovative research and incubation with moral values in the field of Computer Science and Engineering.

## Department Mission
- Impart quality technical education.
- Promote innovation and research.
- Encourage entrepreneurship.
- Develop ethical professionals.

## Cloud Association
Amazon Web Services (AWS) is a cloud computing platform that provides services such as EC2, S3, databases, networking, security, and scalable cloud infrastructure. In this lab, an EC2 instance was used to host a static HTML webpage using the Apache HTTP Server.

## Commands Used

```bash
sudo dnf install httpd -y
sudo systemctl enable --now httpd
sudo systemctl start httpd
sudo systemctl enable httpd

nano index3.html
sudo cp index3.html /var/www/html/

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/Pranathign/AWS.git
git push -u origin main
```

## Website URL

http://16.192.150.92/index3.html

## GitHub Repository

https://github.com/Pranathign/AWS
