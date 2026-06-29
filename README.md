# AWS Portfolio Website

## Overview

This project is a responsive portfolio website built using HTML and CSS.

## Features

* Hero Section
* About Me
* Skills Section
* Project Cards
* Contact Information
* Resume Download Button

## Technologies Used

* HTML5
* CSS3
* AWS S3
* AWS CloudFront
* GitHub

## Author

Amar Kalbande

## Live URL
https://d155xfhi5wqvu2.cloudfront.net
## Deployment Details
https://d155xfhi5wqvu2.cloudfront.net

### GitHub Repository

https://github.com/amark7/aws-portfolio

### AWS Services Used

* Amazon S3
* Amazon CloudFront

### Hosted Website
https://d155xfhi5wqvu2.cloudfront.net
### Steps Performed

1. Developed portfolio website using HTML and CSS.
2. Uploaded code to GitHub.
3. Created an S3 bucket and enabled static website hosting.
4. Configured bucket policy for public access.
5. Created a CloudFront distribution.
6. Enabled HTTPS and deployed the website globally.



# AWS Portfolio Website Deployment using Docker

## Overview

This project demonstrates the deployment of a static portfolio website using Docker on an AWS EC2 Ubuntu instance.

## Technologies Used

* HTML5
* CSS3
* Docker
* Nginx
* Git & GitHub
* AWS EC2 (Ubuntu)

## Project Structure

```
aws-portfolio/
├── Dockerfile
├── README.md
├── index.html
├── styles.css
├── assets/
```

## Deployment Steps

### 1. Clone Repository

```bash
git clone https://github.com/amark7/aws-portfolio.git
```

### 2. Navigate to Project

```bash
cd aws-portfolio
```

### 3. Build Docker Image

```bash
docker build -t portfolio-website .
```

### 4. Run Docker Container

```bash
docker run -d -p 80:80 --name portfolio-container portfolio-website
```

### 5. Verify Running Container

```bash
docker ps
```

### 6. Access the Website

Open the EC2 Public IP in your browser.

```
http://13.233.119.191
```

## Author

**Amar Kalbande**

GitHub: https://github.com/amark7/aws-portfolio
