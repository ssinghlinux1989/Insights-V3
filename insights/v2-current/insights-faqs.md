# Insights FAQs

### What is new in Insights 2.0 and how is it different from Insights 1.0?

Insights 2.0 is a highly improved version of Insights 1.0.&#x20;

**Insights 2.0** supports:&#x20;

* Data lake architecture that provides a highly scalable and performance-oriented platform. Data from different data sources can be brought into the data lake layer through various native and custom connectors. Project administrators can use the Project Control Center (PCC) to configure various data sources from which project-related data is brought into the data lake layer.
* A new enhanced version of the Insights UI provides better visualization reports to analyze the data.
* A brand new **Community Management** application that empowers community managers to better manage their project communities, for example, by adding and managing affiliations and identities of technical contributors within their communities.

Insights 1.0 uses Elastic Search as the data store and embedded Kibana dashboards as the visualization layer, thus restricting the scaling and configuration of data in certain areas. The new data lake architecture in Insights 2.0 solves this problem and provides massive improvements to the scaling and performance of the tool.

### Does Insights 2.0 have a new URL?

Yes. However, the primary URL will remain unchanged and will automatically point to **Insights 2.0**.

### Why does the current release support a limited number of connectors on PCC compared to the last release?

Our goal is to make Insights 2.0 available to all the LF projects so that every Open Source Software (OSS) community gets the same experience and makes full use of the features and analytics provided by Insights 2.0.&#x20;

To scale the platform across hundreds of existing projects and growth, we had to completely re-architecture our connector ecosystem. In the upcoming releases, LFX will provide support for other native connectors, such as Jira, Confluence, Slack, Groupsio, Google Groups, Pipermail, Earned Media, Twitter, Docker Hub, and many more.

### As a Community Administrator or a Project Manager, do I need to move my projects from Insights 1.0 to Insights 2.0?

No, The LFX team will migrate the projects from Insights 1.0 to Insights 2.0, and you will be able to start using the new Insights 2.0 dashboards from day 1 of the product release.

### Do I lose access to all the dashboards and data for connectors that are showing up under Coming Soon on PCC?

No. Insights 1.0 (https://insights.lfx.dev) will still be up and running and also regularly sync data for the data sources (or connectors) that are, for the time being unavailable for v2. You can continue to use the v1 platform while we transition your project data completely to the v2 platform. Once we have completely migrated all our projects and data sources to v2, we will decommission the v1 platform.

### Will the URLs that I  bookmarked from the v1 platform redirect to and work with v2?&#x20;

Unfortunately not, since the two systems are massively different in terms of the APIs and UI, your existing URLs from v1 will not work right out of the box on the v2 platform. Please reach out to us via our community forum or support desk if you need any assistance to get the data that you are looking for.
