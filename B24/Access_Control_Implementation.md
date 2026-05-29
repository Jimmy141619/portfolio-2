# B24 – Design and Implement Access Control

## Introduction

Access control is a fundamental cybersecurity principle that ensures only authorized users can access specific resources. Proper access control helps protect sensitive information from unauthorized disclosure, modification, or destruction.

This activity involved designing and implementing access control within a Linux environment using Access Control Lists (ACLs).

---

# Objective

The objective of this activity was to implement a practical access control solution that restricts access to resources based on user permissions.

---

# Access Control Method

The access control mechanism selected for this activity was Linux Access Control Lists (ACLs).

ACLs provide more granular control than traditional Linux file permissions by allowing permissions to be assigned to specific users and groups in addition to the standard owner, group, and other permission model.

---

# Design

The access control design followed the principle of least privilege.

The design included:

* Resource owners receiving full access permissions.
* Authorized users receiving only the permissions required to perform their tasks.
* Unauthorized users being denied access to protected resources.
* Access restrictions being enforced through ACL entries.

This approach minimizes unnecessary privileges and reduces security risks.

---

# Implementation

The implementation was performed within a Linux environment.

Access Control Lists (ACLs) were configured to assign permissions to specific users and resources. The configuration was verified using Linux ACL management tools.

The implementation process included:

1. Creating or identifying protected resources.
2. Assigning ownership and access permissions.
3. Configuring ACL entries for authorized users.
4. Verifying permissions using ACL inspection commands.
5. Confirming that access restrictions were correctly enforced.

---

# Security Benefits

The implemented access control solution provides several security benefits:

* Restricts access to authorized users only.
* Supports the principle of least privilege.
* Provides granular permission management.
* Reduces the risk of unauthorized access.
* Improves protection of sensitive resources.

---

# Outcome

The access control solution was successfully implemented using Linux Access Control Lists. Permissions were assigned and verified to ensure that only authorized users could access protected resources.

The implementation demonstrated how access control mechanisms can be used to secure resources within a real-world operating system environment.

---

# Reflection

This activity reinforced the importance of access control as a core cybersecurity principle. Implementing ACLs provided practical experience with permission management and demonstrated how operating system security features can be used to protect sensitive information and enforce authorization requirements.
