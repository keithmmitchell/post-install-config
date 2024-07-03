<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

THe first step is to create a Supreme Admin role and assign them Full Control access.  To do this click on Admin Panel.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/aaa5f43d-22b4-4a06-8ba5-0c4f1a6bee4b)

Then click on the Agents tab.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/af5c50f8-a482-45c6-86df-7477eedf0224)

Then click on Roles.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/c7acdc4c-84e5-402c-8726-7293de258728)

Then click Add A New Role.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/2f4eb627-89e9-432b-8758-84e514099117)

In the Definition tab enter the name Supreme User.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/291c6d84-69e5-4960-9d9c-10b6eeb652cf)

In the Permissions tab select all permissions in the Tickets section.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/cbd51efa-bd19-4461-8f29-a9fff144a001)

Then assign all permissions in the task section.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/e1244411-6986-44ab-b245-0746d25528d4)

Then finally assign all permissions in the knowledgebase and click Add Role.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/e8d6e78e-fed6-4aba-91d3-62f70f0d02c0

The next step is to add a department so click on Departments.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/eb0fb9bc-5fe2-46c1-ad7f-a5e974db52c2)

There are already two departments created already but we'll create the System Administrators department.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/fc91ba53-6e11-407c-9dff-69e286653745)

To do this click on Add A New Department.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/ab3e809a-11ac-492b-bad7-b814e321723a)

Enter the name System Administrators and click Create Dept.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/4ba056e5-b686-472d-9b38-02163b44042a)

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/705b2f39-1bcc-4ba8-b4bf-90efc6105c20)

Next, click on Teams to add a team.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/2a3703b2-46b8-49f4-acac-101d3048fdee)

Level I Support is already created so click on Add New Teams and we will create Level II.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/44cdf3fd-5bb1-4363-966a-248465ca8a31)

In the Members tab I add myself to the team then click Create Team.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/7203538d-e0b7-481d-8e8b-4fe214666d9e)

The next step is to configure the agents.  From the Agents panel click on Add New Agent.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/7afbc4f5-b3df-44bd-bab5-81e27ed78032)

In the Account Tab enter the following details:

- Name: Jane Doe
- Email Address: jane.doe@osticket.com
- Username: jane.doe
- Password: Password1

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/ec0b01fc-4260-4616-b1a7-d18b7b60ea3b)

In the Access tab select System Administrators and Supreme Admin in the Primary Department section.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/dff9a08f-c947-43cc-aca1-1ef6a71c8285)

In the Teams tab select Level II support then click Add then Create.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/01e732da-7e89-4b28-90a8-1a9db1d8ec7b)

Next create a new Agent with the following details:

- Name: John Doe
- Email Address: jane.doe@osticket.com
- Username: john.doe
- Password: Password1

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/22484946-8617-4631-b726-21c9a2498cc1)

In the Access tab select Support and View only under Primary Department and Support for Extended Access then Create.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/800f3a71-7ca9-44b2-bb27-f82c5d9a9c00)

The next step is to create users to give support to.  To do this we need to go to the Agent panel.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/2c6c58bd-ad3b-4e2f-a0d1-c3a250119b4f)

From there go to the Users tab and select Add User.

<br /?

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/ab6e7fa7-efeb-4410-a352-bf09b5905fda)








