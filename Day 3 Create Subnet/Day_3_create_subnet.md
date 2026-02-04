# Day 03 – Creat Subnet

## 🔍 Objective
Create a subnet in the default VPC and understand how CIDR blocks and availability zones are used in AWS networking.

Examplaile:
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

![Day 3 Create Subnet](Day 3 Create Subnet/Answer step 1.png)


(Attach screenshots here or mention filenames)

---

## ✅ Outcome / What I Learned
- How to create subnet under VPC  
- How to assign CIDR block for subnet without overlapping 
  

---

## 🧠 Key Takeaways
- A VPC (Virtual Private Cloud) provides a logically isolated network in AWS where cloud resources can be securely deployed
- A subnet is a smaller network segment within a VPC that allows resources to be organized by availability zone and network purpose
- CIDR blocks define the IP address range of both VPCs and subnets and must not overlap
