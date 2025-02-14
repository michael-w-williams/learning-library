<table class="tbl-heading"><tr><td class="td-logo">![](images/obe_tag.png)

June 13, 2019
</td>
<td class="td-banner">
# Lab 3: Provisioning an Autonomous Container Database
</td></tr><table>

## Introduction
An Autonomous Container Database resource provides a container for your Autonomous Databases. You can create multiple Autonomous Container Database resources in a single Autonomous Exadata Infrastructure resource, but you must create at least one before you can create any Autonomous Databases



To **log issues**, click [here](https://github.com/oracle/learning-library/issues/new) to go to the github oracle repository issue submission form.

## Objectives

As a fleet administrator
- Deploy an Autonomous Container Database (ACD) onto an Autonomous Exadata Infrastructure (AEI)

## Required Artifacts

- An Oracle Cloud Infrastructure account with fleet administrator privileges. For a detailed description of required IAM policies, please refer to the [fleet admin guide](https://docs.oracle.com/en/cloud/paas/atp-cloud/atpfg/index.html) of the autonomous database documentation set.


## Steps

### STEP 1: Create an Autonomous Container Database (ACD)

**Login to your OCI account as a fleet administrator**

Navigate to the 'Autonomous Transaction Processing' option in the top left hamburger menu from your OCI home screen

Pick 'Autonomous Container Database' from the three option, make sure you have selected the compartment hosting your exadata infrastructure and click the blue 'Create Autonomous Container Database' button

![create_acd](./images/300/create_acd.png)

On the Create Autonomous Container Database dialog box you can choose / modify the compartment to create your ACD. You also need to select the compartment hosting your AEI and the AEI instance as highlighted below

![create_acd2](./images/300/create_acd2.png)

As you scroll down the form you will see an option to modify your ACD's maintenance schedule. While the time of the maintenance is set to be the same at that of your AEI, you can specify if you'd like to the quarterly RU's ( Release Updates) or also the RURs (Release Update Rivisions)

![create_acd3](./images/300/create_acd3.png)

That's it. Simply scroll down to the bottom and hit the blue 'Create Autonomous Container Database' button to deploy your ACD.

<table>
<tr><td class="td-logo">[![](./images/obe_tag.png)](#)</td>
<td class="td-banner">
### All Done! You have successfully deployed your Autonomous Container Database and it should be available shortly.
</td>
</tr>
<table>