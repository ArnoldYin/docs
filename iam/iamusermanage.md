---

copyright:

  years: 2015, 2017

lastupdated: "2017-05-17"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Managing users and access
{: #iamusermanage}

Depending on the access options that you are authorized to manage, you can view and manage users across the account or organization. As an account owner, you can manage users in any of the access options that you administer and to which the user is assigned access in the current account.
{:shortdesc}

To manage users in your account, complete the following steps:

1. From the menu bar, click **Manage** &gt; **Account** &gt; **Users**. The Users window displays a list of users with their email addresses and current status in the accounts you manage. 
2. Select the user name, or click **Manage user** from the **Actions** menu. 
3. Then, depending on what access you can manage, update the access for the user in the Service policies or Cloud Foundry roles sections, or click the link to access the Assign Infrastructure Access page.

Review the following sections for additional information about managing each type of access and information about using the Team Directory.

If you need to review your assigned access in an account that you have been added to, complete the following steps:

1. From the menu bar, click **Manage** &gt; **Security** &gt; **Identity & Access** &gt; **Users**. 
2. Select your name. 
3. Review your assigned roles.

If you need your role or service policy changed, you must contact the organization manager or account owner to update the Cloud Foundry role or the administrator for the service or service instance to update the service policy.

## Cloud Foundry access
{: #iammancfser}

To manage access to account organizations and spaces, you must be the account owner, organization manager, or space manager:

1. From the menu bar, click **Manage** &gt; **Security** &gt; **Identity & Access** &gt; **Users**. 
2. Select the user name that you want to edit roles for.
3. From the **Actions** menu in the Cloud Foundry section, you can:

  * Remove the user from the organization
  * Edit the organization role
  * Edit the space role

You can also add a user to another organization by clicking **Assign Organization**, if you are the manager of an organization that the user is not yet a member of. 


## Identity and access enabled services
{: #iammanidaccser}

To manage service policies or assign new service policies for users, you must be the account access administrator or the assigned administrator for the particular service or service instance.

1. From the menu bar, click **Manage** &gt; **Security** &gt; **Identity & Access** &gt; **Users**. 
2. Select the user name that you want to assign service policies for.
3. Select **Assign service policies** to create a new service policy, or from the **Actions** menu in the Service policies section, you can:
  
  * Edit the policy
  * Remove the policy

For more information about service policies and roles, see [Identity and access management policies and roles](/docs/iam/users_roles.html#iamusermanpol).

## Infrastructure services

If you have access to assign infrastructure permissions, you can set the following roles for the user: View Only, Basic User, or Super User. Click the **Assign Infrastructure Access** link to update or assign new permissions.

For more information about the permissions, see [Infrastructure permissions](/docs/iam/users_roles.html#infrapermissions).

## Managing Cloud Foundry roles in the Team Directory
{: #editinguserroles}

From the Team Directory page, account owners can manage platform-only users. However, if you can go to the **Manage** &gt; **Account** &gt; **Users** page, you can manage all platform and infratructure services users in one place.

Organization managers can edit organization and space roles for existing users on the Team Directory page.

1. Locate and select the team member whose roles you want to edit.
2. Click **View roles**.
3. Select or clear the space role selections to modify the space access for the team member.
4. Click **Save**.

Space managers can edit roles for the team members in their space.

1. Locate and select the team member whose roles you want to edit.
2. Click **View roles**.
3. Click **View spaces**.
4. Select or clear the space role option for the role that you want to add or remove for the team member.
5. Then, click **Save**.
