\# Static Website Hosting using Amazon S3 and CloudFront



\## Overview



Deployed a static website using Amazon S3 and distributed it globally using Amazon CloudFront.



\## AWS Services Used



\- Amazon S3

\- Amazon CloudFront



\## Architecture



User

&#x20;  |

&#x20;  v

CloudFront

&#x20;  |

&#x20;  v

Amazon S3

&#x20;  |

&#x20;  v

Static Website



\## Implementation



1\. Created an Amazon S3 bucket.

2\. Configured static website hosting.

3\. Configured the index document as `index.html`.

4\. Uploaded the website files to S3.

5\. Configured the S3 bucket policy for website access.

6\. Created a CloudFront distribution.

7\. Configured the S3 static website endpoint as the CloudFront origin.

8\. Configured HTTP to HTTPS redirection.

9\. Accessed the website using the CloudFront distribution domain.



\## Technologies



\- HTML

\- CSS

\- JavaScript

\- Amazon S3

\- Amazon CloudFront



\## Security



The project demonstrates CloudFront-based HTTPS delivery.



For production environments, the S3 bucket should be kept private and CloudFront Origin Access Control should be preferred.



\## Result



The static website was successfully hosted on Amazon S3 and delivered through Amazon CloudFront.



\## Learning Outcomes



\- Static website hosting on S3

\- S3 bucket configuration

\- Bucket policies

\- CloudFront distribution

\- CDN-based content delivery

\- HTTPS redirection

