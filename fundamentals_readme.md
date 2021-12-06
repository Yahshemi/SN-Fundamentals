# Service Now Fundamentals
> Outline a brief description of your project.
> Live demo [_here_](https://www.example.com). <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [Now Platform overview](#now-platform-overview)
* [Now Platform User Interface](#now-platform-user-interface)
* [Get started with lists and filters](#getting-started-with-lists-and-filters)
* [Forms Overview](#forms-overview)
* [Task Overview](#task-overview)
* [Contact](#contact)


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

###### Get started with the Now Platform user interface

Identify the importance of the Now Platform user interface

Are you ready to start getting your hands on the Now Platform? Fasten your seatbelts and adjust your rear view mirror. David and Kristen are here to help begin your road trip.

Select play to drive home the importance of the features provided by the Now Platform user interface.

Find your way around the Now Platform user interface

Once you login to the ServiceNow Now Platform user interface with your user name and password, you are ready to begin. Start by taking a look around the main screen elements and functionality available in the Now Platform user interface. 

Select play to get acclimated to your new control center. Use the Fullscreen option on the video toolbar for better viewing.


###### Get started with the application navigator

Now that you have a feel for the Now Platform user interface, dive in a little deeper. Take a look at how the application navigator helps you find your way around ServiceNow. Just think of the application navigator as the steering wheel of your car.

Select play to learn how to chart your course with the application navigator. Use the Fullscreen option on the video toolbar for better viewing

## Get started with lists and filters

###### Identify the importance of lists and filters

How do you get the information you need quickly using ServiceNow? Your instructors, David and Kristen, are here to shed some light on how lists and filters can transform the way you work and save time. 

Select play to find out how lists and filters give you the power to sort, analyze, and view information in the Now Platform. You got this!

###### Explore the power of lists and filters

Lists and filters help manage the records in a ServiceNow table. This includes task-based records that track the flow of work to completion, such as incidents.

Ready to see lists and filters in action? Select play to explore the power of lists and filters in the Now Platform. Use the Fullscreen option on the video toolbar for better viewing.

###### Natural Language Query (NLQ)

The Natural Language Query allows you to filter the list data using natural language, instead of the condition builder.
As you type, auto-suggestions for text will appear so you can click the suggestion before typing the complete filter.
Select Ask, and you will see the filter applied to the breadcrumb.

The Natural Language Query can be activated by installing the Natural Language Query (com.snc.nlq) and Predictive Intelligence (com.glide.platform_ml) plugins. Administrators will be able to turn this feature off by using the list control. Each NLQ result will be contained to the table the list is populated with data (ex. Incident). 

To turn this feature off, navigate to sys_properties.list, search for *nlq under Name. For com.snc.listv2.nlq.lists.append_query, set the Value to false. 

To learn more about the NLQ and activation information, navigate to ServiceNow Product Documentation: Natural Language Query


## Forms Overview

Welcome to the Forms Overview! In addition to learning how to view and edit records in forms, this overview will provide information on how forms can be configured to target different groups. Upon completion of this course you will be able to:

- Demonstrate how forms are used to capture information of one record on a table
- Identify the components of the form user interface
- Adapt forms to your needs using form personalization 
- Create forms targeting different users or groups using form designer

###### Get started with forms

###### Identify the importance of forms

How do you capture and display the information of a ServiceNow record? With forms, of course. Hear a brief word from your instructors, David and Kristen, on how you can get involved in the development effort configuring forms, no matter your project role. 

Ready to start getting your awesome idea off the ground? Select play for the following video to get inspired and make it happen.

###### Begin with the basics of using forms

Want to learn more about personalizing, managing, and saving important information on your instance? You're in the right place! Pay close attention on how you can create, view, or modify specific records in data tables using forms.

Select play for detailed demonstrations on using form features and functions in the Now Platform. Use the Fullscreen option on the video toolbar for better viewing.

###### Form layout and design

###### Configure forms for different audiences


## Task overview

###### What is a ServiceNow task?

A task is any record that can be assigned or completed by a user in ServiceNow. Users create tasks and are notified as the task moves along a workflow. Tasks can be assigned to specific users or user groups.

###### Why use tasks?

The power (and value) of tasks are that they are repeatable processes across the enterprise. By defining tasks, users with similar issues (for example, no network access) can have their issue automatically assigned to the appropriate user and assignment group. This results in quicker resolution times and minimizes the possibility of human error.

Not convinced yet? Select each numbered step below to explore a normal workflow in which the task is an Incident (no network access) and the users are Fred and Donna.

###### Time to dive a little deeper

The Task table is one of ServiceNow’s core tables. It provides a series of standard fields available to other tables that define specific types of tasks (Incident, Problem, Change Request, etc.). In technical terms, these other tables extend the Task table.

- Approvals can be generated to a list of Approvers, either manually or automatically, according to approval rules. Approvals can be incorporated into workflows or can stand alone.

- Assignment rules can automatically assign tasks to users or groups, ensuring that tasks are handled by the most appropriate team members.

- Service Level Agreements can track the amount of time that a task has been open, to ensure that tasks are completed within an allotted time.

- Inactivity monitors ensure that tasks do not fall by the wayside by notifying users when tasks have been untouched for a predefined period of time.

- Workflow processes are specified by administrators and apply to tasks that meet certain conditions. After a task is created that meets the conditions, the workflow applies an automated process to the task.

###### Task assignment

There are four steps to assign tasks:

- Add users to groups
- Apply roles to groups
- Assign tasks to groups
- Assign tasks to users

###### Assignment rules

Assignment rules are used to automatically set a value in the Assigned to and/or Assignment group fields of a task record.

You can view assignment rules by navigating to the System Policy > Rules > Assignment module.

Create an assignment rule

Creating an assignment rule is a fairly straightforward process that can be done in a few minutes.

Select each numbered step below for more information on how to create an assignment rule.

###### Assignment rule criteria

An assignment rule must meet the following criteria to execute:

- The Task record has been created (or modified) and then saved on a form.  In the example you walked through above, a new Incident was created. Therefore, this criteria was met.

- The Task record must be unassigned (no values in the Assigned to or Assignment group fields). In the example above, the Assignment to and Assigned group fields were initially blank since a new record was created.

- The assignment rule is the first rule that matches the specified table and conditions. If more than one assignment rule matches the conditions, only the rule with the lowest Order value runs. Though not shown in the example above, the assignment rule had the lowest order value (100) for a Hardware Category Incident.

Additionally, assignment rules can be scripted, giving even more flexibility on the trigger and outcome.

###### Assignment lookup rules

Assignment lookup rules are another type of assignment rule. These rules only apply to incident records. They have fewer options than other assignment rules that can be applied to any task. They can be created by navigating to System Policy > Rules > Assignment Lookup Rules. 

If you look closely at Assignment Data Lookups, you can see that both Assignment Rules are displayed and Order values are 100. Even though the Order values are identical, this is not a problem because their Category and Subcategory conditions are different (Network - VPN vs Hardware).

###### Predictive Intelligence

Predictive Intelligence uses machine-learning algorithms to determine field values during record creation. Existing data records are required to "train" machine-learning to make effective decisions.

This results in improved efficiency and quality and reduces cost by:

- Reducing the amount of time spent resolving tasks

- Reducing the number of interactions required to resolve tasks

- Reducing the number of potential human errors that could occur while categorizing and assigning work

###### Visual Task Boards

Use Visual Task Boards to collaborate on tasks in real-time with group members, create personal to-do lists, and more. 

Visual Task Boards allow you to:


- Manage your tasks through a visual, drag-and-drop interface

- Identify process bottlenecks at a glance

- Track activity to view updates all in one place

There are three types of Visual Task Boards: Guided, Flexible, and Freeform.

- Guided boards can be created from a list and use the values of a specified field (e.g. State) as lanes. Tasks in the list are updated when cards are edited or change lanes on the Visual Task Board.

- Flexible boards are also created from a list, but lane changes do not update underlying task data.

- Freeform boards can act as your personal organizer to manage individual tasks of any kind. Lane changes do not update underlying task data.

Elements of a Visual Task Board

Visual Task Boards are displayed graphically as lanes and cards, and provide a landing page to view and organize work in ServiceNow. While Visual Task Boards may vary in their exact configuration, there are four elements common to each type.

- Taskboard Tools

- Quick Panel

- Lanes

- Cards

Select each marker below to learn more about each Visual Task Board element.

###### Taskboard tools

Taskboard tools are a critical part of a Visual Task Board. Take the time now to get familiar with the functionality they provided. 

###### - Guided Visual Task Boards

The lanes of Guided Visual Task Boards are based on the predefined values of a specific reference or choice field for a task. For example, the Guided board below was based on the Assigned To field for change request tasks. Therefore, its lanes correspond to specific users assigned to the change requests. Records in that list, which appear as cards, are modified when you edit cards or change lanes in a Guided board.

###### - Flexible Visual Task Boards

Flexible Visual Task Boards are also based on specified fields from tasks. For example, the Flexible board below was based on the Number field for incidents. However, since Number is not a reference or choice field with predefined values, a Flexible board is created with the default lanes shown here. Records in the list, which appear here by default as cards in the To Do lane, are not modified when you edit cards or change lanes in a Flexible board.

###### - Freeform Visual Task Board

Freeform Visual Task Boards are just what its name implies, freeform. Since it is not based on a record list, you can add task records and configure it however you want. The default lanes are the same as a Flexible board, but since it was not built from a record list, the lanes do not have any cards in them yet. You would add the cards yourself.


















## Contact
Created by [@Yahshemi](https://github.com/Yahshemi/) - feel free to contact me!
