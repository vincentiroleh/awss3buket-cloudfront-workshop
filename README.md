# Workshop

The workshop is for all skill levels, attendees will learn how to build and deploy a static website to AWS S3 Bucket and configure CloudFront.

**At the end of this workshop, attendees:**
- Understand the fundamental concepts of AWS S3 Bucket and CloudFront
- Deploy a static website to AWS S3 Bucket and configure CloudFront

# Bucket Policy

Secure Bucket via IAM

```
{
"Version":"2012-10-17",
"Statement":[
 {
   "Sid":"AddPerm",
   "Effect":"Allow",
   "Principal": "*",
   "Action":["s3:GetObject"],
   "Resource":["arn:aws:s3:::your-website/*"]
 }
]
}
```



# About Me

![](/about.png)

# Resources for the workshop

- Static website:https://github.com/vincentiroleh/static_blog
- https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingBucket.html
- https://aws.amazon.com/cloudfront/
