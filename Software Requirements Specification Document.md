# SENG 3130 - Final Report - Volunteer Management System

## Software Requirements Specification Document
 
### 1. Introduction
#### 1.1. Purpose
This SRS describes the functional requirements for the first version of the Volunteer Management system. This document provides the functionalities of the system for users and staff. This version contains the basic functions for users. This document describes the purpose of the system, the intended use for and other information that may be important towards the user.

#### 1.2. Document Conventions
There are no specific typographical conventions used within this SRS.

#### 1.3. Intended Audience and Reading Suggestions
The intended audience for this document is for the users using the system and staff managing the system. Each section of the document contains information about the system, features, requirements and quality attributes, and it is organized by basic information of the system to the different aspects of the system. Best reading sequence when looking at this document would be looking at section 2 which provides the basic information of the system, then to section 3 which shows the system features, then moving to section 6 listing the attributes of the system. After reviewing those sections, continue through either section 4, 5 or 7 which each section discusses about different types of requirements for the system and end it by reviewing the appendix.

#### 1.4. Product Scope
* Refer to Vision and Scope Document.
* The volunteer management system will be able to connect with the background check system to increase the number of volunteers available and reduce shortages.
* The volunteer management system provides the following benefits:
   * It tracks the number of senior cases.
   * It keeps a record of the number of volunteers available each day.
   * It assigns volunteers to seniors with the help request.
   * It defines some incentives for volunteers to use the system

#### 1.5. References
[1] T. Aitken, L. Aitken, B. Breithaupt, “Vision and Scope Document for Volunteer Management System.” Group 1, Version 1: Created (September 23, 2022). </br>
[2] T. Aitken, L. Aitken, B. Breithaupt, “User Requirements Document for Volunteer Management System.” Group 1, Version 1: Created (October 17, 2022).


### 2. Overall Description
#### 2.1. Product Perspective
Our Volunteer Management System is a standalone self contained system. The need for this system is brought about by the decline in volunteers within our community and the rising demand for said volunteers to help the elderly community.

<div align="center"> Figure 2-1: Context Diagram </div>

#### 2.2. Product Functions
<div align="center"> Figure 2-2: Feature Tree </div>

#### 2.3. User Classes and Characteristics

| User Class and Type | Description |
| --- | --- |
| `Volunteers: Direct and Favored ` | Should enter their name, phone number, address and extra details to the system to be reviewed by the administrators.|
| `Seniors/Elders: Direct and Favored` | Should report their needs for social support.|
| `System Administrators: Direct and Favored` | Receive daily reports with the forecasted number of cases during the next week.</br> For example, I can reassign volunteers to higher severe cases. I should also see any new requests from the School Administrators who request volunteers to teach the students. </br> Send volunteer information to the background check system after the system administrator product champion has looked over the new volunteers. </br> Should be able to verify the educational certificates of volunteers who are required to teach kids.|
| `Mayor/Staff: Direct and favored` | Receive information on seniors and create profiles for the seniors on the system.|
| `Background Check System: Indirect and favored` | Should process 1K background checks per hour. The problem is that the system process includes a manual step to get approval from the police officers, so it only works during working hours.|
| `Sponsors: Indirect and Ignored` | Fund the volunteer management system in exchange for volunteer help.|
| `Subject Matter Expert: Indirect and Favored` | Give advice on the subject matter for the volunteer management system.|
| `Senior People Champion: Indirect and Favored` | Should gather senior’s information over the phone and send it to the staff.|
| `System Administrator Product Champion: Indirect and Favored` | Check over newly registered volunteers and do initial screening. If the profile looks good, the administrators are able to send the information of the volunteers to the background check system.|

#### 2.4. Operating Environment
OE-1: The Volunteer Management system will be a phone application on both android devices and IOS devices.</br>
OE-2: The Volunteer Management system will be on the most up-to-date operating system for each device system.</br>
OE-3: The Volunteer Management system must work with both operating systems and firewalls for each device system.

#### 2.5. Design and Implementation Constraints
CO-1: The Volunteer Management system development on both android devices and IOS devices simultaneously.</br>
CO-2: Coordinate information with the government for acceptance with their systems for police checks for new users.</br>
CO-3: The system requires a reduced amount of memory available for the user as its for android and IOS devices.

#### 2.6. User Documentation
UD-1: There will be a help call center for seniors who are having troubles and require help when trying to register with the Volunteer Management system.</br>
UD-2: There will be an in app tutorial to show how to use the Volunteer Management system to help seniors and new volunteers on how to request or accept help.

