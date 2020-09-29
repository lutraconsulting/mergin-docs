---
layout: page
title: Working with QGIS plugin for Mergin
---

You can manage your Mergin projects from within QGIS through Mergin plugin. The sections below describe how to install, configure, create, upload and synchronise your projects and data from QGIS.

### Mergin plugin installation and configuration

To install Mergin plugin in QGIS:

1. Open QGIS

2. From the main menu, Plugins > Manage and Install Plugins ...

3. A new window will appear:

	3.1 In the **Search** section, type: Mergin

	3.2 Select Mergin in the filtered section and then click **Install Plugin**

4. Once installed, you should see Mergin in your QGIS Browser panel (note that if you are using QGIS 3.12 or earlier you will need to restart your QGIS for Mergin to appear in your browser panel):

	<p align="center"><img src="./images/qgis-plugin/installation.png" width="50%"></p>

	**Note:** if you cannot see your Browser panel, you can enable it by going to the QGIS main menu > View > Panels > Browser

After installation, you need to configure the plugin by entering your Mergin username and password:

1. From the QGIS Browser panel, right-click on **Mergin** and select **Configure**

	<p align="center"><img src="./images/organisations/set-billing-info.png" width="90%"></p>

2. In the new window, type in your username (or email address used for signing up with Mergin) and password

	<p align="center"><img src="./images/qgis-plugin/configure.png" width="50%"></p>

You can select to store the password. For that you need to have already configured your [QGIS password manager](https://docs.qgis.org/3.10/en/docs/user_manual/auth_system/auth_overview.html?highlight=password#master-password)
