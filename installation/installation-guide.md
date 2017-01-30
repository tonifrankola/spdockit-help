This article explains how to install SPDocKit.

**System Requirements:** The product uses the SharePoint Server Object Model to retrieve information about your farm and it needs to run on the SharePoint server to be able to make API calls. It needs to be installed on a **SharePoint 2010, SharePoint 2013 or SharePoint 2016** server to load farm information. The application can be installed on a workstation with **Windows 8** or **Windows 7** operating system, but you will not be able to load new SharePoint farm settings, but only connect to an existing SPDocKit database and open already saved farm settings. [Read more about required system settings](http://www.spdockit.com/support/help/requirements/system-requirements/). 1. [Download](/downloads/) Application. 2\. Unpack and run the **SPDocKitSetup.exe**. The wizard will guide you through the installation steps, click **Next >** to proceed. ![SPDocKit 6 Installation Wizard](https://www.spdockit.com/wp-content/uploads/2016/02/SPDocKit6-Installation.png) 3\. Click **I Accept the terms of the license agreement** to accept the license and then click **Next >** to proceed. ![SPDocKit 6 EULA](https://www.spdockit.com/wp-content/uploads/2016/02/SPDocKit6-Installation-EULA.png) 4\. Choose the desired installation type:

*   **Install** - the product will be installed on your computer.
*   **Run** - the application will NOT be installed on your server but rather unpacked to a temporary folder. This is a zero footprint run, the application will not make any changes to your server. Some functions like automatic snapshots will not be available in this mode.

![SPDocKit 6 Installation Type](https://www.spdockit.com/wp-content/uploads/2016/02/SPDocKit6-Installation-Type.png) 5\. Choose between Default or Advanced installation.

*   **Default** – program will be installed with default features. That is, only the SPDocKit application.
*   **Advanced** – choose which program features you want to be installed. Available additional features are **SPDocKit Collection Service** and **SPDocKit Event Viewer**.

![SPDocKit Installation Setup Type](https://www.spdockit.com/wp-content/uploads/2016/10/spdockit-setup-type.png) 6\. When using Advanced installation mode, select the desired feature using the dropdown menu next to the feature name. If the icon next to the feature is gray, this feature will be installed. If the icon next to the feature name is little red cross, then this feature will not be installed at the end of this process.

*   The **Event Collection Service** crawls the ULS and Windows Event Logs and indexes them. Install this feature on a **server outside of your SharePoint farm** for minimal impact.
*   The **SPDocKit Event Viewer** is used to search and view the events that the Collection Service has indexed. This is a standalone application which can be run without the SPDocKit application. You can install it on any available server, including the one where SPDocKit is installed. [Read more about SPDocKit Event Collection.](http://www.spdockit.com/support/help/get-to-know-documentation-toolkit/monitoring-screen/)

![SPDocKit Custom Feature Selection](https://www.spdockit.com/wp-content/uploads/2016/10/spdockit-installation-custom-features.png) 7\. Choose the installation folder e.g. **C:\Program Files\Acceleratio\SPDocKit.** Click **Next >** to proceed. ![SPDocKit 6 Destination Folder](https://www.spdockit.com/wp-content/uploads/2016/02/SPDocKit6-Destination-Folder.png) 8\. Select the location where to create application shortcuts and preferred availability option (**Anyone** or **Only me**). Click **Next >** to proceed. ![SPDocKit 6 Installation Folder](https://www.spdockit.com/wp-content/uploads/2016/02/SPDocKit6-Installation-Folder.png) 9\. The installation wizard will unpack your files and you will be able to run the application from: **Start** > **All Programs** > **SPDocKit**. 10. [Configure SPDocKit Database and Snapshot Service](http://www.spdockit.com/support/help/configuration-wizard/) settings.

* * *

### Installation guide video

<iframe src="//www.youtube.com/embed/3O4fRDDlyJg" width="640" height="360" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

### Tips&Tricks

If during the installation you encounter any problems and wish to enable logging to help you resolve the problems, you can start the installation using the command prompt with the following argument:

```
*   * /l="full path" will create a log file on a specified location.
*   * /log will create the log file in an installation directory.
```

Note that this will work for both .exe and .msi installation files.

### Learn more

*   [How to: Create Farm Documentation](http://www.spdockit.com/support/help/how-to/farm-documentation/create-farm-documentation/ "Create SharePoint Farm Documentation")
*   [How to: Compare SharePoint Farms](http://www.spdockit.com/support/help/how-to/compare-wizard/compare-sharepoint-farms/)
*   [How to: Configure Automatic Snapshots](http://www.spdockit.com/support/help/how-to/sharepoint-farm-snapshots/configure-automatic-snapshots/ "Configure Automatic Snapshots")
