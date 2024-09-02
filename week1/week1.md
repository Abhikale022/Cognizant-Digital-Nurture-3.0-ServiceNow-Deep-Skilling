DIGITAL NURTURE 3.0 SERVICENOW DEEPSKILLING WEEK-1

1.Define what ServiceNow is and explain its purpose in IT service management.

In IT service management (ITSM), ServiceNow's main purpose is to streamline and automate the processes involved in delivering IT services. Companies use ServiceNow to handle things like tracking customer requests, solving technical problems, and ensuring that IT systems are working properly. This makes IT teams more efficient and helps businesses deliver better service to their users.
<hr>
2.ServiceNow platform overview:

a. Now Platform:
> The Now Platform is the foundation of ServiceNow.It provides the core technology that powers all of ServiceNow’s products, allowing businesses to create custom apps, automate processes, and manage their IT services all in one place.

b. Platform User Interfaces:
These are the different ways users interact with the Now Platform. It includes:
> Classic Interface: The traditional way of navigating through ServiceNow, using menus and lists.
> Service Portal: A more modern, user-friendly interface that lets users easily submit requests and track their status.
> Mobile App: A version of ServiceNow that you can use on your smartphone or tablet, so you can work on the go.

c. Applications and Workflows:
> Applications: These are specific tools or modules within ServiceNow that handle different tasks, like managing IT services, handling customer requests, or managing HR processes. Think of each application as a separate tool in your toolbox, each designed for a specific job.
> Workflows: These are the step-by-step processes that automate tasks within the applications. For example, a workflow might automatically assign a support ticket to the right team member and notify them when it’s time to take action.

d. Role-Based Access:
> This is a security feature that controls what different users can see and do in ServiceNow. Depending on your role (like admin, user, or manager), you get access to certain parts of the platform. For example, an admin might have access to everything, while a regular user might only be able to see and interact with their own tasks.

e. User Authentication:
> User authentication is how ServiceNow makes sure that only the right people can access the platform. When you log in, ServiceNow checks your username and password (or other security methods like two-factor authentication) to verify your identity. This keeps unauthorized users out and protects sensitive information.

<hr>

3.ServiceNow User Interface Overview

The ServiceNow platform user interface is designed to be user-friendly, with key elements like the Application Navigator for easy access to different applications, Favorites for quick access to frequently used features, and History for tracking recently viewed items. Global Search allows users to find anything across the platform quickly, while Connect Chat facilitates real-time communication within the platform. Contextual Help provides on-the-spot assistance based on what you're doing. ACLs (Access Control Lists) define what data users can see and interact with, UI Policies manage the behavior of fields on forms, Business Rules are server-side scripts that execute based on database actions, and Client Scripting allows for customization of the user experience directly in the browser. Together, these features make navigating and using ServiceNow intuitive and customizable.The User Menu Provides tools like Profile, Impersonate User, Elevate roles, logout.

1. Cloud-Based Infrastructure:
ServiceNow operates on a cloud-based infrastructure. This means that the platform is hosted on remote servers rather than on local hardware in your office. The advantage of this setup is that you can access ServiceNow from anywhere with an internet connection, and the cloud provider takes care of things like server maintenance, backups, and updates.

2. Multi-Tenant Architecture:
ServiceNow uses a multi-tenant architecture, meaning multiple customers share the same physical infrastructure but have isolated environments (instances). Each instance is like your own private workspace, where you can customize your applications and data without worrying about interference from others.

3. ServiceNow Data Centers:
ServiceNow’s services are hosted in secure data centers around the world. These data centers are highly reliable and designed to ensure that the platform is always available, even if something goes wrong in one location. This setup provides high availability and disaster recovery capabilities.

4. Integration Capabilities:
ServiceNow can integrate with other systems and tools you’re already using. This is made possible through APIs (Application Programming Interfaces) and connectors that allow different software to communicate and work together seamlessly. This means you can pull in data from other systems or push ServiceNow data to other tools as needed.


5. Instance Management:
Each customer has a unique ServiceNow instance, which can be customized and configured to meet specific business needs. ServiceNow handles the management of these instances, including updates and patches, ensuring that your environment stays up-to-date without downtime.
<hr>

4.ServiceNow Branding Overview
   
ServiceNow's branding tools allow organizations to customize the platform to reflect their company's identity. 
The Company Guided Setup helps businesses configure ServiceNow with their specific branding elements, such as logos, colors, and themes, ensuring a consistent look and feel across the platform. 
The ServiceNow Portal provides a user-friendly, web-based interface where users can access services and resources, and it can be branded to match the company's style. The UI Builder is a powerful tool that lets you create and customize user interfaces within ServiceNow, offering a drag-and-drop experience to design pages and layouts that align with your brand’s aesthetic, without needing deep coding knowledge. Together, these tools ensure that the ServiceNow platform not only functions well but also visually aligns with the company’s brand.
<hr>
5.ServiceNow Lists and Filters

