# AWS IAM Users and Groups Documentation

## Problem Statement

XYZ Corporation requires proper user management and access control using AWS IAM.

### Requirements

Create IAM Users:

* Dev1
* Dev2
* Test1
* Test2

Create IAM Groups:

* Dev Team
* Ops Team

User Assignments:

* Dev1 → Dev Team, Ops Team
* Dev2 → Dev Team
* Test1 → Ops Team
* Test2 → Ops Team

---

# Implementation Steps

## Step 1: Create IAM Users

Created four IAM users:

* Dev1
* Dev2
* Test1
* Test2

### Notes

IAM users provide individual identities for accessing AWS resources.

---

## Step 2: Configure User Permissions

Configured user access settings during user creation.

### Notes

Permissions determine what AWS resources a user can access.

---

## Step 3: Verify User Creation

Verified successful creation of all IAM users.

### Notes

Verification helps ensure users are available for future assignments.

---

## Step 4: Create IAM Groups

Created:

* Dev Team
* Ops Team

### Notes

Groups simplify permission management by assigning permissions to groups instead of individual users.

---

## Step 5: Add Users to Groups

Assignments completed successfully.

| User  | Group              |
| ----- | ------------------ |
| Dev1  | Dev Team, Ops Team |
| Dev2  | Dev Team           |
| Test1 | Ops Team           |
| Test2 | Ops Team           |

### Notes

Group-based management improves scalability and security.

---

## Step 6: Verification

Verified:

* Users created successfully
* Groups created successfully
* Users assigned correctly

---

# Learning Outcomes

Through this project I learned:

* AWS IAM Fundamentals
* User Management
* Group Management
* Access Control
* AWS Security Best Practices

---

# Conclusion

This project demonstrates the implementation of AWS IAM user and group management. By creating users, organizing them into groups, and verifying assignments, secure and efficient access management was achieved.
