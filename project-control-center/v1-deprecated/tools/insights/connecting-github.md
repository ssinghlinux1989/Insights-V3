# Connecting GitHub

Connecting GitHub connectors will help the Insights to collect and analyze various parameters related to the open source projects.&#x20;

To connect GitHub connector for Insights, perform the following:

1.Login to PCC.

2.Click **Insights** available under **LFX Tools** menu.

{% hint style="info" %}
You can also navigate to Insights from the Vertical Sidebar navigation menu. Click **LFX Tools** and then select **Insights**.
{% endhint %}

<figure><img src="../../../../.gitbook/assets/Sec1 (1).png" alt=""><figcaption><p>Insights</p></figcaption></figure>

3.The Connectors screen appears with list of available data connectors. Click the ![](../../../../.gitbook/assets/Plus\_icon.png) icon listed next to Connect GitHub Organization tab.&#x20;

{% hint style="info" %}
Project Administrator can connect to a new organization. Project Maintainer can enable or disable instrumentation on repos, or enable an existing ("autodetected") org, but they cannot connect a new org.
{% endhint %}

<figure><img src="../../../../.gitbook/assets/Connect Git.png" alt=""><figcaption><p>Connect </p></figcaption></figure>

4\. If you want to add a new organization apart from the auto detected organizations, enter the organization name in the **Organization** field under Additional Organization and click **Connect**&#x20;

{% hint style="info" %}
If you have already set up your GitHub orgs or repositories in PCC, they will automatically be detected and available for your project in the **Auto Detected Organizations**. You can click **Connect** to connect to the auto detected GitHub organizations.&#x20;

You can connect Organization that has **Full Connection** status. Refer [Connection Status](https://docs.linuxfoundation.org/lfx/project-control-center-pre-release/tools/insights/connecting-github#connection-status-for-github-organization) for more information.&#x20;
{% endhint %}

<figure><img src="../../../../.gitbook/assets/Github list.png" alt=""><figcaption></figcaption></figure>

6.The connected GitHub account is listed under Configure Account, click **Save** to complete the GitHub connection.

{% hint style="info" %}
Once the project is onboarded, it might take up to 48 hours for the project to show up on LFX insights.

The green dot under Instrumentation Status indicates that the GitHub account is enabled.
{% endhint %}

<figure><img src="../../../../.gitbook/assets/Git Sa.png" alt=""><figcaption><p>Save</p></figcaption></figure>

## Connection Status for GitHub Organization&#x20;

There are different connection status that are available for the GitHub organizations:

<table><thead><tr><th width="214">Connection Status </th><th>Icon</th><th>Description </th></tr></thead><tbody><tr><td>Full Connection </td><td><img src="../../../../.gitbook/assets/FC.png" alt="" data-size="line"></td><td> thelinuxfoundation user is added to the organization. </td></tr><tr><td>Partial Connection </td><td><img src="../../../../.gitbook/assets/PC (2).png" alt="" data-size="line"></td><td>thelinuxfoundation user is added to the organization but not an owner of the organization.</td></tr><tr><td>No Connection </td><td><img src="../../../../.gitbook/assets/NCq.png" alt="" data-size="line"></td><td>thelinuxfoundation user is not added to the organization.</td></tr><tr><td>Organization Not Found </td><td><img src="../../../../.gitbook/assets/ON.png" alt="" data-size="line"></td><td>The organization does not exist.</td></tr></tbody></table>

## Disconnecting GitHub Account&#x20;

You can disconnect a GitHub account as and when you desire to disconnect it.&#x20;

To disconnect a connected GitHub account, perform the following steps:

1.Click Disconnect for the organization that you want to disconnect.&#x20;

<figure><img src="../../../../.gitbook/assets/Dis.png" alt=""><figcaption><p>Disconnect </p></figcaption></figure>

2.The Disconnect GitHub Organization dialog box appears. Click Disconnect.&#x20;

<figure><img src="../../../../.gitbook/assets/Disc .png" alt=""><figcaption><p>Disconnect </p></figcaption></figure>

3.Click **Save** to apply the changes.&#x20;

<figure><img src="../../../../.gitbook/assets/Sa.png" alt=""><figcaption><p>Save</p></figcaption></figure>

## Disabling Instrumentation for GitHub Account

You can disable the instrumentation for the GitHub account as per your requirement. You can enable or disable the account to suit your needs. Disabling an account does not remove the complete account information, it only puts the account in disabled mode.

To disable GitHub account, perform the following:

1.Click **Manage**.&#x20;

<figure><img src="../../../../.gitbook/assets/Man.png" alt=""><figcaption><p>Manage</p></figcaption></figure>

2.Use Toggle button available under Instrument.

<figure><img src="../../../../.gitbook/assets/Toogl.png" alt=""><figcaption><p>Instrument </p></figcaption></figure>

3.The Disable Instrumentation dialog box appears. Click **Keep Data** to disable GitHub account.

{% hint style="info" %}
**Remove Data** will delete the account permanently. &#x20;
{% endhint %}

<figure><img src="../../../../.gitbook/assets/Keep.png" alt=""><figcaption><p>Keep Data</p></figcaption></figure>

## Deleting GitHub Account

You can delete the connected GitHub account permanently. Deleting a GitHub account will remove all the configured data.

To delete the GitHub account, perform the following:

1.Click the delete ![](../../../../.gitbook/assets/Delete\_Icon.png) icon available under Manage tab. The Disconnect GitHub URL appears, click **Disconnect**.

OR

2.User Toggle button. The Disable Instrumentation dialog box appears. Click **Remove Data** to delete GitHub account.

<figure><img src="../../../../.gitbook/assets/remove.png" alt=""><figcaption><p>Remove Account </p></figcaption></figure>
