<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA's
- Configure Help Desk Topics

<h2>Configuration Steps</h2>

The first step is to create a Supreme Admin role and assign it Full Control access.  To do this, click on Admin Panel.

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

Then assign all permissions in the Tasks section.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/e1244411-6986-44ab-b245-0746d25528d4)

Then finally assign all permissions in the Knowledgebase and click Add Role.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/e8d6e78e-fed6-4aba-91d3-62f70f0d02c0)


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

In the Members tab, I add myself to the team then click Create Team.

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

In the Access tab select System Administrators and Supreme Admin in the Primary Department section.  In Extended Access assign the Support department and Supreme Admin group.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/dfada322-eb26-405c-ae2e-c9f14bd45ec0)


In the Teams tab select Level II support then click Add then Create.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/01e732da-7e89-4b28-90a8-1a9db1d8ec7b)

Next create a new Agent with the following details:

- Name: John Doe
- Email Address: john.doe@osticket.com
- Username: john.doe
- Password: Password1

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/22484946-8617-4631-b726-21c9a2498cc1)

In the Access tab select Support and Supreme Admin under Primary Department and Support for Extended Access then Create.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/d1c38e56-7cc9-453b-a509-5c99544c0f2a)


The next step is to create users to give support to.  To do this we need to go to the Agent panel.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/2c6c58bd-ad3b-4e2f-a0d1-c3a250119b4f)

From there go to the Users tab and select Add User.

<br /?

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/ab6e7fa7-efeb-4410-a352-bf09b5905fda)

Enter the email address Karen@osticket.com and the Full Name Karen Karen then click Add User.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/f678cc7e-e375-4fd3-8c56-591d0e8166cc)

Do the same again but this time add the user Ken.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/0e74eb9d-2fee-4a05-a4d2-c3c2c1074870)

Next the Service Level Agreements need to be configured.  Go back to the Admin panel, click the Manage tab, select SLA then click Add New SLA Plan.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/573d60dc-c98f-4135-98d2-32696aac717d)

Enter the following:

- Name SEV-A
- Grace period: 1 hour
- Schedule:24/7

Then click Add Plan

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/085da1ba-36f3-479f-a166-1ea9fb3e0cef)

Create another two plans with the following:

- Name SEV-B
- Grace period: 4 hours
- Schedule:24/7

Enter the following:

- Name SEV-C
- Grace period: 8 hours
- Schedule: Mon - Fri

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/f1d0e2e4-6e91-4ec1-a710-1bb062c812f0)

Next the Help Topics need to be configured.  On the Admin Panel in the Manage tab click Help Topics and then Add New Help Topic.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/0fe2e84c-5659-443f-a471-3c6511461fe2)

Enter "Business Critical Outage" for the topic name then click Add.

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/92f6931c-f9f4-48f2-af44-ecb899c9498b)

Create three more Topics:

- Personal Computer Issues
- Equipment Request
- Password Reset

<br />

![image](https://github.com/keithmmitchell/post-install-config/assets/174253055/7c458596-5d7b-44dd-846d-1626cb3bd6b5)

That brings us to the end of Part 2 of this lab.  Please go to https://github.com/keithmmitchell/ticket-lifecycle for the final part. 








