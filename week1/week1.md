DIGITAL NURTURE 3.0 SERVICENOW DEEPSKILLING WEEK-1

Define what ServiceNow is and explain its purpose in IT service management.

In IT service management (ITSM), ServiceNow's main purpose is to streamline and automate the processes involved in delivering IT services. Companies use ServiceNow to handle things like tracking customer requests, solving technical problems, and ensuring that IT systems are working properly. This makes IT teams more efficient and helps businesses deliver better service to their users.
<hr>
ServiceNow platform overview:

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





ServiceNow User Interface Overview

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

ServiceNow Branding Overview
   
ServiceNow's branding tools allow organizations to customize the platform to reflect their company's identity. 
The Company Guided Setup helps businesses configure ServiceNow with their specific branding elements, such as logos, colors, and themes, ensuring a consistent look and feel across the platform. 
The ServiceNow Portal provides a user-friendly, web-based interface where users can access services and resources, and it can be branded to match the company's style. The UI Builder is a powerful tool that lets you create and customize user interfaces within ServiceNow, offering a drag-and-drop experience to design pages and layouts that align with your brand’s aesthetic, without needing deep coding knowledge. Together, these tools ensure that the ServiceNow platform not only functions well but also visually aligns with the company’s brand.
<hr>
ServiceNow Lists and Filters

The ServiceNow List View interface is where users can see and manage records, like a spreadsheet or a table. This interface follows a standard template, meaning it has a consistent layout across the platform, making it easy to navigate and interact with. List Controls are options at the top of the list that allow you to do things like sort, group, and manage columns. You can apply filter conditions to narrow down the records you're viewing, which is like setting search criteria to find exactly what you need. Finally, the Refresh List button lets you update the list to see the most current information, ensuring you're always working with up-to-date data.
<hr>
Forms in ServiceNow

In ServiceNow, Forms are used to input, view, and edit individual records. The Standard Layout of a form typically includes a header, body, and footer, with Form Field Types such as text boxes, checkboxes, and dropdowns to capture different kinds of information. When working on a form, you can save changes using the Save button, or use Insert to create a new record and return to the list, while Insert & Stay creates a new record but keeps you on the form. Form Sections help organize fields into logical groups, and Related Lists show connected records like tasks or approvals. Formatters add special components like activity logs or user information. Form Views control which fields and sections are visible, and you can customize this with Form Personalization. You can also attach files using Adding Attachments and speed up form filling with Form Templates. For further customization, Creating & Editing Views allows you to define how forms appear to different users or roles.
<hr>
A Hands-on ServiceNow Tool Demo

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
Creating a Data Source in ServiceNow

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
Understanding Import Sets in ServiceNow