#### 2.7. Assumptions and Dependencies
A1.1: We are assuming that the background check system to reduce the time it takes for background checks will be done in the few months that were stated, meaning that it will be done when we are ready to roll out version 1.0 of the management software.</br>
A2.1: We are assuming that this program will reduce the crime rate in the downtown area leading to an increase in sales and visitation to the downtown core</br>
A3.1: We are assuming that in a future release the volunteer management system will expand on other volunteer needs such as after school activities for children.</br>

D1.1: We are dependent on the speed of the rollout for the police background check improvement. Without it, we will be stuck to some timelines that we cannot improve on quickly.</br>
D2.1: We are dependent on the senior help center to get senior information and request on to the volunteer management system.

### 3. External Interface Requirements
#### 3.1. User Interfaces
UI-1: The Volunteer Management system will have 4 main sections that include Settings, Personal Information, Browse and</br>
UI-2: The Volunteer Management system browse section will display recommended seniors that fit with the volunteer’s skills.</br>
UI-3: Clicking on a Senior in the browse section will show all the details about the seniors as well as the service needed.</br>
UI-4: Clicking on the personal information will show all the details about the volunteer and their experiences and skills.

#### 3.2. Hardware Interfaces
HI-1: The Volunteer Management system will be supported on android devices and IOS devices.

#### 3.3. Software Interfaces
Volunteer Management System (VMS)</br>
SI-1: Volunteer Listing System
* SI-1.1: The VMS shall transmit the list of volunteers to the volunteer listing system through a programmatic interface.
* SI-1.2: The VMS shall search the volunteer listing system to determine whether a request for a volunteer is needed.
* SI-1.3: The VMS will be notified by the volunteer listing system if there is going to be a shortage of volunteers in the future.</br>

SI-2: Volunteer Registar System
* SI-2.1: The VMS shall communicate with the volunteer register system through a programmatic interface for the following operations:
* SI-2.2: To allow volunteers to register and unregister from the VMS.
* SI-2.3: To inquire if a volunteer is eligible to register.</br>

#### 3.4. Communications Interfaces
CI-1: The Volunteer Management system will send an email, text message, phone call or notification to volunteers confirming their acceptance to help.</br>
CI-2: The Volunteer Management system will send an email, text message or phone call to seniors telling them that a volunteer has accepted their request.</br>
CI-3: The Volunteer Management system will send an email, text message or notification to volunteers telling them that they approve of using the system.</br>
CI-4: : The Volunteer Management system will send an email, text message or notification to
volunteers telling them that they disapprove of using the system.

### 4. System Features
#### 4.1. Create New Volunteer
#### 4.1.1. Description
A volunteer who wants to be registered onto the system can apply as a volunteer and be approved by the system administration and background check system. A volunteer can update their information and unregister from the system.

#### 4.1.2. Functional Requirement 1
New.Volunteer | Create New Volunteer
* .Register: The system administrator shall add the volunteer to the volunteer management system.
* .Update: The volunteer can update their information about themselves.
* .Delete: The volunteer can unregister from the system if they do not want to be a volunteer anymore.

#### 4.1.3. Functional Requirement 2
Approve.Volunteer | Approve New Volunteer
* .Approve: The system administrator sends information of the volunteer to the background check system.
* .Not Approve: If the background check system finds any criminal records or negative information, it will send the information back to the system administrator and will deny the volunteer access.

#### 4.2. Assign Volunteer
#### 4.2.1. Description
A volunteer who wants to pick a senior they want to help can choose for themselves. A senior who also wants to pick volunteers that they find helpful can choose who can volunteer for them. If a volunteer or senior that cannot find a service or receive service in a certain amount of time, the system operators running the Volunteer Management system will choose for them.

#### 4.2.2. Functional Requirement 1
Assign.Volunteer | Assign Volunteer
* .Volunteer: Seniors able to choose Volunteers.
* .Senior: Volunteers able to help chosen Senior.
* .Assign: If a senior cannot find a volunteer or a volunteer cannot find a senior, the system operators will assign seniors or volunteers for them.

#### 4.3. Generate Daily Report
#### 4.3.1. Description
The system administrator would generate a daily report based on the information and data collected from the Volunteer management system. The system administrator would then send the report to the mayor and staff to show them how the volunteer management system is performing.

#### 4.3.2. Functional Requirement 1
Create.Report | Creating the daily report
* .Create: The system administrator shall create a report based off the information collected from the volunteer management system.
* .Date: The report shall be created daily by the system administrator.

#### 4.3.3. Functional Requirement 2
Send.Report | Sending the daily report
* .Send: The system administrator shall send the daily report to the mayor and staff.
* .Date: The mayor and staff should receive the report once everyday from the system administrator.

