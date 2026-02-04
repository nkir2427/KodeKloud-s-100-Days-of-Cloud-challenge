# Day 03 – Creat Subnet

## 🔍 Objective
Create a subnet in the default VPC and understand how CIDR blocks and availability zones are used in AWS networking.

Goal:
The goal of this task is to understand AWS VPC, CIDR blocks, and subnet.

---

## 🛠️ Services / Tools Used
- AWS VPC
- AWS Management Console

---

## 📋 Steps Performed
1. loged into AWS management console using temporary user name and password privided in challenge task  
2. Direct to VPC and see what is the default VPC and subnet ip's already created under this VPC  
3. Configure new subnet with reffering new CIDR block which is not used previouly to address overlapping the CIDR 
4. Checked the Subnet created and Finished the excercise 

---

## 📸 Evidence / Artifacts
- Console screenshots
    - loging to the aws management console 
    <p>  
    <img src="Answer%20step%201.png" width="600">
    </p>
       - Direct to VPC page
    <p>
    <img src="Answer%20step%202.png" width="600">
    </p>
      - check the default vpc data
    <p>
    <img src="Answer%20step%203.png" width="600">
    </p>    
    - check the available subnet CIDR blocks 
    <p>
    <img src="Answer%20step%206.png" width="600">
    </p>
    - creating new subnet as per the task
    <p>
    <img src="Answer%20step%204.png" width="600">
    <img src="Answer%20step%207.png" width="600">
    </p>
     - Completion the Task
    <p>
    <img src="Answer%20step%208.png" width="600">
    </p>    
---

## ✅ Outcome / What I Learned
- How to create subnet under VPC  
- How to assign CIDR block for subnet without overlapping 
  

---

## 🧠 Key Takeaways
- A VPC (Virtual Private Cloud) provides a logically isolated network in AWS where cloud resources can be securely deployed
- A subnet is a smaller network segment within a VPC that allows resources to be organized by availability zone and network purpose
- CIDR blocks define the IP address range of both VPCs and subnets and must not overlap
