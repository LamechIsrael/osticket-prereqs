<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<!--- <h2>Video Demonstration</h2>

 - ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com) --->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- IIS and CGI (Internet Information Services and Common Gateway Interface)
- PHPManager
- IIS URL Rewrite
- Microsoft Visual C++
- MySQL Server

<h2>Installation Steps</h2>

<p>
<img width="790" alt="Screenshot 2024-12-15 at 4 15 48 PM" src="https://github.com/user-attachments/assets/7a15a600-98af-46b7-96a3-14940786b756" />



</p>
<p>
Before setting up osTicket I created a virtual machine using Microsoft Azure. Then I initiated a remote connection to it using "Windows App." Afterward, I initiated IIS and CGI so I could connect to the localhost.
</p>
<br />

<p>
<img width="674" alt="Screenshot 2024-12-15 at 4 23 33 PM" src="https://github.com/user-attachments/assets/8dc4c58f-19bd-45d7-a504-8823985f313d" />

</p>
<p>
There were a lot of steps needed to actually use osTicket. First, I had to install PHPManager.
</p>
<br />

<p>
<img width="569" alt="Screenshot 2024-12-15 at 4 25 05 PM" src="https://github.com/user-attachments/assets/91d34876-5644-4995-8472-7b0d928a91b6" />

</p>
<p>
Then I had to install an IIS URL Rewrite program.
</p>
<br />

<p>
<img width="589" alt="Screenshot 2024-12-15 at 4 30 52 PM" src="https://github.com/user-attachments/assets/c5414595-538b-4f20-81b0-479a361c4899" />

</p>
<p>
And Microsoft Visual C++. I believe this is an old version that can be redistributed. Otherwise, I don't know why it's called "Redistributable."
</p>
<br />

<p>
<img width="565" alt="Screenshot 2024-12-15 at 4 32 50 PM" src="https://github.com/user-attachments/assets/94e07c79-28f6-4e1f-a747-a460b1435306" />


</p>
<p>
And finally, I installed SQL. Because a database is needed to hold tickets.
</p>
<br />

<p>
<img width="603" alt="Screenshot 2024-12-15 at 4 48 58 PM" src="https://github.com/user-attachments/assets/d7b14b8f-5818-4d19-bd58-5f2b95c76087" />
<img width="609" alt="Screenshot 2024-12-15 at 4 51 15 PM" src="https://github.com/user-attachments/assets/5605a3b1-3ce7-41c3-88af-0d76e73abc0e" />


</p>
<p>
After that, I went into the IIS Manager to add a few functionalities to osTicket. I added the PHP IMAP Extention and the Intl Extension.
</p>
<br />

<p>

<img width="843" alt="Screenshot 2024-12-15 at 4 59 16 PM" src="https://github.com/user-attachments/assets/0139ea6a-c122-4d01-9c0c-b8387b27646a" />


</p>
<p>
And after all that, I am finally done. osTicket was ready for me to use on my computer.
</p>
<br />
