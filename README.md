# AWS IAM & S3 – User Permission Setup

## Objective
Demonstrate understanding of AWS Identity and Access Management (IAM) by creating and configuring a user with service-level permissions limited to Amazon S3.

---

## Task Summary
- Created an IAM user named **`test-user`**
- Granted **Amazon S3-only access**
- Ensured the user cannot access any other AWS service
- Configured console login with a **temporary password**

---

## User Login Details
**AWS IAM Login Link:**  
[https://717279734170.signin.aws.amazon.com/console](https://717279734170.signin.aws.amazon.com/console)

**Username:**  
`test-user`

**Password (temporary):**  
`Test@12345`

---
## Expected Output Verification
- `test-user` can successfully sign in via the IAM login link
- `test-user` can view, create, and upload objects in S3 buckets
- Access to all other AWS services (e.g., EC2, Lambda, DynamoDB) is restricted
