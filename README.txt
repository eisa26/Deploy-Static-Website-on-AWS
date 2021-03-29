#Udacity Project Cloud DevOps Engineer 

#### Eisa Shaheen eisa.shaheen26@gmail.com

## Deploy Static Website on AWS

# Project Overview

	The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. The 		whole project has two major intentions to implement:
	1-Hosting a static website on S3 and
    	2-Accessing the cached website pages using CloudFront content delivery network (CDN) service.
    	3-Recall that CloudFront offers low latency and high transfer speeds during website rendering.


### Access the website via website-endpoint.
	http://my-497726212229-bucket.s3-website.us-east-2.amazonaws.com


### Access the bucket object via its S3 object URL
	http://my-497726212229-bucket.s3-website.us-east-2.amazonaws.com/index.html
	

### Access the bucket object via CloudFront domain name
	http://d3k9yp104co9zd.cloudfront.net/
