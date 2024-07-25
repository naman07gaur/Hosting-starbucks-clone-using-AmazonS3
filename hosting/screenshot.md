# Pre-requisite

1. AWS account
2. Webpage to be hosted


## Step-1: Create a bucket

**Open your aws console and go to s3 dashbord**

### 1. click on create bucket

![Screenshot (51)](https://github.com/user-attachments/assets/5314653b-4951-4851-b585-035fb67cb486)

### 2. Enter bucket name
![Screenshot (52)](https://github.com/user-attachments/assets/081a6ed7-e5f3-4b8f-bf15-f6f7ae3b24ad)

### 3. Click on create bucket at bottom-right
![Screenshot (53)](https://github.com/user-attachments/assets/5e8b2f8b-d338-411a-a965-5f9d4c4b261d)

### 4. Now u can see ur bucket in dashboard


## Step-2 Upload webpage files to bucket

**To upload files**

### 1. Click on the bucket
![Screenshot (54)](https://github.com/user-attachments/assets/27edda90-55de-4f0d-9d5d-2b8431539225)

### 2. click on upload at top-right
![Screenshot (55)](https://github.com/user-attachments/assets/e811d3d6-26a9-4190-9edb-3ca4dbbec59a)

### 3. click on add files
![Screenshot (56)](https://github.com/user-attachments/assets/789b6508-5ff0-4111-ace3-74b9c6909a99)

### 4. select the webpage HTML page and other files from local system and click on upload at bottom-right
![Screenshot (67)](https://github.com/user-attachments/assets/3a2ebfa2-3939-4679-9576-2b356b80df2e)

### 5. Now u can see all ur files in ur bucket
![Screenshot (57)](https://github.com/user-attachments/assets/da5f6ea3-a4b2-4ff2-ad26-848c66dbb0bd)


## Step-3: Enabling public access and writing policiy

**to unblock public access**

### 1. open bucket and click on permissions and then click on edit bucket settings
![Screenshot (62)](https://github.com/user-attachments/assets/3e5f0068-2c91-45ce-abfd-2d2f298292ce)

### 2. Uncheck the button and click on save changes
![Screenshot (68)](https://github.com/user-attachments/assets/b6857b1f-f32c-4d17-b895-5884afa314e8)

### 3. In permissions go to bucket policy and click on edit
![Screenshot (69)](https://github.com/user-attachments/assets/2ed3254f-e1fb-41f1-ac8a-87b526bc4d00)

### 4. Copy the policy from policy.json and paste there and save changes
![Screenshot (70)](https://github.com/user-attachments/assets/7aceaffc-449d-4b4d-a6a6-478a4091ae27)

## step-4: Enabling static hosting

### 1. Open bucket and click on properties
![Screenshot (71)](https://github.com/user-attachments/assets/e8ceb6b8-3f51-478f-b6a6-8849a58a6594)

### 2. At the bottom click on edit at static website hosting
![Screenshot (72)](https://github.com/user-attachments/assets/48e250f8-b1d4-482d-8f2a-ccc0a3542139)

### 3. Click on enable
![Screenshot (59)](https://github.com/user-attachments/assets/de6cb12a-1fae-4fa6-9f0b-e729fd54a8d6)

### 4. Configure index.html
      (enter name of webpage)
![Screenshot (60)](https://github.com/user-attachments/assets/c3c95029-eaa9-43a8-8f65-1c88186caa5f)

### 5. click on save changes at bottom right
![Screenshot (61)](https://github.com/user-attachments/assets/7d11fcbd-127a-437e-94ee-52c15a7b3c89)

### 6. Now u can see DNS generated at static hosting
![Screenshot (66)](https://github.com/user-attachments/assets/d2df6d09-74f0-403f-b685-5dbe55d7fed3)

## Step-5: Testing the DNS

## 1. Open the link in diffrent browser
![Screenshot (66)](https://github.com/user-attachments/assets/d2df6d09-74f0-403f-b685-5dbe55d7fed3)

## 2. Now u can see the landing page of website
![Screenshot (73)](https://github.com/user-attachments/assets/151d1382-6080-4d76-a7e1-9b0b4cd4db5d)




