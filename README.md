# ST@40 Cloud Engineering Capstone Project
## Deploying a Static Web Application via AWS S3 and CloudFront

### Project Overview
This project demonstrates the deployment of a highly available and secure static web application using Amazon Web Services (AWS). By leveraging S3 for storage and CloudFront as a Content Delivery Network (CDN), the application is optimized for low latency and global reach.

### Implementation Steps
1. [cite_start]**S3 Bucket Configuration**: Created a unique S3 bucket with public access enabled for static hosting[cite: 1, 2].
2. [cite_start]**Security & Permissions**: Implemented a Bucket Policy to allow `s3:GetObject` API calls, ensuring the content is accessible via the web[cite: 2].
3. [cite_start]**Static Website Hosting**: Configured bucket properties to serve `index.html` as the entry point.
4. [cite_start]**Content Delivery**: Provisioned an Amazon CloudFront distribution to serve the application via a global DNS endpoint for improved performance and HTTPS security[cite: 5].

### Project Deliverables
[cite_start]The following screenshots can be found in the `/images` directory:
* [cite_start]**S3 Deployment**: Successful rendering of the site via the S3 endpoint.
* [cite_start]**CloudFront Deployment**: Successful rendering via the CloudFront DNS.
* [cite_start]**Resource Verification**: Screenshot of the file structure within the S3 bucket.

---
**Author:** Ghali Sani Muhammad  
**Program:** ST@40 In-Demand Digital Skills Programme (Schull.io)