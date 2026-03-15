# ST@40 Cloud Engineering Capstone Project
## Deploying a Static Web Application via AWS S3 and CloudFront

### Project Overview
This project demonstrates the deployment of a highly available and secure static web application using Amazon Web Services (AWS). By leveraging S3 for storage and CloudFront as a Content Delivery Network (CDN), the application is optimized for low latency and global reach.

### Live Links
* **CloudFront Distribution (HTTPS):** [https://d1h8855kl2q9l3.cloudfront.net/](https://d1h8855kl2q9l3.cloudfront.net/)
* **S3 Static Website Endpoint:** [http://st40-capstone-project-ghali.s3-website.eu-north-1.amazonaws.com/](http://st40-capstone-project-ghali.s3-website.eu-north-1.amazonaws.com/)
* **AWS Console S3 Bucket:** [View Bucket Resources](https://eu-north-1.console.aws.amazon.com/s3/buckets/st40-capstone-project-ghali?region=eu-north-1&tab=objects)

### Implementation Steps
1. **S3 Bucket Configuration**: Created a unique S3 bucket with public access enabled for static hosting.
2. **Security & Permissions**: Implemented a Bucket Policy to allow `s3:GetObject` API calls, ensuring the content is accessible via the web.
3. **Static Website Hosting**: Configured bucket properties to serve `index.html` as the entry point.
4. **Content Delivery**: Provisioned an Amazon CloudFront distribution to serve the application via a global DNS endpoint for improved performance and HTTPS security.

### Project Deliverables
The following screenshots can be found in the `/images` directory:
* **S3 Deployment**: Successful rendering of the site via the S3 endpoint.
* **CloudFront Deployment**: Successful rendering via the CloudFront DNS.
* **Resource Verification**: Screenshot of the file structure within the S3 bucket.

---
**Author:** Ghali Sani Muhammad  
**Program:** ST@40 In-Demand Digital Skills Programme (Schull.io)
