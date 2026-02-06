# Day 5 - Create GP3 Volume

## 🔍 Objective
To provision a cost-effective GP3 EBS volume, attach it to an EC2 instance, and configure it for persistent, high-performance block storage.

Goal:
The goal of this task is to understand about EBS volume

---

## 🛠️ Services / Tools Used
- AWS EBS
- AWS Management Console

---

## 📋 Steps Performed
1. loged into AWS management console using temporary user name and password privided in challenge task  
2. Direct to EC2 service and select the volume from EBC section bucket 
3.Add new volume and rename it after creating the volume 
4.  Finished the excercise 

---

## 📸 Evidence / Artifacts
- Console screenshots
       - Direct to EC2 service 
    <p>
    <img src="Answer%20step%201.png" width="600">
    </p>
      - Select the volume from EBS section
    <p>
    <img src="Answer%20step%202.png" width="600">
    </p>    
    - Create a volume
    <p>
    <img src="Answer%20step%203.png" width="600">
    </p>
    - Name the newly created EBS volume
    <p>
    <img src="Answer%20step%204.png" width="600">
    </p>
     - Completion the Task
    <p>
    <img src="Answer%20step%205.png" width="600">
    </p>    
---

## ✅ Outcome / What I Learned
- How to create a EBS volume 
  

---

## 🧠 Key Takeaways


- ☁️ AWS EBS

	-Amazon EBS is an AWS block storage service for EC2

	-Provides durable, persistent storage

	-Manages replication, snapshots, and encryption

	-Storage is Availability Zone–scoped

	-You pay for provisioned storage and performance

-💽 EBS volume

	-An EBS volume is a single virtual disk created using Amazon EBS

	-Must be attached to an EC2 instance to be used

	-Requires formatting and mounting at the OS level

	-Supports resizing and performance tuning

	-Data persists even if the EC2 instance is stopped