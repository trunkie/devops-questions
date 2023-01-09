# Ansible

1. What is Ansible?
2. What is configuration management?
3. Is Ansible only a tool for configuration management?
4. What are the components of Ansible?
5. How Ansible works?
6. What are the other tools in market other than Ansible?
7. How Ansible is different from chef & puppet?
8. What is inventory is Ansible?
10. What are the types of inventories?
11. What is play & playbook?
12. Difference between hosts & groups?
13. What is Roles?
14. How to install a Role?
15. How to install multiple roles?
16. How to create roles?
17. What is dynamic inventory & when we use it & for what?
18. Where is the Ansible configuration file located?
19. What are the different ways other than ssh by which Ansible can connect to remote hosts?
20. What is variable in Ansible?
21. What are different types of variables?
22. How to assign variables in group vars & hosts vars?
23. Difference between file & template directory in Roles?
24. Difference between default & vars directory in Roles?
25. What is jinja 2 template?
26. What is modules in Ansible?
27. Difference between copy & file modules?
28. Difference between SHELL & COMMAND modules?
29. What is setup module ? what it does?
30. What is register $ debug in Ansible?
31. What is changed_when in Ansible?
32. Can we disable automatic facts gathering in Ansible?
33. How error handling can be done in Ansible?
34. How to ignore failed commands in Ansible?
35. What is handlers ? why we use handlers in Ansible?
36. What is privilege escalation in Ansible?
37. Task to connect(SSH) Ansible to remote host using another user & run the playbook to the remote host using with another user ?
38. What is Ansible vault?
39. How to decrypte a vault file?
40. How to encrypt a string in Ansible using Ansible vault?
41. If a string is encrypted in a file with a password then how to pass the password using parameter while decrypting?
42. If a file in encrypted using password & password is stored in a file how to pass the file to decrypt the file?
43. If a file is encrypted using password & password is also encrypted then how to provide the password while decrypting the file?
44. What is Ansible galaxy?
45. What is tags in Ansible ? why it is used?
46. What is lookup in Ansible playbook?
47. How to control the command failure in Ansible?
48. How to debug your playbook?
49. What is diff mode?
50. What is dry run in Ansible & how to do that?
51. What is pre task & post task?
52. How you can run your all tasks at once?
53. What is block in ansible?
54. What are different variable scopes?
55. Dow variable precedence tasks place?
56. Defference between include & import?
57. How to include custom modules in ansible?
58. Describe the role directory structure?

# Ansible Task

## Task 1
Part 1: Write Ansible playbook to automate jenkins deployment
Part 2: Write Ansible role to install Docker & setup Kubernetes cluster
#### Automate the pipeline creation in Jenkins to create docker container & deploy on Kubernetes cluster

## Task 2
#### Write Ansible playbook for below tasks:
1. Install apache server and deploy sample html application
2. Create /var/www/example.com
3. Deploy a sample application to the above directory
4. Create a virtual host for deploy application and set it as default virtualhost