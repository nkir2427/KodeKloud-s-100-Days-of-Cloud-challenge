# Day 4 - Enable Versioning for S3 Bucket

## 🔍 Objective
Enabling Versioning in S3 bucket to ensure data protection and recovery 

Goal:
The goal of this task is to understand about Versioning in S3 bucket to recover data which can be accidently deleted or corruption to ensure the data availability

---

## 🛠️ Services / Tools Used
- AWS S3
- AWS Management Console

---

## 📋 Steps Performed
1. loged into AWS management console using temporary user name and password privided in challenge task  
2. Direct to S3 bucket and select the S3 bucket which is going to add versioning
3.Click on Properties tab and edit bucket versioning and update the changes 
4.  Finished the excercise 

---

## 📸 Evidence / Artifacts
- Console screenshots
       - Direct to S3 page
    <p>
    <img src="Answer%20step%201.png" width="600">
    </p>
      - Select the S3 bucket going to versioning
    <p>
    <img src="Answer%20step%202.png" width="600">
    </p>    
    - Update as enabling the versioning
    <p>
    <img src="Answer%20step%205.png" width="600">
    </p>
    - Results after Versioning
    <p>
    <img src="Answer%20step%206.png" width="600">
    </p>
  
---

## ✅ Outcome / What I Learned
- How to Enable versioning  to existing S3 bucket which missed the versioning
  

---

## 🧠 Key Takeaways


- 🪣 AWS S3

	- AWS S3 is a scalable, durable object storage service

	- Data is stored as objects inside buckets

	- Used for data lakes, backups, ML datasets, logs, and static files

	- You pay only for storage and usage

	- Designed for high availability and durability

-🔁 S3 Versioning

  - Versioning keeps multiple versions of the same object

	- Prevents accidental overwrite or deletion

	- eleting an object creates a delete marker, not a permanent delete

	- Older versions remain stored and incur cost

	- Enabled per bucket, not per object
