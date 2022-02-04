# interview_questions

- [interview_questions](#interview_questions)
	- [Programming](#programming)
	- [Security](#security)
	- [Kubernetes](#kubernetes)
	- [Active Directory](#active-directory)
	- [Git](#git)
	- [Ansible](#ansible)
	- [Agile](#agile)

## Programming

- Programming: What is your preffered language for automation?
  - `placeholder`
- Programming: If you have a variable set equal to "11" what data type is this?
  - (string)
- Programming: What are some of the commmon data types in programming/scripting?
  - (string, int, bool, float, list, dict, tuple, etc...)
- Programming: What is a difference between a list(array) and a dict(hash table)
  - (list is indexed, dict is keyed:value)
- Programming: What is a for loop?
  - (process each item in a list/dict)
- Programming: When would you use a function?
  - (reuse a set of code)
- Programming: What is a class?
  - (object template, shares common characteristics)
- Programming: Tasked to deploy a WSUS server, based on data determine if internal or external DB should be used, what sort of logic is this.
  - (conditional/if/when)
- Programming: In pseudo code- explain the process to deploy said WSUS server.
  - `placeholder`

## Security

- Security: What is Kerberos used for?
  - `placeholder`

## Kubernetes

- k8s: when to use, when not to use
  - `placeholder`
- k8s: Benefits of k8s
  - `placeholder`
- k8s: What are some of the workload types for automating pod recreation/persistence? (deployment or statefulset or replicaset)
  - `placeholder`
- k8s: what is a deployment or statefulset
  - `placeholder`

## Active Directory

- AD: What is LDAP?
  - `placeholder`
- AD: Where would I find a global catalog server?
  - `placeholder`
- AD: If I have 100 computers and 200 users, what is the standard windows product to manage the users and computers?
  - (Active Directory):
- AD: Of my 200 users, if I want to group users for administrative or permission oriented reasons, what sort of (Active Directory) group would I use?
  - (Security Group):
- AD: What is the other common group.
  - (Distribution Group):
- AD: With the created group, what (Active Directory) feature would you use to enforce unique behavior/permissions within the domain?
  - (Group Policy):
- AD: If I want to provide administrative login to all domain computers, using group policy I've added Domain Admins. My admin account is unable to login, how do I add Domain Admin to my admin account?
  - (Active Directory Users & Computers -- Domain Admins shouldnt be on every box, and shouldn't be handed out easily):
- AD: Are there any issues with the previous question for production use?
  - (Domain Admins shouldnt be on every box, and shouldn't be handed out easily):

## Git

- Git: You have a repository online, how would you get a local copy
  - (Git clone):
- Git: You want to do your own work on the repository, what would you do next?
  - (Create a branch):
- Git: You have commited your changes, and want to send the changes to the online/remote repository, what do you do?
  - (Push):

## Ansible

- Ansible: What feature of ansible is used to store all of the target computers, groups, users, variables, etc?
  - (Inventory):
- Ansible: What is the .yml file that contains the tasks to be executed against the target.
  - (Playbook):
- Ansible: What is the ansible feature that is used when code is intended for repeat use.
  - (Role):
  - (Module):
- Ansible: What is a module?
  - `placeholder`
- Ansible: What language are modules commonly?
  - `placeholder`

## Agile

- Agile: What is a the purpose of a spike?
  - (Research/better understand): no

###

- CI/CD: Any experience with Jenkins? What is a common use-case for Jenkins?
  - (Automated Testing):

###

- Networking: When you power on a computer, and you see an APIPA address. What does this mean, where do you look to resolve this?
  - (DHCP):

###

- Linux: Using yum (or distribution equivalent) to install a piece of software, if I am told it cannot be found in yum. How do I resolve this so I can install with yum.
  - (Add new repo to yum repolist):
