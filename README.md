# LAB2
1. 
Create a user account with the following attribute
 username: islam
 Fullname/comment: Islam Askar
 Password: islam
 ![Screenshot from 2022-11-26 15-58-57](https://user-images.githubusercontent.com/90289910/204092569-a8331eaf-1406-49dd-a2ed-5e59dc158105.png)
 ------------------------------------------------------------------------------------------------------------
2.
Create a user account with the following attribute
Username: baduser
Full name/comment: Bad User
Password: baduser
![Screenshot from 2022-11-23 15-08-11](https://user-images.githubusercontent.com/90289910/204092635-45fc6022-e31c-45b4-926e-191a4c325c9f.png)
--------------------------------------------------------------------------------------------------------------
3.
Create a supplementary (Secondary) group called pgroup with group ID of 30000
![Screenshot from 2022-11-24 14-07-42](https://user-images.githubusercontent.com/90289910/204092674-7670b9ad-a36f-44c1-9e54-1782273e6650.png)
---------------------------------------------------------------------------------------------------------------
4.
Create a supplementary group called badgroup
![Screenshot from 2022-11-26 16-05-53](https://user-images.githubusercontent.com/90289910/204092791-fa4ce5cd-8965-4813-b33e-267cf50c6424.png)
---------------------------------------------------------------------------------------------------------------
5.
Add islam user to the pgroup group as a supplementary group

![Screenshot from 2022-11-24 14-25-59](https://user-images.githubusercontent.com/90289910/204092817-ad2cc8af-5958-4838-830e-9b32428d54c5.png)
---------------------------------------------------------------------------------------------------------------
6.
Modify the password of islam's account to password
![Screenshot from 2022-11-24 14-43-36](https://user-images.githubusercontent.com/90289910/204092853-d217d8ef-9bca-457d-b049-74561a155a9b.png)
----------------------------------------------------------------------------------------------------------------
7.
Modify islam's account so the password expires after 30 days
![Screenshot from 2022-11-24 14-46-25](https://user-images.githubusercontent.com/90289910/204092905-43158290-a228-45a8-b579-7920c96ec5cd.png)
-----------------------------------------------------------------------------------------------------------------
8.
Lock bad user account so he can't log in
![Screenshot from 2022-11-24 14-49-15](https://user-images.githubusercontent.com/90289910/204092933-c6f9e8ca-1b3f-43a4-93c4-99fce2c0dad5.png)
-------------------------------------------------------------------------------------------------------------------
9.
Delete bad user account
![Screenshot from 2022-11-24 14-57-37](https://user-images.githubusercontent.com/90289910/204092986-644ad9ed-c1fe-4791-851d-95551650bc64.png)
-------------------------------------------------------------------------------------------------------------------
10. Delete the supplementary group called badgroup.
![Screenshot from 2022-11-24 14-58-49](https://user-images.githubusercontent.com/90289910/204093020-d0888d1d-b001-4e97-83f9-16d48a3618d4.png)
---------------------------------------------------------------------------------------------------------------------
13. Create a folder called myteam in your home directory and change its permissions to
read only for the owner.

![Screenshot from 2022-11-24 15-13-23](https://user-images.githubusercontent.com/90289910/204093043-a7275642-604e-42c5-947a-b2ecf53fbc72.png)
-----------------------------------------------------------------------------------------------------------------------
14. Log out and log in by another user
exit
![Screenshot from 2022-11-26 16-13-36](https://user-images.githubusercontent.com/90289910/204093185-f803dcae-4ea3-48e7-a105-3a93ee174318.png)

------------------------------------------------------------------------------------------------------------------------
15. Try to access (by cd command) the folder (myteam)
![Screenshot from 2022-11-26 15-17-04](https://user-images.githubusercontent.com/90289910/204093240-62366cb6-e05a-41c8-9f3e-1a7c149fca8c.png)
------------------------------------------------------------------------------------------------------------------------
16. Using the command Line
Change the permissions of oldpasswd file to give owner read and write
permissions and for group write and execute and execute only for the others
(using chmod in 2 different ways)

![Screenshot from 2022-11-26 15-21-25](https://user-images.githubusercontent.com/90289910/204093373-0ad17385-2f28-47ee-b326-fe519008c692.png)
-------------------------------------------
//Change your default permissions to be as above.
What is the maximum permission a file can have, by default when it is just
created? And what is that for directory.
for the file it is read/write only
for directory read/write/execute
--------------------------------------------
Change your default permissions to be no permission to everyone then create a
directory and a file to verify.
![Screenshot from 2022-11-26 15-36-41](https://user-images.githubusercontent.com/90289910/204093479-26ec9cf2-6125-4a6e-8d0a-d7cfdcc85739.png)
--------------------------------------------------------------------------------------------------------------------------
17.
What are the minimum permission needed for:
Copy a directory (permission for source directory and permissions for target
parent directory)
for the source-> read and execute 
for target-> write and execute
-------------------------------
Copy a file (permission for source file and and permission for target parent
directory)
source->read
target->write
-------------------------------
Delete a file
execute and write
-------------------------------
Change to a directory
execute and write
-------------------------------
List a directory content (ls command)
execute and read
-------------------------------
View a file content (more/cat command)
read
-------------------------------
Modify a file content
read and write
---------------------------------------------------------------------------------------------------------------------------
18. Create a file with permission 444. Try to edit in it and to remove it? Note what
happened.

![Screenshot from 2022-11-26 15-38-40](https://user-images.githubusercontent.com/90289910/204093878-c011c1d4-6647-4915-9010-879095fc214e.png)
-----------------------------------------------------------------------------------------------------------------------------
19. What is the difference between the “x” permission for a file and for a
directory?
execute (x) Execute permission on files means the right to execute them, if they are programs. 
For directories, execute permission allows you to enter the directory.





