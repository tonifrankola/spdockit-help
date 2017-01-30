This article explains how to configure the database for SPDocKit.

SPDocKit  uses the database for storing data gathered from your SharePoint farm. If you choose not to use a database, some of the features will not be available.

These are as it follows: Some of the Site Explorer reports, Permissions Explorer history records and Permissions reports, Content & Usage reports, report subscriptions and alerts, SPDocKit Event Collection feature, license management, Queries and Rules and custom made report views.

You can also document more than one SharePoint farm using the same SPDocKit database. When installing SPDocKit on desired farms, just provide the same database details for each installation and you will be able to explore **multiple farm** reports from each SPDocKit instance.

**Please note! **This should be SPDocKit dedicated database, please **do not provide in any case SharePoint databases here.


1. Select **Configuration **from the left navigation bar on the Backstage Screen and then click the **Configure** button. ![SPDocKit 6 Configuration](https://www.spdockit.com/wp-content/uploads/2016/02/SPDocKit6-Configuration.png) 
1. Select whether to create a new database or use the existing one. Read more about the [SPDocKit database requirements](http://www.spdockit.com/support/help/requirements/spdockit-user-permission-requirements/#databaserequirements). ![SPDocKit 6 Database](https://www.spdockit.com/wp-content/uploads/2016/02/SPDocKi6-Database.png)
1. Specify **SQL Server**, **Database** **Name** and authentication. It is possible to overwrite the existing database under the same name. After providing the information, click the **Test Connection** button to ensure that the settings are correct. ![SPDocKit 6 Database Settings](https://www.spdockit.com/wp-content/uploads/2016/02/SPDocKit6-SQL-Settings.png)
1. If by any chance you have configured SQL Server on a specific port, all you have to do is place a comma after the SQL Server name and input a port. 5\. Click **Next**, wait a few seconds and your SPDocKit database will be ready to use!
