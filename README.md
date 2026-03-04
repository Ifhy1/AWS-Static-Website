Technical Architecture & Implementation
To ensure this site is secure and fast, I implemented the following AWS configuration:

Origin Access Control (OAC): Configured CloudFront to communicate with S3 using OAC, ensuring the bucket remains private and only accessible via the CDN.

Edge Caching: Leveraged AWS Global Infrastructure to cache content at edge locations, reducing latency for users regardless of their geographic location.

Security Policy: Applied a least-privilege JSON bucket policy to the S3 bucket to prevent direct public access and mitigate unauthorized data retrieval.

 How to View
Live Site: https://dlnrrz6o74scn.cloudfront.net/

AWS Console: This project was built and verified within the us-east-1 region using the AWS Management Console.
