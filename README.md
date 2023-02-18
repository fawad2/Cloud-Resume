# Cloud-Resume-AWS
I will host a static website on Amazon s3 and access it via Route 53 and cloudfront



What is route 53?
Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service.

What is ACM?
Use AWS Certi(ACM)ficate Manager (ACM) to provision, manage, and deploy public and private SSL/TLS certificates for use with AWS services

What is Cloudfront?
Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content


Site is Live: Fawad.cloud Subdomain: resume.fawad.cloud

Story: 

![image](https://user-images.githubusercontent.com/51129966/218310264-a428486c-ecb5-465f-97a3-adf11e09e07d.png)


I have purchased a domain from namecheap, after that I opened rout53 and created a hosted zone and copy the dns and paste it into namecheap dns
and then I have created a bucket in which i uploaded my files and block the public access and used cloud front distribution and created a bucket policy and use some option like created oic and redirect http to https:
and created the distribution and then i opened the s3 bucket and put a record for my domain as an alias to my cloudfront distrubiton link


and it worked.
I forgot to mention Created and SSL certificate and selected on cloudfront distribution settings.
![image](https://user-images.githubusercontent.com/51129966/218310287-186d0ab9-2f21-4254-a676-15ad7a8a5bb5.png)


Thank you all for reading.

![fawad_aws](https://user-images.githubusercontent.com/51129966/218266846-112010c3-01a2-448f-b3df-50f4c04bbdcb.jpg)


