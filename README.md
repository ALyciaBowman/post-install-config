<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This project outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machine/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives/Steps </h2>

- Configure Roles

   a. Admin Panel -> Agents -> Roles

   b. (add new role) Supreme Admin

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/bb40792d-572d-44be-bf58-5cfe5bf65b9e)


- Configure Departments

   a. Admin Panel -> Agents -> Departments

   b. (add new department) System Administrators

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/5b9357d6-3da7-4b64-a66c-a540289ca435)


- Configure Teams

   a. Admin Panel -> Agents -> Teams

      i.  Level I Support

      ii. Level II Support

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/8573f79b-e726-44a1-9f7a-6ecc1f415669)


- Allow anyone to create tickets

   a. Admin Panel -> Settings -> User Settings

   b. Registration Required: Require registration and login to create tickets

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/a30bce5c-2248-4697-8c8a-d2e350c59759)



- Configure Agents (workers)

  a. Admin Panel -> Agents -> Add New

      i.  Jane

      ii. John

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/527cb077-235e-4c2b-87c8-d2febcc54c89)

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/93193b06-d4cc-4fe5-b4fc-69dc0a862c84)



- Configure Users (customers)

  a. Agent Panel -> Users -> Add New

      i.  Karen

      ii. Ken

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/238c5dfd-d308-4a3c-9364-599770c43803)


- Configure SLA

  a. Admin Panel -> Manage -> SLA

      i.   Sev-A (1 hour, 24/7)

      ii.  Sev-B (4 hours, 24/7)

      iii. Sev-C (8 hours, business hours)

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/169bbc02-d63b-4c33-9c60-97a45e03e548)

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/026f4493-338f-42b9-859e-81766eccd920)



- Configure Help Topics

  a. Admin Panel -> Manage -> Help Topics

       i.   Business Critical Outage

      ii.  Personal Computer Issues

      iii. Equipment Request

      iv.  Password Reset

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/9f464d09-d585-4d34-93cf-f8fb0f732e2d)

  ![image](https://github.com/ALyciaBowman/post-install-config/assets/141197471/344f46ce-43f0-461d-a429-039c7748102e)








<br />
