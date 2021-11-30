# Service Now Fundamentals
> Outline a brief description of your project.
> Live demo [_here_](https://www.example.com). <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [Now Platform overview](#now-platform-overview)
* [Now Platform User Interface](#now-platform-user-interface)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->


## Now Platform overview

###### Define the Now Platform

The Now Platform from ServiceNow provides an Application Platform-as-a-Service (aPaaS). That means it is a cloud-based computing model which provides the infrastructure needed to develop, run, and manage applications. It is not limited to a specific department or function, but encompasses the entire enterprise.

The Now Platform from ServiceNow provides a modern, easy-to-use, service management solution in the cloud. It allows your organization to automate manual, repeatable processes, standardize service delivery, and focus on your core business.

ServiceNow provides all of this from a configurable web-based user interface built on top of a flexible table schema. The applications that run on the Now Platform use a single system of record and a common data model to consolidate your organization's business processes. Another advantage to this single system is that it can be leveraged to build custom applications.  

The applications delivered by ServiceNow are divided into four different workflows:



- IT Workflows

- Employee Workflows

- Customer Workflows

- Creator Workflows

There are many applications contained in each workflow. Want to learn more about these three workflows and all the applications they contain? Check out the ServiceNow web page below for all the details.


###### Identify the Now Platform architecture

The Now Platform architecture takes care of all your application infrastructure requirements, such as service availability, backups, and security. That allows you to focus on building, running, and managing great applications.

Select play on the video below to identify how the Now Platform architecture supports your infrastructure needs and gives you peace of mind. Use the Fullscreen option on the video toolbar for better viewing.

Management of all ServiceNow hosted instances, including upgrades, is performed using the Now Support (HI) (formerly known as HI Service Portal). The abbreviation HI stands for hosted instance. 

Want to get a quick overview of the Now Support (HI)? Check out the Now Support Portal video below.

Access to Now Support (HI) is typically reserved to a few team members at each site. A link to the Now Support (HI) homepage is provided below. It identifies helpful resources, such as contact information for ServiceNow Global Technical Support.
<!-- End of Now platform overview. -->


###### Now Platform interfaces

There are three ways to interact with the Now Platform. Each of the three approaches provides a different interface targeting different devices and purposes. All of these interfaces access the same single system of record and common data model of the Now Platform. The three Now Platform interfaces are:

- Now Platform user interface

- ServiceNow Mobile apps

- Service Portal

###### Now Platform UI

The Now Platform user interface is the primary way to interact with the applications and information in a ServiceNow instance. Notable Now Platform user interface features include real-time form updates, user presence, enhanced activity streams, and an application navigator designed with tabs for favorites and history.

Ideally, you should access the Now Platform user interface using your desktop or laptop computer through a web browser. Most major browsers are supported.

Want more information on the generally supported browsers for accessing the Now Platform user interface? Check out the product documentation below for details.

###### ServiceNow Mobile apps

ServiceNow offers three, persona-focused ServiceNow Mobile apps:

- ServiceNow Agent

- Now Mobile

- ServiceNow Onboarding

These apps help agents and employees work more efficiently and productively on the go. Select the flashcards below to learn more about each ServiceNow Mobile app and its target audience.

These three apps can be downloaded from the app store and configured by application developers in the Now Platform with the features, functions, and details needed for your business. The same expectations you have for all your other mobile applications outside of work, now also apply to ServiceNow Mobile apps.

Top 10 reasons to use ServiceNow Mobile apps

- Persona-focused for intuitive use

- Mobile first and completely native, using the device's built-in features

- Codeless and rapid development of new applets

- Ability to submit, view, and update requests, issues, and tasks

- Global search to find people, service and items, and articles

- Offline access with Mobile Agent to enable fulfillers to complete work while not connected

- Push notifications for access to important information instantly

- Access to Virtual Agent, chat, and knowledge articles

- Role-based access to customized information

- Manageable from an MDM (mobile device management) or an MAM (mobile application management)

Want to learn more about using and developing ServiceNow Mobile apps? Check out the Mobile Development Fundamentals on demand course available in Now Learning.

###### Service Portal

The Service Portal provides a user-friendly self-service experience, by providing access to specific features, using widgets. Users are able to:

- Search for articles, catalog items, records
- Submit requests
- Browse the corporate news feed
- And much more!

The Service Portal homepage can be accessed by navigating to https://<instancename>.service-now.com/sp. Your organization might have different ServiceNow instance environments for development, test, and production. Therefore, the <instancename> is the name of the specific ServiceNow instance you are connecting to for use. 

Both expert developers and beginners with the proper permissions can configure portals to create engaging experiences. Less technical users can make basic configuration changes to the UI, using Branding Editor and other components of Service Portal. More advanced users can edit and extend portals, pages, and widgets. Expert users can use the Widget Editor tool to write scripts to power a portal and even create rich web applications on the Now Platform.

Want to learn more about using the ServiceNow Service Portal to create engaging experiences? Check out the following resources to get started today.

###### Define the components of role-based access

The Now Platform utilizes role-based access to ensure people have the information and workflows they need to fulfill their roles – no more, no less! It is crucial to protect sensitive data. Realize not every member of your organization needs access to all information at all times. 

To understand how role-based access works in the Now Platform, it is important to first define its components. Expand the sections below to identify the purpose of each component involved in the implementation of role-based access for the Now Platform.

- User
A user is an individual that has been granted access to your ServiceNow instance.

- Group
A group is a set of users who share a common purpose. Members of groups perform similar tasks or need access to similar information for various purposes, such as approving change requests, resolving incidents, receiving email notifications, or administering the Service Catalog. Users working in ServiceNow are typically assigned to one or more groups. 

- Role
A role is a collection of permissions in the Now Platform. These permissions define which applications a user or group will and will not be able to access within the system and which actions the user will be able to take on records within the applications. A role can be assigned to a single user or a group of users. Users and groups can be assigned more than one role.



A role can contain other roles. In the example below, the catalog_admin role contains the catalog and user_criteria_admin roles. If a user or group was assigned the catalog_admin role, they would be granted the permissions of all three roles.



Generally, when you think about your "role" in the workplace, you are thinking about your specific position or title, such as project manager, developer, or operations manager.  It is the part you play and job you perform every day. For the Now Platform, the word "role" defines your capabilities in the application. Therefore, it is important to distinguish between the different definitions.


- Base System Roles

he Now Platform includes many delivered base system roles, some are described below. For a complete list of base system roles, refer to ServiceNow product documentation for "base system roles". LEARN MORE >



- System Administrator (admin): Provides almost all roles and access to all Now Platform features, functions, and data (with some exceptions such as HR and Security Operations constraints). Grant this privilege carefully. Users holding the admin role can create and modify user roles, as well as impersonate other users. 

- Specialized Administrator (example: catalog_admin): Provides users with specialized administrator roles to manage specific functions or applications, such as knowledge base, human resources, reports, and web services. 

- Approvers (approver_user): Allows users to view or modify approval records directed to them.
- ITIL (itil): Can perform standard actions for an ITIL helpdesk technician. Can open, update, close incidents, problems, changes, configuration management items. By default, only users with the itil role can have tasks assigned to them.

###### Assign role-based access

Once a collection of permissions has been defined as a role, it can be assigned to a group or user. All groups or users assigned to that role are granted the access allowed by the role permissions.  


###### GOOD PRACTICE: Rather than assigning roles to individual users, add the users to a group and assign the role to the group. This method of role assignment simplifies maintenance when responsibilities within the organization change. A user can be removed from one group and added to a new group, inheriting all the permissions needed to the perform their new duties. 

###### User authentication

When you login to ServiceNow, user authentication is the first level of security applied. It validates the identity of a user who accesses an instance. Then it authorizes the user to access features that match the user's roles or job function.

To login to ServiceNow, navigate to the URL of your ServiceNow instance in your web browser. On the login page, enter your ServiceNow User name and Password, and then select Login.


<!-- End of Now platform interfaces. -->

## Now Platform User Interface


## Features
List the ready features here:
- Awesome feature 1
- Awesome feature 2
- Awesome feature 3


## Screenshots
![Example screenshot](./img/screenshot.png)
<!-- If you have screenshots you'd like to share, include them here. -->


## Setup
What are the project requirements/dependencies? Where are they listed? A requirements.txt or a Pipfile.lock file perhaps? Where is it located?

Proceed to describe how to install / setup one's local environment / get started with the project.


## Usage
How does one go about using it?
Provide various use cases and code examples here.

`write-your-code-here`


## Project Status
Project is: _in progress_ / _complete_ / _no longer being worked on_. If you are no longer working on it, provide reasons why.


## Room for Improvement
Include areas you believe need improvement / could be improved. Also add TODOs for future development.

Room for improvement:
- Improvement to be done 1
- Improvement to be done 2

To do:
- Feature to be added 1
- Feature to be added 2


## Acknowledgements
Give credit here.
- This project was inspired by...
- This project was based on [this tutorial](https://www.example.com).
- Many thanks to...


## Contact
Created by [@flynerdpl](https://www.flynerd.pl/) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->