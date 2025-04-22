Exp 8: Create a user account 

AIM:
To create a user with UID 1326 and username as alies

EQUIPMENTS REQUIRED:
Hardware: Minimum 4 GB RAM and 25 GB storage – essential for running services like Cockpit and handling system updates smoothly.
Software: Red Hat Enterprise Linux (RHEL) or any open-source Linux OS like Fedora or CentOS Stream – used for system administration and repository creation.

PROCEDURE & COMMENTS:
The first command is: useradd -u 1326 alies
This command creates a new user account on the system. Here's a breakdown of the options used:
1. useradd: This is the command used to create a new user account. 
2. -u 1326: This option specifies the user ID (UID) for the new user account. The UID is a unique identifier associated with each user account. In this case, the new user account will have a UID of 1326. 
3. alies: This option specifies the username for the new user account. The username is the name that the user will use to log in to the system.   
The second command is: cat /etc/passwd | grep "alies" 
This command is used to verify the information about the newly created user account. Here's a breakdown of the options used: 
	1. cat: This command is used to display the contents of a file. In this case, it's used to display the contents of the /etc/passwd file.
 2. /etc/passwd: This file contains information about all user accounts on the system. Each line in the file contains information about one user account in the following format: username:password:UID:GID:full name or comment:home directory:default shell 
3. grep "alies": This option pipes the output of the cat command to the grep command. The grep command is used to search for a specific pattern in the input. In this case, it's used to search for lines that contain the username "alies"
The third line in the image is a shell prompt, which indicates that the user is ready to enter another command.
In summary, these commands create a new user account named "alies" with a UID of 1326 and then verify the information about the newly created user account

EXPECTED OUTPUT:
![OSOS_EXP_08](https://github.com/user-attachments/assets/85d74f87-7685-46e8-8aad-f34b39ddc5c6)

RESULT:
Thus the user has been created successfully. 
RESULT:
Thus the user has been created successfully. 