### 5. Other Nonfunctional Requirements
#### 5.1. Performance Requirements
PER-1: The system shall be able to track 60% of senior cases and support up to 85% of cases. </br>
PER-2: The system shall reduce the last-minute volunteer shortages to two times per year.</br>
PER-3: The system shall display forecast the needed cases ahead of time by one week in advance.</br>
PER-4: The system shall display confirmation messages to volunteers with an average of 4 seconds and a maximum of 60 seconds after the volunteer submits information to the system.</br>
PER-5: The system shall be able to process information very quickly.

#### 5.2. Safety Requirements
SAF-1: The user shall be able to log out of the system to protect personal information, to log back in refer to SEC-1.

#### 5.3. Security Requirements
SEC-1: The system shall have a two-step verification for volunteers to log on to protect volunteer information and access from unwanted users.</br>
SEC-2: The list of volunteer information shall only be authorized for view by people who work for the system administrator and no outside users, refer to BR-1.</br>
SEC-3: The system shall only allow assigned volunteers to view information.

#### 5.4. Software Quality Attributes
SQA-1: The availability of the Volunteer Management system should
* be at least 95% available to all users except for when the system is under maintenance 2 times per year.
* be accessible on different operating systems.

SQA-2: The interoperability of the Volunteer Management system should be able to exchange information with the Background check system and make use of the information given back.</br>
SQA-3: The usability of the Volunteer Management system should be easy to use and easy to understand in terms of both volunteers and seniors.</br>
SQA-4: The maintainability of the Volunteer Management system should be able to maintain the number of volunteers with the number of seniors requests.</br>
SQA-5: The integrity of the Volunteer Management system should keep and validate information of the users.</br>
SQA-6: The installability of the Volunteer Management system should be easy to install and up-to-date.</br>
SQA-7: The reliability of the Volunteer Management system should only experience 2 or less failures every year.

#### 5.5. Business Rules
BR-1: The system administrator and their employees only have access to view the list of volunteer and case data.</br>
BR-2: The system administrator confirms future volunteers after the background check system sends back background information of volunteers and if they are cleared.

### 6. Other Requirements
#### 6.1. Legal Requirements
LR-1: The Volunteer Management system should follow the government rules on privacy.</br>
LR-2: The Volunteer Management system should work with the Background Check system to prevent any unwanted users.

### Appendix A: Glossary
**Actor**: A person that performs a specific role.</br>
**Assumption**: A statement that is considered true without proof.</br>
**Business Rule**: A set of rules/guidelines that must be followed by a business.</br>
**Dependencies**: A statement that is influenced/dependent on something else.</br>
**Volunteer Management System**: See product.

### Appendix B: Analysis Models

<div align="center"> Figure A-1: Data Model </div> </br>

<div align="center"> Table A-1: Data Dictionary </div></br>

| Data Element | Description | Data Type/Composition | Length | Values |
| --- | --- | --- | --- | --- |
| Volunteer Service Description | Description of the volunteer service required| Senior name </br> +phone number </br> +service location| | |
| Volunteer Account Description | Volunteer information that shows details about the volunteer| Volunteer name</br> +phone number</br> +services</br> +list of experiences and engagements</br> +list of interests| | |
| Volunteer ID | ID number of the volunteer when applying for requests| integer| 10| |
| Service Location | Start time and end time of service, and description of location | alphanumeric | 100| Commas and hyphens are allowed|

<div align="center"> Table A-2: GFD Technique of Benefit, Penalty & Value </div></br>
| Relative Weights | 2 | 1 |  |  |
| --- | --- | --- | --- | --- |
|     | Benefit | Penalty | Total Value | Value % |
|Create Senior-Peer volunteer | 5 | 5 | 15 | 24.6% |
|Create Student-peer Volunteer| 1 | 1 | 3 | 4.9% |
|Assign Volunteer | 5 | 5 | 15 | 24.6% |
|Generate Daily Report | 3 | 5 | 11 | 18.0% |
|Record Volunteer progress report| 4 | 2 | 10 | 16.4%|
|Modify Volunteer Date| 2 | 3 | 7 | 11.5% |
|Total | 20| 21 | 61 | 100% |


### Appendix C: Validation
When validating each requirement, we checked to see if the description matches with the requirements of each actor and made sure that each requirement was written in a clear and concise way. By doing so, reading each requirement either as an actor or customer will make it much easier to read each requirement, as well as an easier understanding of what each requirement talks about. Additionally, it will make it much easier for the programmers to implement each requirement given.


