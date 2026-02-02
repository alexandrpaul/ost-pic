<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration

This project demonstrates hands-on experience configuring a comprehensive helpdesk environment. It covers role-based access control, department and team setup, agent and user account management, SLA configuration, and helpdesk system customization. The work reflects practical enterprise IT responsibilities, including secure account administration, workflow optimization, and the delivery of structured, efficient support across an organization.

## Environments and Technologies Used

- **Windows 10 (21H2)**
- **Internet Information Services (IIS)**


## Skills Demonstrated

- Role-Based Access Control (RBAC) Configuration
- Department & Team Management
- User & Agent Account Administration
- Service Level Agreement (SLA) Management
- Helpdesk System Customization
- System Administration & Configuration


## Tasks for this project

### 1. Configure User Roles
Navigate to **Admin Panel** → **Agents** → **Roles**. Enter the desired role name (*for this example: Principal Admin*) and select **Add Role** to apply.

![Screenshot](https://github.com/alexandrpaul/ost-pic/blob/5fb5bf3384a47e02eec102696b33a347abbdc3bb/Screenshots/img1.png)



### 2. Configure Departments
Navigate to **Admin Panel** → **Agents** → **Departments**. Define the department name as required (*for this instance, System Administrators*) then select **Add Department** to finalize the entry.

![Screenshot](https://github.com/alexandrpaul/ost-pic/blob/5fb5bf3384a47e02eec102696b33a347abbdc3bb/Screenshots/img2.png)



### 3. Configure Teams in Admin Panel
Navigate to **Admin Panel** → **Agents** → **Teams** and define the desired team name.
For this configuration, **Level III Support** was used as the example.
Select **Create Team** to finalize the setup.

![Screenshot](https://github.com/alexandrpaul/ost-pic/blob/5fb5bf3384a47e02eec102696b33a347abbdc3bb/Screenshots/img3.png)



### 4. Enable Public Ticket Creation
Navigate to **Admin Panel** → **Settings** → **User Settings** and ensure **“Registration Required: Require registration and login to create tickets”** is **unchecked** to allow ticket submission without user registration.

![Screenshot](https://github.com/alexandrpaul/ost-pic/blob/5fb5bf3384a47e02eec102696b33a347abbdc3bb/Screenshots/img4.png)



### 5. Configure New Agents
Navigate to **Admin Panel** → **Agents** → **Add New**. Enter the desired agent details (*for this instance, Pablo Maneho*) and select **Add Agent** to complete the setup.

![Screenshot](https://github.com/alexandrpaul/ost-pic/blob/5fb5bf3384a47e02eec102696b33a347abbdc3bb/Screenshots/img5.png)



### 6. Configure Users in Agent Panel
Navigate to **Agent Panel** → **Users** → **Add New** . Enter the desired user information (*for this instance, Michael Townley*) and select Add User to complete the configuration.

![Screenshot](https://github.com/alexandrpaul/ost-pic/blob/5fb5bf3384a47e02eec102696b33a347abbdc3bb/Screenshots/img6.png)



### 7. Configure Service Level Agreement (SLA)
Access the **Admin Panel** → **Manage** → **SLA**. Define the desired SLA parameters. For this example, **SEV-B** is set with a **1-hour response** during **Business Hours: Monday – Friday, 8am – 5pm**. Click **Add Plan** to apply.

![Screenshot](https://github.com/alexandrpaul/ost-pic/blob/5fb5bf3384a47e02eec102696b33a347abbdc3bb/Screenshots/img7.png)



### 8. Configure Help Topics
Navigate to **Admin Panel** → **Manage** → **Help Topics**.
Enter the desired topic name (*for this instance, Password Reset*) and select **Add Topic** to complete the configuration.

![Screenshot](https://github.com/alexandrpaul/ost-pic/blob/5fb5bf3384a47e02eec102696b33a347abbdc3bb/Screenshots/img8.png)



<h2> Final Thoughts </h2>

<p> Completing these tasks provided practical experience managing a helpdesk environment on Windows 10 (21H2) with IIS, covering the full spectrum of enterprise IT responsibilities. Configuring role-based access, structuring departments and teams, and managing agent and user accounts reinforced hands-on skills in secure administration and operational workflow. Setting up SLAs and customizing helpdesk functionalities demonstrated the ability to maintain service accountability while optimizing support efficiency. This work sharpened both technical execution and organizational awareness, providing a strong foundation for delivering reliable, professional IT support within an enterprise environment. </p>
