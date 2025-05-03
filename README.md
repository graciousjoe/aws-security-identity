# aws-security-identity
Repository for AWS security and identity tasks
## Create an IAM user with restricted permissions and test their access.

- Created an IAM user with the username `restricted-user`.
  
- Assigned permissions to allow access to **S3** (custom policy: `S3listonlypolicy`).
  
- Tested user access by logging in as the IAM user and verifying the ability to list S3 buckets.
  
(screenchots attached)

## Set up Multi-Factor Authentication (MFA) for an IAM user.

- Enabled **MFA** for the IAM user.
  
- Used the **Authenticator app** for MFA setup.
  
- Verified MFA by logging in with the IAM user and entering the MFA code.
  
## Create and attach a custom policy to an IAM role.

- Created a custom policy `S3listonlypolicy` with read-only access to S3.
  
- Created an IAM role `restricted-user-S3role` and attempted to attach the policy.
  
## Challenges
Role creation kept failing due to conflicting role names.
i was able to create the role eventually but it said there were some errors which I coudn't exactly find.

# screenshots attached