The ServiceNow List View interface is where users can see and manage records, like a spreadsheet or a table. This interface follows a standard template, meaning it has a consistent layout across the platform, making it easy to navigate and interact with. List Controls are options at the top of the list that allow you to do things like sort, group, and manage columns. You can apply filter conditions to narrow down the records you're viewing, which is like setting search criteria to find exactly what you need. Finally, the Refresh List button lets you update the list to see the most current information, ensuring you're always working with up-to-date data.
<hr>
6.Forms in ServiceNow

In ServiceNow, Forms are used to input, view, and edit individual records. The Standard Layout of a form typically includes a header, body, and footer, with Form Field Types such as text boxes, checkboxes, and dropdowns to capture different kinds of information. When working on a form, you can save changes using the Save button, or use Insert to create a new record and return to the list, while Insert & Stay creates a new record but keeps you on the form. Form Sections help organize fields into logical groups, and Related Lists show connected records like tasks or approvals. Formatters add special components like activity logs or user information. Form Views control which fields and sections are visible, and you can customize this with Form Personalization. You can also attach files using Adding Attachments and speed up form filling with Form Templates. For further customization, Creating & Editing Views allows you to define how forms appear to different users or roles.
<hr>
7.A Hands-on ServiceNow Tool Demo

When logging in to ServiceNow, users are greeted by the Next Experience UI, which offers a modern, intuitive interface. The Navigation Bar at the top provides quick access to key features like settings and notifications. The Application Navigator on the left is where users find and access various ServiceNow applications, which are tools for managing different tasks within the platform. The ServiceNow Store is like an app store, offering additional applications and integrations that can be added to the platform. For learning and skill development, ServiceNow Application Training and Certifications provide courses and credentials.

Working with Lists 
and Forms is a core part of using ServiceNow, where List Views display multiple records in a table format, and Form Views show details of individual records. Knowledge Management in ServiceNow helps organizations create, share, and manage knowledge articles. Finally, the ServiceNow Database is the backbone of the platform, storing all the data and information that powers these applications and features.
<hr>
8.Introduction to Importing Data in ServiceNow

a.Setup Import Set Table: Create or identify the Import Set Table where data will be initially stored.

b.Define Transform Map: Create and configure a Transform Map to map fields from the Import Set Table to the target table.

c.Write Transform Scripts: Add any necessary Transform Scripts to handle custom logic and data manipulation.

d.Use Import Set API: Utilize the Import Set API to import data from external sources into the Import Set Table.

e.Run Transform: Execute the Transform Map to move data from the Import Set Table to the target table, applying any Transform Scripts in the process.

Using Import Sets for REST integration in ServiceNow provides a robust solution for importing and transforming data from various external sources. By leveraging Transform Maps and Transform Scripts, you can ensure that data is accurately and efficiently mapped to your ServiceNow tables. The Import Set API further enhances this process by allowing seamless integration through RESTful web services. By following these best practices and utilizing the tools provided by ServiceNow, you can achieve a streamlined and effective data import process.
<hr>
9.Creating a Data Source in ServiceNow

Data Sources:
A Data Source in ServiceNow represents an external data provider or system.
It allows you to load data from external sources into ServiceNow.
Common examples include databases, web services, and files.

Creating a Data Source Record:
Navigate to “System Definition” > “Data Sources” in ServiceNow.
Click “New” to create a new Data Source record.

Configure the following details:

>Name: Give your Data Source a descriptive name.

>Type: Choose the appropriate type (e.g., JDBC, REST, SOAP, etc.).

>Connection Details: Provide connection information (URL, credentials, etc.).

>Authentication: Set up authentication if required.

>Import Set Table: Specify the target Import Set table where data will be loaded.

Importing Data:
Once the Data Source is set up, create an Import Set Table.
Map fields between the Data Source and the Import Set Table using a Transform Map.
Schedule data imports or trigger them manually.
<hr>
10.Understanding Import Sets in ServiceNow

Import sets in ServiceNow are a powerful tool for importing data from various sources and transforming it to fit into target tables. Here’s a step-by-step overview of how they work:

Creating Import Sets
Load Data:
Navigate to System Import Sets > Load Data.

Choose the source of your data (e.g., file, JDBC, etc.).

Define the import set table where the data will be temporarily stored.
Create Transform Maps:

Go to System Import Sets > Administration > Transform Maps.

Click New to create a new transform map.

Provide a name for the transform map and select the source import set table and the target table in ServiceNow.

Transforming Data
Field Mapping:

Define field mappings by specifying the source field from the import set table and the target field in the ServiceNow table.
Use the Auto Map Matching Fields feature to automatically map fields with the same name.

