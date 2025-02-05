# Project1-host-a-static-website-with-Amazon-S3

I would like to demonstrate how to deploy a static website with Amazon S3 by uploading the website content in S3 bucket.

Let me explain about Amazon S3 and benefits of using S3 bucket.

What is Amazon S3 ?

Amazon Simple Storage Service (Amazon S3) is an object storage service. It offers data availability, security, and performance. It can be used to store or retirve any amount of data such as documents, images and videos etc. S3 bucket is a resource in Amazon s3. It is a container where we can upload files and folders.

Benefits of using S3 bucket:

1.Each object can contain up to 5TB of data.

2.A resource can only be accessed by the owner until permission is granted to others which makes it more secure.

3.It is cheap.

4.You can enable Multi-Factor Authentication (MFA) delete on an S3 bucket to prevent accidental deletions and unintentional data loss.

Let's get into project

Step1: Create an S3 bucket.

Sign in to the AWS Management Console and open the Amazon S3 console. From the S3 dashboard, click on Create bucket. Give the bucket a unique name, the name we choose must be globally unique.
Choose preferred region and uncheck all public access check box, accept the acknowledgement. This makes the website to host publicly. Then click to create website.


![WhatsApp Image 2025-02-05 at 4 30 27 PM](https://github.com/user-attachments/assets/8d82eff6-6272-462e-9a5b-af36009e5b12)

Step2: Upload webfiles to S3 bucket.

Upload files and images in Object tab.

![WhatsApp Image 2025-02-05 at 4 30 28 PM](https://github.com/user-attachments/assets/5154fdf8-dd8a-407f-9cd0-92fa0c18764d)

Step3: Generate bucket policy

click on the permissions tab. Scroll down to bucket policy section and generate it and add to the bucket.

![WhatsApp Image 2025-02-05 at 4 30 28 PM (1)](https://github.com/user-attachments/assets/bcf07de8-dcd6-49a8-bc93-3f0134fefd92)

Step4: Configure S3 bucket

In Properties tab, scroll down to static website hosting clict on edit and enable it. Enter index.html in index document. Save changes.

![WhatsApp Image 2025-02-05 at 4 30 28 PM (2)](https://github.com/user-attachments/assets/d16cbff9-dd26-4e1a-8c4d-5c4187bacb28)

After saving it, will get the bucket endpoint to access the website. Copy the endpoint and paste in new tab to see the result.

![WhatsApp Image 2025-02-05 at 4 30 29 PM (1)](https://github.com/user-attachments/assets/2bd65d27-0949-4ec5-888a-c9a2f103b9d4)

code to create your own index.html file.

![WhatsApp Image 2025-02-05 at 4 30 30 PM](https://github.com/user-attachments/assets/ad64b929-f0b3-4d19-98cd-3dba7405a929)







