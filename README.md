# Data-Dashboard
Intelehealth Data Dashboard  is an information management tool that is used to track KPIs, metrics, and other key data points relevant to the organization. 

At Intelehealth, we utilize the open-source "Apache Superset" BI tool to create dashboards that empower users to leverage past data to identify trends and make informed decisions. 

Through the implementation of this tool, we provide program-specific dashboards that enable real-time data insights, data analysis over a specific time period, and identification of areas requiring urgent actions. 

By using these dashboards, the Intelehealth core team can take necessary actions to streamline workflows, optimize resource utilization, and improve overall decision-making processes.

##Pre-requisites
1. Ubuntu 20.04 onwards
2. nginx
3. certbot for letsencrypt

##Instructions
1. Install superset using <https://superset.apache.org/docs/installation/installing-superset-from-scratch/>
2. Login into superset using admin credentials
3. Import databases from this file <https://github.com/Intelehealth/Data-Dashboard/blob/main/database_export_20231213T090811.zip>  using instructions from <https://intelehealthwiki.atlassian.net/wiki/spaces/INTELEHEAL/pages/26214416/Importing+Exporting+Apache+Superset+Data+Dashboard>
4. Change DB details
5. Import sample dashboard file <https://github.com/Intelehealth/Data-Dashboard/blob/main/dashboard_export_20231213T085944.zip> using instructions from <https://intelehealthwiki.atlassian.net/wiki/spaces/INTELEHEAL/pages/26214416/Importing+Exporting+Apache+Superset+Data+Dashboard> and you have the Superset working!!
   
   

