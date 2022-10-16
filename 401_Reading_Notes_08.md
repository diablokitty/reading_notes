# Reading Notes for Day 8 of 401:

## 5 steps to RBAC

- What is Role Based Access Control (RBAC) and why do we care?
RBAC authorizes by role instead of building unique authorizations each time someone is added.

- Describe a Role/Permission hierarchy that you might implement using RBAC.
A client might be able to see certain things related to their own account, a client manager could see the same things related to all of the clients assigned to them.

- What approach might you take to implement RBAC?
I would map out all of the permissions needed by each role, and build profiles for those roles.


## wiki - RBAC

- If Authentication is “you are who you say you are,” what is Authorization?

You are allowed to do what you are trying to do. 

- Name three primary rules defined for RBAC.
Can view, can edit, can delete.

- Describe RBAC to a non-technical friend.
Your role is who you are in the system and that defines what you can do. Like if you're in accounting you can see accounting information, and if you're in hr you can see hr files, but accountants can't see hr info and hr people can access the balance sheets.

## Videos
## RBAC tutorial

- What Are access rights Associated with? The User? or The Role? Explain. 
The role, because there can be many people with the same role and it's more efficient to ba able to assign and unassign rights by role.


- Access Rights, or Authorization, is activated after a user successfully does what? 
Logs in or authenticates.

- Explain how RBAC might benefit a business.
It's faster and more efficient to have role assignments when multiple people might need the same access. 

### Things I want to know more about:

[back to Table of Contents](./README.md)
