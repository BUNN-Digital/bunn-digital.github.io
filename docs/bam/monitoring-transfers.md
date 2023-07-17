---
title: "Monitoring File Transfers"
layout: default
parent: "BUNN Asset Management API"
has_children: false
nav_order: 4
---

# Monitoring File Transfers

API requests such as pushing a Brew Schedule or Recipe Assignment are asynchronous. Therefore, to verify a transfer was successful, you will need to monitor for success or failure.

In the future, file transfers will be available via the BUNN Event APIs. But, for now, users of these file transfer operations will need to monitor them via the BUNNlink Portal application.

## Viewing the File Transfer in BUNNlink Portal

1. Navigate to [BUNNlink Portal](https://bunnlink.bunn.com/)
2. Log in using your user credentials. If you do not have credentials, please contact our Support Team to [request access](registration)
3. From the Dashboard, locate the left sidebar, and select 'Machines' -> 'List All'

    ![List All option under Machines menu](/assets/images/content/bam-api/bunnlink-machines-list-all.png)

4. Search for your machine's Serial Number in the search box on the right

    ![Searching for a machine](/assets/images/content/bam-api/bunnlink-search-machines.png)

5. Find your machine and click on the Machine Name

    ![Select your machine by name](/assets/images/content/bam-api/bunnlink-select-machine.png)

6. This will load the dashboard for your machine
7. In left sidebar, select content overview under the menu with your machine name


    ![Select Content Overview from the menu with your machine's name](/assets/images/content/bam-api/bunnlink-select-content-overview.png)

8. View 'Content Transfers' in the Right Column for status updates

    ![List of Content Transfers](/assets/images/content/bam-api/bunnlink-content-transfers.png)

    Status List:

    1. **<mark style="background-color: grey; color: white">&nbsp;Pending&nbsp;</mark>** - The content is currently being transferred to the machine.
    2. **<mark style="background-color: grey; color: white">&nbsp;Sent&nbsp;</mark>** - The content has been delivered to the machine.
    3. **<mark style="background-color: green; color: white">&nbsp;Complete&nbsp;</mark>** - The content has been successfully applied to the machine.
    4. **<mark style="background-color: red; color: white">&nbsp;Failed&nbsp;</mark>** - There was an issue transferring or applying the content to the machine.