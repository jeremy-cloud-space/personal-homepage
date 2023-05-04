# About
GitHub repository for my personal website, which will also be used to learn CI/CD with AWS. Since I do not envision myself being a hardcore front-end developer; hence, to reduce overhead Bootstrap5 is used for styling and also to make the site responsive.

This project serves two functions: 
1. Build a simple static site on AWS using CI/CD and well-architectured framework.
2. To create a portfolio page for future use.

# To do
Some outstanding things to do for this project as I go along includes the following:
1. Build the remaining of the site using scroll navigation.
2. Add a custom domain name for the website, since the current name is too unyielding.
3. Improve UX by improving my JS and CSS toolkit. 

# AWS infrastructure
The website is hosted on AWS S3 [http://git2awshomewebpage.s3-website-ap-southeast-1.amazonaws.com/], which version control is managed by Git. To integrate both, AWS CodePipeline is used. Once a code is committed to the `main` branch, it is automatically pushed to the S3 bucket. A AWS CloudFront distribution is used to serve the content of the home page.
