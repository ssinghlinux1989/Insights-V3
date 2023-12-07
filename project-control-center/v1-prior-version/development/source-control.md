# Source Control

Source Control allows you to track and manage updates to your code. It gives you the control to manage the right version of the code. PCC allows you to setup Source Control for your projects.

For compliance reasons, the Linux Foundation platform needs to have access to each GitHub organization you use to host your code. Your governance body and authorized community members will still be responsible and accountable for day-to-day administration of repositories, teams, and users, unless covered by a specific managed-services-agreement with the Linux Foundation.

You can setup the following Source Controls tools to your projects:

* [GitHub](source-control.md#setting-up-github)
* [GitLab](source-control.md#setting-up-gitlab)
* [Gerrit](source-control.md#setting-up-gerrit)

## Setting up GitHub <a href="#setting-up-github" id="setting-up-github"></a>

GitHub is a web and cloud-based service that helps developers to store and manage their code, as well as to track and control changes to their code base.&#x20;

You can use GitHub as a source control tool to manage your project.

To setup the GitHub account to your project, perform the following steps:

1.Login into PCC.

2\. Search for the required project. The Project dashboard appears. Click **Source Control** from the **Development** tab.

{% hint style="info" %}
You can also navigate to Source Control from the Vertical Sidebar navigation menu. Click **IT Services** and then select **Development**.
{% endhint %}

<figure><img src="../../../.gitbook/assets/SC1 (1).png" alt=""><figcaption><p>Source Control</p></figcaption></figure>

3.The Source Control page appears. Click **GitHub** and click the <img src="../../../.gitbook/assets/PL Ico (1).png" alt="" data-size="line"> icon available in front of **Connect**.

![GitHub](https://gblobscdn.gitbook.com/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MMBvrEsjsliBZECYf7t%2F-MMByCcDTjZ9B5Zxy5DQ%2FConnect.png?alt=media\&token=0891165d-b8cb-48a3-9253-6880ae5511dd)

4.The Connect GitHub Organization dialog box appears. Enter the **Organization Name** and click **Connect**.

{% hint style="info" %}
Make sure to enter a valid GitHub organization name.
{% endhint %}

![GitHub Organization Name](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-MT\_pAMg4FUQlUpKbPvg%2F-MTj0TQnzz-FlSQFT1oZ%2F-MTjDq0dhMrtHe11\_Bun%2FConnect.png?alt=media\&token=999ec864-7477-4679-acd3-f06059c897ff)

{% hint style="info" %}
* For more information on how to create an organization, refer [Create an Organization](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/creating-a-new-organization-from-scratch).
* For more information on how to transfer a repository, refer [Transfer a Repository](https://docs.github.com/en/github/administering-a-repository/transferring-a-repository).
{% endhint %}

5.Once the connection is setup, you can see the status of GitHub project and its repositories.

<figure><img src="../../../.gitbook/assets/Status.png" alt=""><figcaption><p>GitHub Status</p></figcaption></figure>

{% hint style="danger" %}
If the Organization name is changed in the GitHub, you need to connect the renamed organization again. The renamed organization won't be automatically connected even though the organization with the old name was connected.
{% endhint %}

### Setup GitHub Repositories  <a href="#invite-users-to-organization" id="invite-users-to-organization"></a>

You can manually add the repositories to the configured GitHub server.&#x20;

To add repositories to the GitHub server, perform the following steps:

1.Go to the GitHub server in the Source Control and click **+ Add Repository**. &#x20;

<figure><img src="../../../.gitbook/assets/DCO1.png" alt=""><figcaption><p>Add Repository</p></figcaption></figure>

2.The Add Repository dialog box appears. Enter the **Repository Name, Website,** **Description**. Click **Add** to add the repository. &#x20;

{% hint style="info" %}
You can also enable the DCO, Issues and Wiki by using the **Enable DCO**, **Enable Issues** and **Enable Wiki** toggle button respectively.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/DCO - Copy.png" alt=""><figcaption><p>Repository Details </p></figcaption></figure>

{% hint style="warning" %}
You have to install the DCO app before enabling the DCO on the repository. Refer [GitHub DCO ](https://githttps/github.com/apps/dcohub.com/apps/dco)for configuration. After configuring the DCO in GitHub, you can enable the DCO in the PCC.&#x20;
{% endhint %}

{% hint style="info" %}
Enabling DCO in the PCC:

* Adds branch protection rules for the default branch, so that PRs must be made before changes can be merged.
* It adds a required DCO status check for PRs

&#x20;
{% endhint %}

{% hint style="warning" %}
If the DCO app is not installed and configured for the organization before DCO is enabled on a repository, all changes to the default branch will be blocked until the app is added.&#x20;
{% endhint %}

### Invite The Linux Foundation user to your Organization <a href="#invite-users-to-organization" id="invite-users-to-organization"></a>

Your project should have its own GitHub organization, separate from your company's GitHub organization, and which is not shared with other, non-Linux-Foundation projects. If you need to, create a new GitHub organization for this project, and have a user who is an owner in both organizations transfer each project repository to this organization.

Then, invite the user “thelinuxfoundation” as an owner at the organization level (not per repository) to the GitHub organization, and connect them in Project Control Center.

{% hint style="info" %}
* We cannot accept invites unless the organization is associated with a project. Please make sure to add the project to the PCC before sending an invite to 'thelinuxfoundation" user, or the invite will not be accepted and will expire after 7 days.
* For more information on how to invite users to join organization, refer [Invite Users to an Organization](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/inviting-users-to-join-your-organization).
* For more information on how to transfer a repository, refer [Transfer a Repository](https://docs.github.com/en/github/administering-a-repository/transferring-a-repository).
{% endhint %}

{% hint style="warning" %}
If your invite has expired, you must delete it and send a new invite.
{% endhint %}

### Deleting a GitHub Organization <a href="#deleting-github-organization" id="deleting-github-organization"></a>

You can delete the added GitHub organization from the PCC.

To delete the GitHub organization that is added in the PCC, perform the following:

1.Login into PCC.

2.Click the **Source Control**.

3.Under **GitHub**, click on the required GitHub organization that you want to delete.

![GitHub Organization](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-MT\_pAMg4FUQlUpKbPvg%2F-MWSsYEQB2dSZ8dYMPfb%2F-MWSwCcGG1dBv-of9Ain%2FG1.png?alt=media\&token=3650f3de-977b-4541-a4d9-5cf6b3ef5dc2)

4.Click the ![](<../../../.gitbook/assets/Setting .png>) icon and click **Disassociate**.

![](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-MT\_pAMg4FUQlUpKbPvg%2F-MWSsYEQB2dSZ8dYMPfb%2F-MWSwaLjn4A4gyhFMSNm%2FG2.png?alt=media\&token=d324770c-e5df-4ecf-9707-809e592496af)

5.The Confirm Disassociation dialog box appears, click **Delete** to delete the GitHub Organization.

![Delete](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-MT\_pAMg4FUQlUpKbPvg%2F-MWSsYEQB2dSZ8dYMPfb%2F-MWSwtzItvRTln\_kth57%2FG3.png?alt=media\&token=985b3280-d2d4-418e-8e5d-dd77638baeaa)

## Setting up GitLab

GitLab is an open source code repository and collaborative software development platform for large DevOps and DevSecOps projects. GitLab helps you to automate the builds, integration, and verification of your code.

You can use GitLab as a source control tool to manage your project.

To setup the GitLab account to your project, perform the following steps:

1.Login into PCC.

2\. Search for the required project. The Project dashboard appears. Click **Source Control** from the **Development** tab.

{% hint style="info" %}
You can also navigate to Source Control from the Vertical Sidebar navigation menu. Click **IT Services** and then select **Development**.
{% endhint %}

<figure><img src="../../../.gitbook/assets/SC1.png" alt=""><figcaption><p>Source Control</p></figcaption></figure>

3.The Source Control page appears. Click **GitLab** and click the![](https://firebasestorage.googleapis.com/v0/b/gitbook-legacy-files/o/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MM6s2eHhjQ\_tQZBLg-r%2F-MM6sWbUBHCbO-u3210L%2FIcon.png?alt=media\&token=5797d8be-df9f-4f97-bb25-6c699e9d6253) icon available in front of **Connect**.

![GitLab](https://gblobscdn.gitbook.com/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MMBzyPEWoumUhMMbi3v%2F-MMC0CxSwdrHEJorgf-y%2FGitlab.png?alt=media\&token=4cec0390-4573-4d2e-9c84-4aa8e5e4b99a)

4.The Connect GitLab Group dialog box appears. Enter the **Group Name** and click **Connect**.

{% hint style="info" %}
The name of the group should be added and not the url or the ID.
{% endhint %}

![GitLab Group Name](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-MT\_pAMg4FUQlUpKbPvg%2F-MTj0TQnzz-FlSQFT1oZ%2F-MTjEYXWtQ06emjLntt6%2FConnect\_Gitlab.png?alt=media\&token=5b16d66f-392d-40c9-a158-4e8d8b361c64)

5.Once the connection is setup, you can see the status of GitLab project and its repositories.

![GitLab Status](https://gblobscdn.gitbook.com/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MMBzyPEWoumUhMMbi3v%2F-MMC1IC5alHrzKrM8PIg%2FLab\_Status.png?alt=media\&token=2b0ce2d2-76bf-4cfe-a1bb-1c3f0372d003)

## Setting up Gerrit&#x20;

Gerrit is a web-based code review tool, which is integrated with Git and built on top of Git version control system (helps developers to work together and maintain the history of their work). It allows merging changes to Git repository when you are done with the code reviews.&#x20;

1.Login into PCC.

2\. Search for the required project. The Project dashboard appears. Click **Source Control** from the **Development** tab.

{% hint style="info" %}
You can also navigate to Source Control from the Vertical Sidebar navigation menu. Click **Development** and then select **Source Control**.
{% endhint %}

<figure><img src="../../../.gitbook/assets/SC1 (2).png" alt=""><figcaption><p>Source Control</p></figcaption></figure>

3.The Source Control page appears. Click **Gerrit** and then click **File Ticket** to submit a ticket to configure Gerrit server for your project.&#x20;

<figure><img src="../../../.gitbook/assets/Gerrit.png" alt=""><figcaption><p>Gerrit </p></figcaption></figure>

4\. In the Support Form, provide details such as summary, project name, Gerrit URL and description. Click **Create** to submit the request to the support team.&#x20;

<figure><img src="../../../.gitbook/assets/Supp Tick.png" alt=""><figcaption><p>Support Ticket</p></figcaption></figure>

5.Once the support team configures the Gerrit server, the Gerrit server is added in the source control along with the associated repositories.&#x20;

<figure><img src="../../../.gitbook/assets/Gerr and Repo.png" alt=""><figcaption><p>Gerrit</p></figcaption></figure>

### Adding Repositories

You can manually add the repositories to the configured Gerrit server.&#x20;

To add repositories to the Gerrit server, perform the following steps:

1.Go to the Gerrit server in the Source Control and click **+ Add Repository**.&#x20;

<figure><img src="../../../.gitbook/assets/Add Repo.png" alt=""><figcaption><p>Add Repository </p></figcaption></figure>

2.The Add Repository dialog box appears. Enter the **Repository Name** and **Description** and click **Add**.&#x20;

{% hint style="info" %}
You can use the toggle button if you want to enable the repository as the parent repositories for other repositories.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/Repo Dial.png" alt=""><figcaption><p>Add Repository </p></figcaption></figure>

### Updating the Repository&#x20;

You can update the repository name and other changes with respect to the listed repository.&#x20;

To update the repository details, perform the following steps:

1.Go to the required repository and click the ellipsis  <img src="../../../.gitbook/assets/Icon (12).png" alt="" data-size="line">icon and select Edit Repository.&#x20;

<figure><img src="../../../.gitbook/assets/Edit Repo.png" alt=""><figcaption><p>Edit Repository</p></figcaption></figure>

2.The Edit Repository dialog box appears. You can update the **Repository Name**,  **Enable DCO** and **Description** and click **Save** to update the changes.&#x20;

<figure><img src="../../../.gitbook/assets/Ed Re.png" alt=""><figcaption><p>Repository Updates</p></figcaption></figure>

### Making a Repository as Writeable or Readable&#x20;

You can set a repository as readable from writeable or from writeable to readable. To set the repository as readable or writeable, click the ellipsis <img src="../../../.gitbook/assets/Icon (3).png" alt="" data-size="line"> icon and select **Set Repository as Readable** or **Set Repository as Writeable**.&#x20;

{% hint style="info" %}
When the repository is set as Writeable, the Read-only column is set as **Yes** and when the repository is set as Readable, the Read-only column is set to **No**.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/Read and Write.png" alt=""><figcaption><p>Read and Write Access </p></figcaption></figure>

### Hiding a Repository and Restrict All  Access&#x20;

You can hide a repository and restrict all access to the repository by clicking the ellipsis <img src="../../../.gitbook/assets/Icon (2).png" alt="" data-size="line"> icon and selecting the **Hide Repository and Restrict All Access**.&#x20;

<figure><img src="../../../.gitbook/assets/Hide Repo.png" alt=""><figcaption><p>Hide Repository </p></figcaption></figure>

### Deleting a Repository&#x20;

You can delete the listed repository by clicking the ellipsis <img src="../../../.gitbook/assets/Icon (2).png" alt="" data-size="line"> icon and selecting the **Delete Repository**.

<figure><img src="../../../.gitbook/assets/Del Repo.png" alt=""><figcaption><p>Delete Repository </p></figcaption></figure>
