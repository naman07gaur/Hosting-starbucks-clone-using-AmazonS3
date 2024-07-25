# Configuring a static website on Amazon 

## Steps to follow

Step 1: Create a bucket\
Step 2: Enable static website hosting
Step 3: Edit Block Public Access settings
Step 4: Add a bucket policy that makes your bucket content publicly available
Step 5: Configure an index document
Step 6: Configure an error document
Step 7: Test your website endpoint
Step 8: Clean up



## Step 1: Create a bucket

### To create a bucket

1. Sign in to the AWS Management Console and open the Amazon S3 console.

2. Choose Create bucket.

3. Enter the Bucket name (for example, example.com).

4. Choose the Region where you want to create the bucket.

5. To accept the default settings and create the bucket, choose Create.


## Step 2: Enable static website hosting

### To enable static website hosting

1. Sign in to the AWS Management Console and open the Amazon S3 console.

2. In the Buckets list, choose the name of the bucket that you want to enable static website hosting for.

3. Choose Properties.

4. Under Static website hosting, choose Edit.

5. Choose Use this bucket to host a website.

6. Under Static website hosting, choose Enable.

7. In Index document, enter the file name of the index document, typically index.html.

8. To provide your own custom error document for 4XX class errors, in Error document, enter the custom error document file name.

9. Choose Save changes.

10. Under Static website hosting, note the Endpoint.


## Step 3: Edit Block Public Access settings

1. Open the Amazon S3 console.

2. Choose the name of the bucket that you have configured as a static website.

3. Choose Permissions.

4. Under Block public access (bucket settings), choose Edit.

5. Clear Block all public access, and choose Save changes.

## Step 4: Add a bucket policy that makes your bucket content publicly available

1. Under Buckets, choose the name of your bucket.

2. Choose Permissions.

3. Under Bucket Policy, choose Edit.

4. To grant public read access for your website, write the policiy in Bucket policy editor.

5. Choose Save changes.

## Step 5: Configure an index document

1. Create an index.html file.

2. Save the index file locally.

3. Sign in to the AWS Management Console and open the Amazon S3 console.

4. In the Buckets list, choose the name of the bucket that you want to use to host a static website.

5. Upload webpage(index.html) to the bucket.

       -To upload the index document to your bucket:

        Choose Upload, and follow the prompts to choose and upload the index file.

        Upload other website content to your bucket.(if any)

5. Enable static website hosting for your bucket, and enter the exact name of your index document (for example, index.html). For more information, see step 2 point 7 & 8.


## Step 6: Configure an error document

To configure the error document we follow the same step like configuring index.html.This webpage will be shown at website endpoint if it faces any issue in displaying index.html


## Step 7: Test your website endpoint

1. Under Buckets, choose the name of your bucket.

2. Choose Properties.

3. At the bottom of the page, under Static website hosting, choose your Bucket website endpoint.

   (Your index document opens in a separate browser window.)


## Step 8: Clean up

It is always a good practice to delete all the resources that we used in our AWS console after the succesfulty hosting a website in order to avoid the unnecessary bill from Amazon.
After we delete the resource the endpoint will also be deleted and our webpage will be bo longer hosted on that endpoint. 



