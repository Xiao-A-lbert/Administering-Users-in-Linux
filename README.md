<h1>Administering Users in Linux</h1>

<h2>Description</h2>
In this Linux home lab, I addressed a practical help desk ticket that wanted me to add two users in Ubuntu, create an expiring password for them, add them to a "confidential" group, create a "Confidential" directory, give root owner and new created group users full permissions, and assign others zero permissions. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux CLI</b> 

<h2>Environments Used </h2>

- <b>Linux Mint 22</b> 

<br />
<br />

<p align="center">
Help Desk Ticket:
 
![0) Help Desk ticket](https://github.com/user-attachments/assets/ea1bf8df-71d6-4570-abcf-44fce659c160)

<br />
<br />
Created users bertram and elrich.  <br/>

![1) Create users bertram and elrich](https://github.com/user-attachments/assets/68676e8b-91d7-44bb-b986-b641fff05ed3)

<br />
<br />
Set expiring passwords for new users and switched users to set new password after expiry.

![2) Expire new user passwords ](https://github.com/user-attachments/assets/77ea3d98-66e4-42a0-a4ee-5244635f5eae)

<br />
<br />
Created new "Confidential" directory in root directory.

![3) Create new  Confidential  directory in root directory](https://github.com/user-attachments/assets/42bfa2aa-f089-4c7a-80c9-427218be0cbf)

<br />
<br />
Created "confidential group", added elrich and bertram to confidential group, and set confidential group as group for "Confidential" directory.

![4) Added erlich   bertram to confidential group and set confidential as group for directory](https://github.com/user-attachments/assets/f99eb01e-5d70-4df5-84e6-6e5cc1d30947)

<br />
<br />
Set full permissions to root owner and group and zero permissions for other. 

![5) Changed permissions for owner, group, and other ](https://github.com/user-attachments/assets/012a6ef3-6326-442d-9b80-7c1095904fee)

<br />
<br />
Confirmed proper permissions as elrich in Confidential directory by creating a test file. 

![6) Confirmed proper permissions as erlich in Confidential directory by creating a test file](https://github.com/user-attachments/assets/6e1dc9ea-258d-493e-ab93-085236d2ef9e)
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
