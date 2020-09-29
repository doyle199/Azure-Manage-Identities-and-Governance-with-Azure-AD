# Azure-Manage-Identities-and-Governance-with-Azure-AD
Azure Manage Identities and Governance with Azure AD

To get started with Azure AD one shall create an organization and users for it. Sign into the Azure portal. In the left menu click on create resource, then search for Azure Active Directory. Click create. 

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/1.png)

Enter the organization name, custom azure domain name, country, and click create to create a Tenant. Wait for the tenant to be created and then click into it.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/2.png)

Start an Azure AD Premium P2 trial. In the new directory. It can be switched by clicking on the top right of the page and changing the directory if it doesn’t automatically switch. 

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/3.png)

To add a user, you must have administrative privileges. To see one’s own access role, click on roles and administrators in the left menu. It will display the name of your role.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/4.png)

Click users in the left menu and then new user.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/5.png)

From here one can create individual users, create bulk users by uploading a csv file or invite a user.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/6.png)

Click on create user. We shall make one user for now. Fill out the username and name. Choose a to auto-generate or create the initial password.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/7.png)

It is important to add users to groups. As there are no groups now, we shall do that after user creation. Roles are also very important, assign according to least privileged access. One can block sign in by location. Enter the job title and Department and click create.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/8.png)

Click on Groups in the left menu then new group. 

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/9.png)

Choose the group type (Security or Microsoft 365), group name and description. Choose to allow roles or not, which as of this writing is in preview. Choose a membership type (Assigned, Dynamic User, or Dynamic Device). Select any owners and any members. Click create.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/10.png)

Make more groups according to company departments.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/11.png)

Next create more users for each group while selecting the groups option during user creation.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/12.png)

Admins can enable self-service password reset by clicking on password reset in the left menu then select group. Choose a group and click select.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/13.png)

MFA should be enabled for all users and is always enabled for self-service password reset. You can make the MFA stronger by clicking on Authentication methods in the left menu. Admins have the ability to change the registration, notifications, customized helpdesk link, and on-premises password writebacks.  

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/14.png)

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/15.png)

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/16.png)

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/17.png)

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/18.png)

To collaborate by using guest accounts and Azure AD B2B. Select users and then new guest user.  Click on users then new guest user. Leave invite user selected. Enter the guest users email address and give the user a name and correct access. Click invite. 

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/19.png)

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/20.png)

An email will be sent to the guests email that they must accept.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/21.png)

The guest will have to create a Microsoft account if they don’t already have one and then accept the permissions from your organization.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/22.png)

To add a guest user to an application, select Enterprise applications and then all applications. Click new application.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/23.png)

Add an application if one doesn’t have any yet.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/24.png)

Select users and groups in the left menu and then click add user. 

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/25.png)

Select users and groups and choose the guest user. Click select and then assign.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/26.png)

You can further assign roles, groups, administrative assignments, licenses, devices, azure role assignments, and authentication methods to the guest user to make sure that least privileged access is enforced.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/27.png)

Now when that guest user signs into azure that app will be available to them.

![alt text](https://github.com/doyle199/Azure-Manage-Identities-and-Governance-with-Azure-AD/blob/master/28.png)

TO BE CONTINUED
