# SENG 3130 - Final Report - Volunteer Management System

## Vision and Scope Document
 
### 1. User Requirements
#### 1.1. Engineering Requirements & Practices
From the previous report on the vision and scope document, one of the lessons that our group learned was that it is important to figure out who the stakeholders are in a project. Also, it is important to figure out how the volunteer management system relates to the stakeholders and their interest and values. With the vision and scope document, it was key to figure out who the stakeholders were for the volunteer management system so that we can write out certain subjects, such as the business opportunities and objectives, success metrics, and system profiles, keeping in mind who the stakeholders are in the project. Figuring out how the volunteer management system will work based on the stakeholders and their needs will directly help us with the user requirement document. This lets us figure out the user classes, actors, and use cases of the volunteer management system, by taking into consideration the stakeholders and their needs. Also, it lets us figure out how the volunteer management system will work based on who or how a user is using the system.

#### 1.2. User Classes
| User Class and Type | Description |
| --- | --- |
| `Volunteers: Direct and Favoured` | Should enter their name, phone number, address and extra details to the system to be reviewed by the administrators.|
| `Seniors/Elders: Direct and Favoured` | Should report their needs for social support. |
| `System Administrators: Direct and Favoured` | Receive daily reports with the forecasted number of cases during the next week. </br> For example, I can reassign volunteers to higher severe cases. I should also see any new requests from the School Administrators who request volunteers to teach the students. </br> Send volunteer information to the background check system after the system administrator product champion has looked over the new volunteers. </br> Should be able to verify the educational certificates of volunteers who are required to teach kids.|
| `Mayor/Staff: Direct and Disfavoured` | Receive information on seniors and create profiles for the seniors on the system.|
| `Background Check System: Indirect and Disfavoured` | Should process 1K background checks per hour. The problem is that the system process includes a manual step to get approval from the police officers, so it only works during working hours.|
| `Sponsors: Indirect and Ignored` | Fund the volunteer management system in exchange for volunteer help. |
| `Subject Matter Expert: Indirect and Favoured` | Give advice on the subject matter forthe volunteer management system.|
| `Senior People Champion: Indirect and Favoured` | Should gather senior’s information over the phone and send it to the staff.|
| `System Administrator Product Champion: Indirect and Favoured` | Check over newly registered volunteers and do initial screening. If the profile looks good, the administrators are able to send the information of the volunteers to the background check system. |

#### 1.3. Actors
| Actors | Actor Description |
| --- | --- |
| `Volunteers (Primary)` | To provide services for seniors.|
| `Seniors/Elders (Primary) ` | To receive services from volunteers.|
| `Mayor/Staff Members (Primary)` | Running the system.|
| `System Administrators (Supporting)` | To approve and accept volunteers into the system.|
| `Background Check System (Supporting)` | To review volunteer information.|
| `Sponsors (Offstage)` | To support the system.|
| `Product Champions (Supporting)` | To provide advice for the system.|
| `Subject Matter expert (Supporting)` | To provide advice on how to engage users and to make the system easy to use|

#### 1.4. Use Cases
**UC-1:** Create new Volunteer: Volunteer, System administrators
* Volunteer joins the system
* System administrators sends it to the background check system
**UC-2:** Approve new Volunteer: Background Check System, System administrators
* System credential check looks over volunteer info
* System administrators receives info on volunteer
**UC-3:** Update Volunteer: Volunteer, System administrators
* Volunteer changes account info about them
* System administrators allows the update
**UC-4:** Delete Volunteer: Volunteer, System administrators
* Volunteer cancels volunteer system
* System administrators deletes volunteer account
**UC-5:** View Volunteer: Senior, Volunteer, System administrators
* Volunteer can view their own info
* System administrators can view info on volunteer
* Senior can view info on Volunteer
**UC-6:** Generate Daily Report: System administrators, Mayor/Staff members
* System administrators and mayor/staff members receive daily report on system
**UC-7:** Request Volunteer: Senior
* Senior request volunteer aid
**UC-8:** Accept Volunteer Request: Volunteer, Senior
* Volunteer accepts volunteer request from senior

#### 1.5 Use Case Diagram

### 2. Fully Dressed Use Cases
#### 2.1. UC-1: Create New Volunteer

#### 2.2. UC-2: Approve New Volunteer

#### 2.3. UC-3: Generate Daily Report