Transform Scripts:

Use server-side JavaScript to manipulate data during the transformation process.

Types of transform scripts include:

onBefore: Executed before any record is processed.

onStart: Executed at the start of the transformation.

onAfter: Executed after each record is processed.

onComplete: Executed after all records have been processed.
<hr>
11.ServiceNow Transform Maps & Field Maps

Importing Data

Load Data:

Navigate to System Import Sets > Load Data.

Choose the data source (e.g., CSV file, Excel file, JDBC, etc.).

Define the import set table where the data will be temporarily stored.

Transforming Data

Create Transform Maps:

Go to System Import Sets > Administration > Transform Maps.

Click New to create a new transform map.

Provide a name for the transform map and select the source import set table and the target table in ServiceNow.

Field Mapping:

Define field mappings by specifying the source field from the import set table and the target field in the ServiceNow table.

Use the Auto Map Matching Fields feature to automatically map fields with the same name.

Mapping Data

Run Transform:

Once the transform map is set up, run the transform to move data from the import set table to the target table.

Navigate to System Import Sets > Run Transform.

Select the import set and the transform map, then execute the transform.

Review and Validate:

After the transformation, review the data in the target table to ensure it has been correctly imported and mapped.

Use the Import Set Table to check for any errors or discrepancies.
<hr>

12.ServiceNow Incident Management Tutorial and Task Administration

Incident Management

Incident Creation: Users can create incidents to report issues or disruptions in service.

Incident Lifecycle: Incidents go through various stages such as New, In Progress, Resolved, and Closed.

SLA Management: Service Level Agreements (SLAs) ensure incidents are resolved within a specified timeframe.

Problem Management

Problem Identification: Problems are identified from recurring incidents or proactive analysis.

Root Cause Analysis: Tools like the 5 Whys and Fishbone Diagram help in identifying the root cause.

Problem Resolution: Solutions are implemented to prevent future incidents.

Change Management

Change Requests: Users can submit change requests for modifications to the IT environment.

Change Approval: Changes go through an approval process involving CAB (Change Advisory Board).

Change Implementation: Approved changes are implemented and monitored for success.

Task Creation

Manual Task Creation: Tasks can be manually created and assigned to users or groups.

Automated Task Creation: Tasks can be automatically generated based on predefined rules or workflows.

Task Assignment Rules

Assignment Rules: Define criteria for automatically assigning tasks to the appropriate user or group.

Skills-Based Routing: Tasks are assigned based on the skills required and the availability of resources.

Workload Balancing: Ensures tasks are evenly distributed among team members.

Task Collaboration

Comments and Work Notes: Team members can add comments and work notes to tasks for better collaboration.

Activity Stream: Provides a real-time feed of all updates and changes to a task.

Notifications: Users receive notifications for task updates, assignments, and due dates.

Visual Task Boards

Kanban Boards: Visualize tasks in a Kanban-style board, allowing for easy tracking of progress.

Drag-and-Drop: Tasks can be moved between different stages by dragging and dropping.

Customizable Lanes: Lanes can be customized to represent different stages of a workflow.

Real-Time Updates: Boards are updated in real-time, ensuring all team members have the latest information.
<hr>
13.ServiceNow Reporting Tutorial

ServiceNow offers robust reporting capabilities that allow users to create, manage, and share various types of reports, including list, bar, pie, and line charts. Users can easily generate reports using the Report Designer, which provides a guided flow to configure, preview, and edit reports. These reports can be shared with users or groups through dashboards, service portals, or by publishing them to URLs. Additionally, ServiceNow supports data visualization with customizable dashboards, enabling real-time insights and performance monitoring.

In addition to basic reporting, ServiceNow also supports advanced reporting features such as drill-down capabilities, which allow users to explore data in greater detail by clicking on specific report elements. Users can schedule reports to run at regular intervals and distribute them via email or export them in various formats like PDF, Excel, or CSV. Furthermore, ServiceNow’s Performance Analytics module enhances reporting by providing key performance indicators (KPIs) and trend analysis, enabling organizations to track progress against goals and make data-driven decisions.

<hr>
14.What is Low Code No Code Development?

Low Code/No Code (LC/NC) software development allows users to create applications with minimal or no coding knowledge, using visual interfaces and pre-built templates. This approach works by enabling "citizen developers" to drag and drop components to build applications, significantly speeding up the development process. The pros include faster development times, lower costs, increased accessibility for non-technical users, and enhanced collaboration. However, it also has cons such as limited customization, potential vendor lock-in, security concerns, and performance limitations. Career opportunities in LC/NC development are growing, with roles such as low-code developers, business analysts, and citizen developers becoming more prominent. This field offers high job satisfaction and the chance to work on innovative projects.


