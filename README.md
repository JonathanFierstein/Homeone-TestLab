# The Homeone Test Lab Configuration Repository 

This repository will contain details of the Homeone Test Lab's network cobfiguration, provided network services, and server/workstation configuration information.


### Repository Subfolders (List Repo Subfoldeds and Their Purpose)

**vm-logs** - Each VM has a folder in this directory which contains VM creation & change logs.

**IaC** - This folder contains a subfolder for each Test Lab node which contains current IaC files for that node.

**Services** - This folder contains a file for each network service provided in the Test Lab which documents how the service is implemented on the network.


### Files in the Repository's Root Folder

**TestLab Network Configuration Details.xlsx** - This Excel Spreadsheet contains multiple color-coded sheets as follows:
  Sheet 1:Test Lab's Netowork Overview & DHCP Configuration
  Sheet 2:Test Lab Nodes - Details all Nodes and the Node's OS/Function
  Sheet 3:Test Lab IP & DNS Configuration - Details Each Node's DNS & IP settings.