# Connecting Gerrit

Connecting Gerrit connectors will help the Insights to collect and analyze various parameters related to the open source projects.&#x20;

To connect Gerrit connector for Insights, perform the following:

1.Login to PCC.

2.Click **Insights** available under under **LFX Tools** menu.

{% hint style="info" %}
You can also navigate to Insights from the Vertical Sidebar navigation menu. Click **LFX Tools** and then select **Insights**.
{% endhint %}

<figure><img src="../../../.gitbook/assets/Sec1 (1).png" alt=""><figcaption><p>Insights</p></figcaption></figure>

3.The Connectors screen appears with list of available data connectors. Click **Connect** from the Gerrit tile.&#x20;

{% hint style="warning" %}
You should have added the Gerrit server in the Source Control. If the Gerrit Server is not added in the Source Control, you cannot connect it for the Insights connectors.&#x20;

For more information refer [Gerrit Source Control](https://docs.linuxfoundation.org/lfx/project-control-center/it-services-for-a-project/source-control#setting-up-gerrit).&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/Ger.png" alt=""><figcaption><p>Gerrit </p></figcaption></figure>

4.The Gerrit Server is connected and you can see the Gerrit server details along wit the repositories associated with it.&#x20;

&#x20;

<figure><img src="../../../.gitbook/assets/In Ger.png" alt=""><figcaption><p>Gerrit and Repositories </p></figcaption></figure>

{% hint style="info" %}
If the Gerrit server or its repositories is not detected, you need to file a ticket with the support team.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/Ger Supp (1).png" alt=""><figcaption><p>Support Ticket </p></figcaption></figure>

## Connection Status for Gerrit&#x20;

There are different connection status that are available for the Gerrit organizations:

<table><thead><tr><th width="214">Connection Status </th><th>Icon</th></tr></thead><tbody><tr><td>Full Connection </td><td><img src="../../../.gitbook/assets/Greem.png" alt=""></td></tr><tr><td>No Connection </td><td><img src="../../../.gitbook/assets/grey dot .png" alt=""></td></tr><tr><td>Failed Connection </td><td><img src="../../../.gitbook/assets/Red do.png" alt=""></td></tr></tbody></table>

<figure><img src="../../../.gitbook/assets/Different Repo.png" alt=""><figcaption><p>Status </p></figcaption></figure>



## Adding Tags&#x20;

Tags will allows you to group bunch of repositories. This will allow you to  have aggregated data of each tag on Insights.

To add tags, preform the following steps:

1 Click the <img src="../../../.gitbook/assets/PL Ico (1).png" alt="" data-size="line"> icon listed next to the repository.&#x20;

<figure><img src="../../../.gitbook/assets/Plus Rep.png" alt=""><figcaption><p>Tags</p></figcaption></figure>

2\. The Add Tags dialog box appears. Select the tag name and click **Add** and select **Save**.

<figure><img src="../../../.gitbook/assets/Tags name.png" alt=""><figcaption><p>Add Tags</p></figcaption></figure>

## Disabling Instrumentation for Gerrit Account

You can disable the instrumentation for the Gerrit account as per your requirement. You can enable or disable the account to suit your needs. Disabling an account does not remove the complete account information, it only puts the account in disabled mode.

To disable Gerrit account, perform the following:

1.Use Toggle button available under Instrument.

<figure><img src="../../../.gitbook/assets/Rep Ger.png" alt=""><figcaption><p>Instrumentation </p></figcaption></figure>

2.The Disable Instrumentation dialog box appears. Click **Keep Data** to disable Gerrit account.

{% hint style="info" %}
**Remove Data** will delete the account permanently. &#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/Keep.png" alt=""><figcaption><p>Keep Data</p></figcaption></figure>

## Deleting Gerrit Account

You can delete the connected Gerrit account permanently. Deleting a Gerrit  account will remove all the configured data.

To delete the Gerrit account, perform the following

1.User Toggle button. The Disable Instrumentation dialog box appears. Click **Remove Data** to delete Gerrit account.

<figure><img src="../../../.gitbook/assets/remove.png" alt=""><figcaption><p>Remove Account </p></figcaption></figure>
