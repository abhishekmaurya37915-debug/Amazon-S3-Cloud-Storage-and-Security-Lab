# Amazon-S3-Cloud-Storage-and-Security-Lab

Amazon S3 Cloud Storage and Security Lab

Project Overview

This project demonstrates how to configure Amazon Simple Storage Service (Amazon S3) for secure cloud storage. It covers bucket creation, object uploads, access control, and data protection.

Objectives

- Understand Amazon S3 and object storage.
- Create and configure an S3 bucket.
- Upload and manage files.
- Understand IAM and bucket policies.
- Protect data using encryption.
- Prevent accidental public exposure of sensitive files.

Requirements

- AWS account
- Web browser
- Internet connection
- Sample test files

Lab Setup

# 1. Sign in to the AWS Management Console.

<img width="1911" height="870" alt="image" src="https://github.com/user-attachments/assets/760bbff8-a5b0-4139-b22c-8e00a0f543d5" />
<img width="1917" height="867" alt="image" src="https://github.com/user-attachments/assets/819f5e45-0f72-4113-a93a-e32139cba6c1" />

# 2. Search for Amazon S3.

<img width="1916" height="865" alt="image" src="https://github.com/user-attachments/assets/97c714ce-b40c-4e46-992c-cf9a3e5acdd2" />

After click S3
<img width="1916" height="865" alt="image" src="https://github.com/user-attachments/assets/2ff274f9-a877-41b1-9939-e7b6797c068f" />

# 3. Select Create bucket.
   
Click on Create bucket
<img width="1912" height="867" alt="image" src="https://github.com/user-attachments/assets/57faa852-19ee-4753-a54b-848c1b8bf2da" />

# 5. Enter a globally unique bucket name.

<img width="1911" height="870" alt="image" src="https://github.com/user-attachments/assets/9332bad1-1aaf-4b74-9091-8accbaad2f2f" />

# 6. Keep Block Public Access enabled.
<img width="1910" height="760" alt="image" src="https://github.com/user-attachments/assets/8c5a0c06-631b-4e99-b3e4-0a22dd665767" />

After click (I acknowledge that the current settings might result in this bucket and the objects within becoming public).

<img width="1911" height="830" alt="image" src="https://github.com/user-attachments/assets/953c0d84-163f-4e5f-8551-1cc4b1ffe416" />

# 8. Enable default encryption.

<img width="1951" height="867" alt="image" src="https://github.com/user-attachments/assets/bf980610-87b8-4277-9b83-4831f37e6f54" />

# 9. Create the bucket.

<img width="1910" height="762" alt="image" src="https://github.com/user-attachments/assets/dabe11fa-ad0e-4f99-b55b-ad017d02fb56" />
 
# 10. Open the bucket and upload a sample file.

<img width="1917" height="982" alt="image" src="https://github.com/user-attachments/assets/a4e8b7e6-aa9d-4418-9255-edb5e65f5291" />

# 11 1.step:- Search (simple index html file download) and click 1 Link.
<img width="1912" height="807" alt="image" src="https://github.com/user-attachments/assets/9baa7e5d-22f7-4549-b191-53409aa451ad" />

# 2.Step:- Click On Download 7 Zip.

<img width="1917" height="905" alt="image" src="https://github.com/user-attachments/assets/aeff2022-bc6a-4981-877a-3118237a45d9" />

# 12. (Download 7-Zip) Successfully upload the application file.

 1. click On Add file.

<img width="1917" height="822" alt="image" src="https://github.com/user-attachments/assets/508e633a-f8cb-44a6-ae2f-9b847ac19879" />

2. Select Application File add add now. 

<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/afbf9cdc-beac-4142-bb74-601073461d90" />

3. After Click On upload.
<img width="1915" height="851" alt="image" src="https://github.com/user-attachments/assets/c6c92ff8-b938-4cba-adf0-886c6cd47621" />
<img width="1906" height="827" alt="image" src="https://github.com/user-attachments/assets/4cca6eba-869f-40df-9ce8-de7dad0fc43a" />

4. After On Index.html and open it.

<img width="1906" height="827" alt="image" src="https://github.com/user-attachments/assets/300d2dec-6329-4497-b047-2f67fe95a315" />

5. And Click on open and look uploaded file.

<img width="1916" height="857" alt="image" src="https://github.com/user-attachments/assets/d60c9eb3-328a-449d-b0ab-6a67a7163c8f" />
<img width="1841" height="1020" alt="image" src="https://github.com/user-attachments/assets/4980e8aa-fd54-4ae0-b311-592eeaa97abe" />

Security Best Practices

- Keep S3 buckets private unless public access is explicitly required.
- Use IAM policies and least-privilege permissions.
- Enable encryption at rest.
- Enable versioning when recovery from accidental deletion or modification is needed.
- Review bucket policies and access permissions.
- Enable logging or monitoring where appropriate.
- Never upload passwords, access keys, or confidential company data to GitHub.

Expected Result

A private S3 bucket is created, a sample file is uploaded, and the main security settings are reviewed.

Tools Used

- Amazon Web Services (AWS)
- Amazon S3
- AWS Identity and Access Management (IAM)
- AWS Management Console

Learning Outcomes

- Understanding cloud object storage
- Basic AWS cloud security
- S3 bucket configuration
- Access control and data protection

Disclaimer

This project is for educational purposes. All activities should be performed in an AWS account you own or are authorized to use.

Author

Abhishek Maurya

Cybersecurity Student | Cloud Security Enthusiast


