<table class="tbl-heading"><tr><td class="td-logo">[![](images/obe_tag.png)](README.md)

Last Updated:<br>October 12, 2018
</td>
<td class="td-banner">
# Getting Started with Autonomous Data Warehouse                                    
</td></tr><table>


This workshop walks you through all the steps to get started using the **Oracle Autonomous Data Warehouse  (ADW)**. You will provision a new ADW database, load data from the object store and troubleshoot data loads, query external data residing on the object store, manage an ADW instance, scale an ADW instance, and use Oracle Machine Learning notebooks.


## Goals for this workshop

 - Get comfortable with Oracle's public cloud services
 - Provision a new ADW database
 - Run sample queries against the sample data sets
 - Load data from the object store
 - Query external data from the object store
 - Manage and Monitor an ADW instance
 - Scale an ADW instance
 - Use Oracle Machine Learning SQL notebooks
 - Use Oracle Data Visualization Desktop (DVD) with ADW
 - Use Oracle Data Integration Platform Cloud (DIPC) with ADW

# How to Get Your Free Cloud Trial Account
If you already have an Oracle Cloud account then you can skip this section. If you don't have an Oracle Cloud account then you can quickly and easily sign up for a free trial account that provides:

$300 of free credits good for up to 3500 hours of Oracle Cloud usage
Credits can be used on all eligible Cloud Platform and Infrastructure services for the next 30 days
Your credit card will only be used for verification purposes and will not be charged unless you 'Upgrade to Paid' in My Services
Click on the image below to go to the trial sign-up page which will allow you to request your free cloud account:

