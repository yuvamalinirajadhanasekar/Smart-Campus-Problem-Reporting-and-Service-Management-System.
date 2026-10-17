# Smart-Campus-Problem-Reporting-and-Service-Management-System.
This project is a web application that helps students and staff manage campus problems and services in one place. It combines issue reporting, lost and found, and digital queue management.
1. Project Overview
The Smart Campus Problem Reporting and Service Management System is a web-based application designed to improve the management of everyday campus problems and services. Students and staff often face difficulties reporting maintenance issues, finding lost belongings, and accessing college services efficiently.
This project proposes a centralized platform that combines issue reporting, lost-and-found management, digital queue tokens, request status tracking, and an administrator dashboard. Instead of depending entirely on verbal communication, WhatsApp messages, or physical queues, users can access these services through a common website.
The main aim is to make campus services more organized, accessible, and transparent.
2. Problem Statement
In many educational institutions, campus maintenance complaints and service requests are handled through manual or disconnected communication methods. Students may report damaged classroom equipment verbally, communicate lost items through messages, or wait in long queues to access administrative services.
These processes can lead to delays, scattered information, duplicate complaints, and difficulties tracking the progress of requests. Students may also need to contact staff repeatedly to know whether their problems have been addressed.
Therefore, a centralized web platform is proposed to simplify complaint submission, organize lost-and-found information, manage service queues, and provide better visibility into request status.
Research goal: To develop a centralized web platform that makes campus issue reporting and service access faster, organized, and transparent.
3. Objectives
The primary objective is to simplify campus problem reporting and service management through a single web application.
- Campus issue reporting: Enable students and staff to submit maintenance complaints, including details about the problem and its location.
- Lost-and-found management: Allow users to register lost or found items and view relevant information to help recover belongings.
- Digital queue management: Generate tokens for supported campus services so users can access an organized queue system.
- Request status tracking: Allow users to check the progress of submitted complaints and service requests.
- Improved communication: Provide a common platform through which students, staff, and administrators can coordinate campus services.
These objectives focus on reducing manual effort and making campus service processes easier to manage.
4. Scope
The scope defines the major functions covered by the proposed application.
Centralized issue reporting: Users can submit campus maintenance complaints through a common interface rather than relying only on verbal communication or separate messaging channels.
Digital lost-and-found management: Lost and found item information can be recorded and displayed in an organized manner, making it easier for users to search for belongings.
Online token generation: Users can obtain digital tokens for supported campus services. This can help organize service requests and reduce the need to wait without knowing the queue position.
Request status tracking: Users can check the current status of their requests, improving transparency and reducing the need for repeated follow-ups.
Communication and administration: The platform brings students, staff, and administrators together to support more organized campus service management.
The scope described in the project focuses on these core functions. Additional features would depend on future development.
5. Technologies Used
The project identifies HTML, CSS, Bootstrap, and JavaScript as its main frontend technologies.
HTML — HyperText Markup Language
HTML provides the basic structure of the website. It is used to create headings, forms, text fields, buttons, navigation menus, and tables.
For example, the issue-reporting page can contain fields for the complaint title, problem description, and location, along with a submit button.
CSS — Cascading Style Sheets
CSS controls the appearance and layout of web pages. It can define colours, fonts, spacing, borders, button styles, and dashboard layouts.
For example, CSS can help distinguish pending complaints from resolved complaints through different visual styles.
Bootstrap
Bootstrap is a frontend framework that provides reusable components and responsive layout tools. It helps create consistent forms, navigation bars, buttons, and dashboard cards.
It also helps the website adapt to different screen sizes, such as laptops, tablets, and mobile phones.
JavaScript
JavaScript adds interactive behaviour to the website. It can validate form inputs, respond to button clicks, display messages, and support client-side queue-token generation.
For example, it can check that required complaint fields are filled before allowing the user to submit a form.
These technologies mainly cover the frontend. A complete multi-user application would also need an appropriate backend and data-storage mechanism, but the PDF does not identify which backend or database technologies have been selected.
6. Existing System
The existing system refers to the manual or disconnected approaches used to report campus problems and access services.
Students may communicate maintenance complaints verbally or through WhatsApp. Lost-and-found information may be shared through informal messages, while some campus services require students to visit an office and wait in a physical queue.
Although these approaches can be convenient for simple situations, they become difficult to manage when many people submit requests simultaneously.
The major limitations are:
- Time-consuming processes: Users may need to contact staff repeatedly or visit offices in person.
- Difficult request tracking: Students may not know whether a complaint has been received, assigned, or resolved.
- Scattered information: Details are distributed across different conversations and communication channels.
- Duplicate complaints: The same issue may be reported multiple times when users cannot see existing requests.
- Unnecessary waiting: Students may spend time waiting for services without an organized digital token system.
These limitations explain the need for a more centralized and organized approach.
7. Proposed System
The proposed system is a centralized web application that combines several campus services in one place.
Issue reporting: Users can submit maintenance problems with relevant descriptions and locations. The application can organize complaints so administrators or responsible staff can review them.
Lost-and-found management: Users can record information about lost or found belongings. Other users can view these details to help identify and recover items.
Digital queue management: The system can generate tokens for supported services. A token-based process can help organize the order in which users receive service.
Request status tracking: Submitted requests can be associated with statuses such as Pending, In Progress, and Resolved. These are suggested example statuses for implementation, not statuses explicitly listed in the PDF.
Admin management dashboard: Administrators can access a central interface to review requests, manage information, and update service records, depending on the permissions implemented.
The expected outcome is faster reporting, easier recovery of lost items, reduced waiting, and better campus service management. These are intended benefits rather than measured results reported in the PDF.
8. System Concept
The concept is to replace disconnected manual campus service processes with a common web-based platform.
The system connects three main user groups:
Students: Students can submit maintenance complaints, report lost belongings, search for found items, and access digital queue services.
Staff: Staff members can review or handle relevant complaints and service requests according to their responsibilities.
Administrators: Administrators can oversee the platform, manage requests, and coordinate service operations.
For example, if a student notices a broken classroom fan, the student can submit a complaint through the website. The responsible staff member can review the request and update its progress. The student can then check the status online instead of repeatedly asking for updates.
Similarly, if a student loses an ID card, the lost-and-found section can provide an organized way to share and search for item information.
This concept improves coordination by providing a common interface for different campus activities.
9. System Architecture
The architecture explains how the different parts of a web application work together. The PDF includes a system-architecture section, but its detailed diagram labels are not available in the extracted text. The following describes a suitable architecture based on the proposed project functions.
Users
Students, staff and administrators
          
