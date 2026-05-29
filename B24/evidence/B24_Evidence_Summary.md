# B24 – Evidence Summary

## Evidence 1 – Creating User Accounts

Multiple user accounts were created within a Linux environment to simulate different organizational roles. These accounts represented various staff members with different levels of responsibility, including managers, counsellors, administrators, and system owners.

The user accounts formed the foundation of the access control model by providing unique identities that could be assigned specific permissions.

**Associated Evidence:**
- users.png

---

## Evidence 2 – Protected Resource Structure

A directory structure was created to represent organizational resources and client records. Protected resources included multiple client directories, audit logs, and system files.

The resources were organized to allow access permissions to be applied at the directory level, supporting controlled access to sensitive information.

**Associated Evidence:**
- ls-al.png

---

## Evidence 3 – Access Control List (ACL) Implementation

Linux Access Control Lists (ACLs) were used to implement fine-grained access control. ACL entries were configured to assign permissions to individual users based on their role and responsibilities.

For example:

- The owner retained full access permissions.
- The manager was granted full access.
- The senior counsellor was granted full access.
- Counsellors were granted read and execute permissions where appropriate.
- Permissions were restricted according to the principle of least privilege.

This approach provided more granular control than standard Linux owner/group/other permissions.

**Associated Evidence:**
- getfacl.png

---

## Evidence 4 – Verification of Access Control Configuration

The implemented ACL configuration was verified using Linux command-line tools. The `getfacl` utility was used to inspect and confirm the permissions assigned to protected resources.

Verification demonstrated that permissions had been successfully applied and that access rights matched the intended security design.

**Associated Evidence:**
- linuxcommand.png
- getfacl.png

---

## Security Benefits

The implemented access control system provided several important security benefits:

- Restricted access to authorized users only.
- Supported the principle of least privilege.
- Reduced the risk of unauthorized access to sensitive client information.
- Allowed granular permission assignment to individual users.
- Improved accountability by associating permissions with specific user accounts.

---

## Reflection

This activity demonstrated the practical implementation of access control within a Linux environment using Access Control Lists (ACLs). By creating multiple user accounts and assigning permissions based on role requirements, I was able to enforce authorization controls and protect sensitive resources. The activity reinforced the importance of access control as a core cybersecurity principle and provided practical experience managing permissions in a real-world operating system environment.
