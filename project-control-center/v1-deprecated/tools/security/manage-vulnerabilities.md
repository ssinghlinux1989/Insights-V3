# Manage Vulnerabilities

Manage Vulnerabilities allows you to perform the following tasks:

* Enable or disable vulnerability scanning for a repository to refine scanning report of the project.
* Auto enabling repositories for scanning vulnerabilities.

## **Enable/Disable a Repository for Vulnerability Scan**

You can enable or disable a repository for vulnerability scanning in PCC from the Manage Vulnerabilities tab. If you enable a repository for vulnerability scanning, the repository is scanned for the vulnerabilities. If you disable the vulnerability scanning for a repository, the scanning will be skipped for the selected repository and vulnerabilities are not detected.

To enable or disable a repository for vulnerability scan, perform the following steps:

1.Login into [PCC](https://projectadmin.lfx.linuxfoundation.org).

2\. Search for the required project. The Project dashboard appears. Click **Security** from the **LFX Tools** tab.

{% hint style="info" %}
You can also navigate to Security from the Vertical Sidebar navigation menu. Click **LFX Tools** and then select **Security**.
{% endhint %}

<figure><img src="../../../../.gitbook/assets/Sec2 (2).png" alt=""><figcaption><p>Security</p></figcaption></figure>

3.The Security page appears. Click **Manage Vulnerabilities** tab, all repositories of the project are listed in alphabetical order.

![Manage Vulnerabilities](../../../../.gitbook/assets/MV.png)

{% hint style="info" %}
The fail scan details for the repository such as time and date of the is displayed when you click the <img src="../../../../.gitbook/assets/Info.png" alt="" data-size="line"> icon.
{% endhint %}

4.Under **Scan Vulnerabilities** tab, toggle **scan** button to enable or disable a repository from scanning.

{% hint style="info" %}
You can also enable or disable scanning for all repositories by toggle of **Scan Vulnerabilities**.
{% endhint %}

![Scan Repositories](../../../../.gitbook/assets/MV2.png)

5\. Under **Last** **Scan Results** tab, you can see whether the repository scan has been successful or failed while scanning the repository.

When the scan of the repository is successful, it is displayed as **Successful** and if there are any errors, it will be displayed as **Failed**.

{% hint style="info" %}
The fail scan details for the repository such as time and date of the is displayed when you click the <img src="../../../../.gitbook/assets/Info (1).png" alt="" data-size="line"> icon.
{% endhint %}

![Last Scan Results](../../../../.gitbook/assets/MV3.png)

## Auto Enable Scanning of Repositories for Vulnerabilities <a href="#auto-enable-scanning-of-repositories-for-vulnerabilities" id="auto-enable-scanning-of-repositories-for-vulnerabilities"></a>

You have an option to auto enable scanning of repositories for vulnerability scanning when a new repository is added in the GitHub project. When you select the Auto enable option, all new repositories are scanned for the vulnerabilities.

You can the **Auto Enable New Repositories** toggle button to set the auto scanning of the new repositories. This button is available in the **Manage Vulnerabilities** tab.

![Auto Enable](../../../../.gitbook/assets/MV4.png)