[![](http://www.oracle.com/webfolder/technetwork/tutorials/learning_path/images/700705-auto-dw-social-bn728_-152.png)](https://myservices.us.oraclecloud.com/mycloud/signup?language=en&sourceType=APMK180704P0003:APACVT082918:ie:mt)

Once your trial account is created, you will receive a Welcome to Oracle Cloud email that contains your cloud account password along with links to useful collateral. To sign into the Oracle Cloud, copy and paste this URL into a browser window: [https://cloud.oracle.com](https://cloud.oracle.com)


# Workshop Overview

## Before Your Begin
**What is an Autonomous Data Warehouse?**

Oracle Autonomous Data Warehouse is built around the market leading Oracle database and comes with fully automated data warehouse specific features that deliver outstanding query performance.  This environment is delivered as a fully managed cloud service running on optimized high-end Oracle hardware systems.  You don’t need to spend time thinking about how you should store your data, when or how to back it up or how to tune your queries.  

We take care of everything for you.

Click here to [watch our short video](https://www.youtube.com/watch?v=tZMZODoi2xw) that explains the key features in Oracle's Autonomous Data Warehouse.

Oracle’s Autonomous Data Warehouse is the perfect quick-start service for fast data loading and sophisticated data reporting and analysis.  Oracle manages everything for you so you can focus on your data.

Read on to begin your Getting Started journey with Oracle Autonomous Data Warehouse.


**Lab Pre-requisites – Required Software**
This workshop needs two desktop tools to be installed on your computer to do the exercises in this lab.

*1. SQL Developer*
  To download and install SQL Developer please follow [this link](http://www.oracle.com/technetwork/developer-tools/sql-developer/downloads/index.html), and select the operating system for your computer. This page also has instructions on how to install SQL Developer on Windows, Mac OSX and Linux.

  If you already have SQL Developer installed on your computer then please check the version. The minimum version that is required to connect to an Oracle Autonomous Data Warehouse Cloud is SQL Developer 17.4.

*2. Data Visualization Desktop*
  To download and install Data Visualization Desktop please follow [this link](https://www.oracle.com/technetwork/middleware/oracle-data-visualization/downloads/oracle-data-visualization-desktop-2938957.html), and select the operating system for your computer. This page also has instructions on how to install DVD on Windows and Mac OSX.

  If you already have Data Visualization Desktop installed on your computer then please check the version. The minimum version that is required to connect to an Oracle Autonomous Data Warehouse Cloud is 12c 12.2.5.0.0.


**Getting Help During This Workshop**
  ![](images/README-9a67ec93.png)

[**CloudCustomerConnect**](https://cloudcustomerconnect.oracle.com/resources/32a53f8587/summary) Forum for Autonomous Data Warehouse
If you have a question during this workshop then use the Autonomous Data Warehouse Forum to post questions, connect with experts, and share your thoughts and ideas about Oracle Autonomous Data Warehouse.

Are you are completely new to the [CloudCustomerConnect](https://cloudcustomerconnect.oracle.com/resources/32a53f8587/summary) forums? Visit our forum  [Getting Started page](https://cloudcustomerconnect.oracle.com/pages/1f00b02b84) to learn how to best leverage community resources.

**You are all set, let's begin!**



## Step 1: Getting Started and Provisioning a New Autonomous Data Warehouse
This lab walks you through the steps of logging into Oracle Cloud, accessing the Oracle Autonomous Data Warehouse console and provisioning your first Autonomous Data Warehouse. The last part of this lab will explore how to connect to your new data warehouse using Oracle SQL Developer.

**Key Objectives**:

- Learn how to sign-in to the Oracle Public Cloud
- Learn how to provision a new Autonomous Data Warehouse instance
- Learn how to download the client credentials wallet file
- Learn how to connect from Oracle SQL Developer

**Click here to run [Lab 1](LabGuide1.md)**


## Step 2: Working with Data Warehouse Services and the Free Sample Data Sets
In this lab you will explore the free sample data sets that are included witin your new autonomous data warehouse. As part of this lab you will experiment with the selecting different levels of database services that come with your Autonomous Data Warehouse.

**Key Objectives**:

- Learn about the different levels of Autonomous Data Warehouse service (HIGH, MEDIUM, LOW)
- Learn about the Star Schema Benchmark (SSB) and Sales History (SH) sample data sets
- See how the different levels of database service affect performance and concurrency

**Click here to run [Lab 2](LabGuide2.md)**



## Step 3: Loading Data into Your New Autonomous Data Warehouse
In this lab, you will be uploading files to Oracle Object Storage, creating new sample tables, loading data into those sample tables from files on the OCI Object Storage, and troubleshooting errors relating to your data load jobs.

**Key Objectives**:

- Learn how to upload files to the Oracle Cloud Infrastructure (OCI) Object Storage
- Learn how to load data from an object store
- Learn how to use the SQL Developer Data Import Wizard to load data
- Learn how to troubleshoot data loads

**Click here to run [Lab 3](LabGuide3.md)**



## Step 4: Querying External Data
In this lab, you will be querying files directly on Oracle Object Storage without loading them to your autonomous data warehouse.

**Key Objectives**:

- Learn how to define external tables against Oracle Object Store data sets
- Learn how to query external tables
- Learn how to create data warehouse user

**Click here to run [Lab 4](LabGuide4.md)**



## Step 5: Creating Rich Data Visualizations
This lab will walk you through the process of connecting your Autonomous Data Warehouse to Data Visualization Desktop and then use DVD and build sophisticated data visualizations to help your business teams get deeper insights about their data

**Key Objectives**:

- Learn how to connect your free Data Visualization Desktop analytics tool to Autonomous Data Warehouse
- Learn how to secure a desktop client connection to Autonomous Data Warehouse
- Learn how to create a simple data visualization project with Oracle Data Visualization Desktop
- Learn how to access and gain insights from data in the Autonomous Data Warehouse

**Click here to run [Lab 5](LabGuide5.md)**




# Bonus Labs - Slightly More Advanced Labs for Data Warehouse Developers, Cloud DBAs and Data Scientists

The following labs will let you explore some of the more advanced features of your Autonomous Data Warehouse. They cover the following topics that will help you expand your knowledge by introducing some more advanced topics for Autonomous Data Warehouse" 

1) Managing and monitoring Autonomous Data Warehouse using the Cloud Console
2) Using Oracle Machine Learning SQL Notebooks
3) Introduction to machine learning with DBMS_PREDICTIVE_ANALYTICS
4) Using data integration tools with Autonomous Data Warehouse



## Bonus Lab - Lab 6:  Managing and Monitoring Autonomous Data Warehouse using the Cloud Service Console
For this lab you will watch a couple of demos to show the capabilities available via the Cloud Console and Autonomous Data Warehouse Service Console.

**Key Objectives**:

- Learn how to start/stop your ADW instance
- Learn how to recover your data warehouse - if needed
- Learn how to use the service console to monitor the performance of your Autonomous Data Warehouse

**Click here to run [Bonus Lab 6](LabGuide6.md)**




## Bonus Lab - Lab 7: Scaling and Performance in Autonomous Data Warehouse
In this lab you will scale up your Oracle Autonomous Data Warehouse instance by adding more CPUs with on interruption to your service. You will watch a recorded demo that shows the performance and concurrency impacts of scaling your service online.

**Key Objectives**:

- Learn how to scale up and down the CPUs and storage used by your Autonomous Data Warehouse
- See how scaling affects your concurrency and performance

**Click here to run [Bonus Lab 7](LabGuide7.md)**



## Bonus Lab - Lab 8:  Using Oracle Machine Learning SQL Notebooks
During this lab you will be using the new Oracle Machine Learning SQL notebook application that is part of your Autonomous Data Warehouse. This browser-based application provides a web interface to run SQL queries and scripts, which can be grouped together within a notebook. Notebooks can be used to build single reports, collections of reports, and dashboards. Oracle Machine Learning provides a simple way to share workbooks with other OML users.

**Key Objectives**:

- Learn how to create new users for Oracle Machine Learning
- Learn how to run a SQL Statement
- Learn how to share notebooks
- Learn how to create and run SQL scripts

**Click here to run [Bonus Lab 8](LabGuide8.md)**



## Bonus Lab - Lab 9: Simple Introduction to Machine Learning Algorithms
During this lab you will be using the Oracle Machine Learning SQL notebook application to explore how you can use the in-database DBMS_PREDICTIVE_ANALYTICS functionality. DBMS_PREDICTIVE_ANALYTICS provides a set of easy-to-use procedures that simplify the machine learning process.

**Key Objectives**:

- Learn how to use DBMS_PREDICTIVE_ANALYTICS routines
- Learn how to use Oracle ML Gallery
- Learn how to import notebooks into Oracle ML

**Click here to run [Bonus Lab 9](LabGuide9.md)**



## Bonus Lab - Lab 10: Using Data Integration Tools with Autonomous Data Warehouse
In this lab, you will configure and use Oracle Data Integration Platform Cloud (DIPC) with Autonomous Data Warehouse. This lab follow a typical enterprise data warehouse reference implementation with ETL/ELT batch processing, real time data replication, and data quality review. You will load data from a flat file and a database table using Oracle Data Integrator (ODI) to your Autonomous Data Warehouse. You will replicate data from a database table to Autonomous Data Warehouse using Oracle Golden Gate (OGG). You will review data quality in your Autonomous Data Warehouse using Oracle Enterprise Data Quality (EDQ).

**Key Objectives**:

- Learn how extract, load and transform data into your Autonomous Data Warehouse using Oracle Data Integration Platform
- Learn how to replicate data into your Autonomous Data Warehouse with Oracle GoldenGate (OGG)
- Learn how to review data quality your Autonomous Data Warehouse with Oracle Enterprise Data Quality (EDQ)

**Click here to run [Bonus Lab 10](LabGuide10.md)**



## Learn More About Autonomous Data Warehouse...

Use these links to get more information about Oracle Autonomous Data Warehouse

 - [Oracle Autonomous Data Warehouse website](https://www.oracle.com/database/data-warehouse/index.html)
 - [Oracle Autonomous Data Warehouse ipaper](http://www.oracle.com/us/products/database/autonomous-dw-cloud-ipaper-3938921.pdf)
 - [Oracle Autonomous Data Warehouse Documentation](https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/index.html)
 - [Additional Autonomous Data Warehouse Cloud Tutorials](https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/tutorials.html)