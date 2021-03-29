<p align="center"><a href="https://advantagecsp.com/Assets/AdvantageCMS/Images/advantagecsp-2x.png" rel="noopener" target="_blank"><img width="500px" src="https://advantagecsp.com/Assets/AdvantageCMS/Images/advantagecsp-2x.png" alt="Advantage CSP - Enterprise-Class Content Management System"></a></p>

## About Advantage CSP ##

Build Better Digital Products, Faster. Advantage CSP is an enterprise-class content services platform that powers complex websites, mobile apps, and business applications while offering the flexibility to adapt to each organization's unique processes and workflows.

It features:

- Centrally manage thousands of sites using just one interface
- 30% faster development and deployment time compared to a traditional CMS
- Spend less time on coding and more time on scaling your business
- Fully extensible and flexible framework
- A completely extensible .NET framework that opens up a world of possibilities. 

You can learn all about it at [advantagecsp.com](https://advantagecsp.com), and documentation is available at [support.advantagecsp.com](https://support.advantagecsp.com/hc/en-us).

## Tech Specs

You must install .Net Framework 4.7.1 or higher developer pack. You should have Visual Studio 2015 or higher(2017 - Recommended). You should have SQL 2012 or higher. Learn more here: https://support.advantagecsp.com/hc/en-us/articles/360024704171-Project-Overview

## Popular Resources

- **[Documentation](https://support.advantagecsp.com/hc/en-us/categories/360001530711-Developer-Guide)** – Read the official docs.
- **[Guides](https://support.advantagecsp.com/hc/en-us/categories/115001150106-Admin-User-Guide)** – Follow along with the official guides.
- **[#advantagecsp](https://twitter.com/hashtag/advantagecsp)** – See the latest tweets about Advantage CSP.


## First Time Setup
- Install -> Stop all instances of Visual studio and double-click to install the .vsix.
- Create Project -> Open Visual Studio -> Create a new project -> Select "AdvantageCSP Project" type.
- Configure Database -> Open the web.config and set the connection string for your database server.  Make sure the user specified has privileges to create a new database
	- Server -> Name or IP address of database server
	- Database -> Name of the database that will be created for this project (will automatically be created on initialization.
	- User -> SQL Server user ID
	- Password -> SQL Server password
- On startup you will will land on the default "Coming Soon" page.  Navigate to the /advantagecsp/initializecsp to begin setup of the project.



