# Configuring a static website on Amazon 

## Steps to follow

Step 1: Create a bucket
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

1. Sign in to the AWS Management Console and open the Amazon S3 console at https://console.aws.amazon.com/s3/.

2. In the Buckets list, choose the name of the bucket that you want to enable static website hosting for.

3. Choose Properties.

4. Under Static website hosting, choose Edit.

5. Choose Use this bucket to host a website.

6. Under Static website hosting, choose Enable.

7. In Index document, enter the file name of the index document, typically index.html.

8. To provide your own custom error document for 4XX class errors, in Error document, enter the custom error document file name.

9. Choose Save changes.

10. Under Static website hosting, note the Endpoint.