Frontend
HTML, CSS, Bootstrap and JavaScript
Displays pages, forms and dashboards

Backend / Application Logic
Processes requests and applies access permissions

Database
Stores users, complaints, item records, tokens and request statuses


The frontend is the part users interact with. The backend processes requests, applies business rules, and communicates with the database. The database maintains the information required for the application to operate.
For example, when a complaint is submitted, the frontend collects the information, the backend validates and processes it, and the database stores the record. When the student checks the complaint later, the application retrieves the latest status.
The specific backend and database are not named in the PDF, so their selection should be based on the actual implementation.
10. Modules and Implementation
The application can be divided into modules, with each module responsible for a particular function.
Module	Detailed function
Login	Provides a user entry point and, in a complete implementation, verifies identity and permissions.
Student Dashboard	Presents the available services and helps users access their requests.
Issue Reporting	Collects complaint details and allows users to submit maintenance issues.
Lost & Found	Records lost and found item information and displays relevant records.
Queue Management	Generates digital tokens and organizes service requests in a queue.
Admin Dashboard	Allows authorized administrators to review requests and manage their status.
Implementation involves creating the user interface, connecting the pages, adding the required functionality, and ensuring that the information is processed correctly.
For instance, the issue-reporting module should accept valid complaint details and provide appropriate feedback after submission. In a fully functional system, the complaint should be stored so the relevant user and authorized staff can access it later.
Testing should verify that forms work correctly, information is saved and retrieved properly, token generation behaves as expected, and unauthorized users cannot access administrative functions.
11. Expected Results and Conclusion
The project is expected to make everyday campus operations more organized by bringing complaint reporting, lost-and-found management, and digital queue services into one application.
The anticipated benefits include:
- Easier submission and tracking of maintenance complaints.
- Better organization of lost-and-found information.
- More structured access to campus services through digital tokens.
- Improved visibility into request progress.
- Better communication between students, staff, and administrators.
- Less dependence on scattered manual communication.
In conclusion, the Smart Campus Problem Reporting and Service Management System proposes a centralized digital solution for common campus service challenges. By combining the major functions in one web application, it aims to improve accessibility, organization, and transparency in campus management. Its actual effectiveness would depend on successful implementation, reliable data storage, appropriate access control, and testing with users.

