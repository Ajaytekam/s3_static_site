# Hosted Jekyll Site on AWS S3 using GitHub Actions, Cloudfont CDN, Route53 and AWS Certificate Manager for SSL Certificate   

* Created CICD pipeline using Github Actions to host static website on S3 Bucket. 
* Website Artifcat is generated using Jykell (static site generator) and push onto S3 bucket, and CloudFront CDN is used to distribute website content, and a custom domain https://blog.aliencloud.tech is configured via Route53 service and AWS Certificate Manager for SSL Certificate.  


Notes on Invalidating files : 

https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Invalidation.html

