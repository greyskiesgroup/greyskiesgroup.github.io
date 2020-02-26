# Welcome to Grey Skies Group

![Grey Skies Logo](images/logo_130.png)

Although fictional the Grey Skies Group is representative of a medium size enterprise which sells items to other businesses.  
With its headquarters in Brisbane, Australia there are also regional sales and logistics operations across Australia, in the United States of America, and in the United Kingdom, giving Grey Skies Group a global footprint.

An area of growth for the group over the past 3 years has been its cloud retail business. As one of the world’s premier cloud retailers Grey Skies Group prides itself on the efficiency which its customers can order from a large catalogue of clouds and have them delivered quickly and cost effectively.

## Grey Skies Group offices

| **Australia**           | **USA**         | **UK** |
| ----------------------- | --------------- | ------ |
| Brisbane (Headquarters) | New York | London |
| Sydney                  | Dallas |
| Perth                   |

**Headquarters**

The headquarters has office space in Brisbane&#39;s CBD for its sales and management staff and houses around 50 workers.

There is also office space in a technology park in a Brisbane suburb which is used exclusively by the internal software development team (more on the team structure later).

**Regional Offices**

Each of the regional offices contain up to 30 staff with around 80% being sales and support staff. These staff provide an on-site presence for local customers and maintain relationships with regional vendors.

Regional offices have a high percentage of mobile staff relying on their portable devices (mobile phones, iPads, and laptops) to access Grey Skies Group enterprise systems.

## The software development teams

Grey Skies Group have a significant development team with over 20 full time staff. These staff are primarily split into 3 teams.

The largest of the two three teams is the **Enterprise Systems** team, responsible for the inventory, logistics and finance system, _Rainydays_.

- Team Lead
- Snr. Software Engineer\*
- Architect\*
- Business Analyst\*
- Snr. Software Developer x 2
- Software Developer x 3
- Snr. Tester x 2

_\* these roles are shared with other teams when necessary_

The next largest team, **Sales Systems** , is the responsible for the Sales and CRM system, _Snowstorm_ (Blizzard was taken).

- Team Lead
- Snr. Software Developer x 3
- Software Developer
- Jnr. Software Developer
- Tester x 2

The smallest and newest team, **Cloud Systems** , was introduced to support the growing Cloud sales sector. Unlike the incumbent teams this team has been given support from the organisations management to operate in an Agile agile manor. If this is successful other teams will also be allowed to operate in a more agile manor.

- Team Lead
- Snr. Software Developer x 2
- Software Developer
- Tester

[Learn about this team](team-cloudsystems.md)

_As the new sparkly team on the block the Snr. Software Engineer and Architect have shown a keen interest in the Cloud Systems team and want to make their mark by getting involved. You can be sure they will be interested in having their 2 cents about all the decisions getting made._

## Existing Technologies

All the software applications developed for Grey Skies Group have been build using MS development tooling and the .Net.NET framework (varying versions). Priding itself on its ability to &quot;keep up&quot; with technical advances all systems are running the Microsoft Azure platform, to make them &quot;cloud apps&quot;.

### Rainydays

This is actually 3 separate ASP.Net.NET MVC apps (.Net.NET Framework version 4.5), ): one for Finance, one for Inventory, and one for Logistics. Backed by a shared Azure SQL database these apps have not seen much evolution since their inception 7 years ago.

Historically all interaction with Grey Skies Group suppliers have been integration directly from the Rainydays inventory application.

### Snowstorm

AngularJS single page application in front of an ASP.Net.NET Web API (.Net.NET Framework version 4.5). This application is significantly newer than Rainydays and was built to replace Greys Skies Group&#39;s dependence on Microsoft Dynamics as it failed to deliver on the features and the Mobile mobile capabilities required for the Grey Skies Group sales team.

### Integrations

When sales people place orders for customers in Snowstorm that order is &quot;submitted&quot; to Rainydays by adding a new order to the &quot;IncommingOrders&quot; table for the shared Rainydays database.

## More detail about Grey Skies Group

- Grey Skies Group has recently appointed a new CTO to attempt to resolve the issues they have been having keeping their internals systems competitive. The first project undertaken by the new CTO was to migrate all of the internal systems off self-hosted servers to Microsoft Azure.

- The new CTO is also responsible for the creation of the Cloud Systems team and backing the team to work with an Agile agile project structure.

- The Grey Skies Group executive leadership team consider &quot;responsiveness&quot; to be a key principle for the organisation&#39;s success. This responsiveness is expected in all aspects of the organisation and in turn it&#39;s systems. This means sales staff must get back to customers within minutes, not hours, logistics have extremely aggressive targets for deliveries, and the software systems are expected to by be &quot;fast&quot; no matter where the customer is located.

- With the move to Azure this means that each application has a node in each of the main countries or regions.
