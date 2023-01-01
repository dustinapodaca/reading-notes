<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 401 Reading Notes

## Class 08 Reading Notes

### 5 Steps to RBAC

```
1. What is Role Based Access Control (RBAC) and why do we care?
   - RBAC is a method of controlling access to resources or operations based on the roles of users within an organization. It is important because it allows organizations to set fine-grained access controls based on the roles of users, rather than having to manage permissions for each user individually. This can make it easier to manage access to resources and operations, especially in large organizations with many users.
2. Describe a Role/Permission hierarchy that you might implement using RBAC.
   - One example of a Role/Permission hierarchy that could be implemented using RBAC might be:
     1. Administrative roles: These roles would have access to all resources and operations within the organization. Examples might include system administrators or top-level executives.
     2. Managerial roles: These roles would have access to a subset of resources and operations within the organization. Examples might include department managers or team leaders.
     3. User roles: These roles would have access to a limited set of resources and operations within the organization. Examples might include regular employees or contractors.
     4. Guest roles: These roles would have access to a very limited set of resources and operations within the organization, or possibly no access at all. Examples might include clients or partners.
3. What approach might you take to implement RBAC?
   - To implement RBAC, you would need to first define the roles and permissions within your organization. This might involve creating a hierarchy of roles, as described above, and defining the resources and operations that each role has access to. You would then need to set up a system for managing and enforcing these roles and permissions, such as a user management system or an access control system. This might involve creating user accounts and assigning roles to each user, as well as setting up rules and policies for granting and revoking access to resources and operations.

```

### Wiki - RBAC

```
1. If Authentication is “you are who you say you are,” what is Authorization?
  - Authorization is the process of granting or denying access to certain resources or actions based on whether the user is authorized to perform them.
2. Name three primary rules defined for RBAC.
  - 1) Role Assignment: A user is assigned to one or more roles, and the roles are granted certain permissions to access resources or perform actions. 
  - 2) Role Activation: A user's active role(s) are used to determine what resources and actions they are authorized to access or perform.
  - 3) Role Authorization: The system checks whether the user's active role(s) are authorized to access the requested resources or perform the requested actions.
3. Describe RBAC to a non-technical friend.
  - RBAC is a method of controlling access to computer systems or networks based on the roles of individual users within an organization. It works by assigning permissions to different roles, and then assigning users to one or more of those roles. This way, you can control what actions users are allowed to perform based on their role within the organization, rather than having to manage permissions for each individual user.

```

### Videos - RBAC

```
1. What Are access rights Associated with? The User? or The Role? Explain.
  - Access rights are associated with roles.
2. Access Rights, or Authorization, is activated after a user successfully does what?
  - Access rights, or authorization, is activated after a user successfully authenticates.
3. Explain how RBAC might benefit a business.
  - RBAC can help a business to better manage access to its systems and data, by allowing the organization to define roles and permissions in a flexible and granular way. This can make it easier to control who has access to what resources and actions, and can reduce the risk of unauthorized access or misuse of company resources. Additionally, using RBAC can make it easier to onboard new employees and manage access rights as employees change roles within the organization.

```
