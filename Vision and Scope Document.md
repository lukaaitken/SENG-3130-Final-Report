# SENG 3130 - Final Report - Volunteer Management System

## Vision and Scope Document
 
### 1. Business Requirements
#### 1.1. Background
During the covid pandemic, there was a decline in the use of volunteer aids in the client's community. This is due partially to the fact that there were a lot of customers lost, as well as a huge drop off of volunteers during the pandemic. On top of all this, the onboarding system that we currently have is taking too long with wait times upwards of two weeks to complete a background check through the police.

#### 1.2. Business Opportunity
For this volunteer management system, the business opportunities that can come out of this project is that more city activities will have more volunteers, which can boost the city’s popularity. It can help boost the number of volunteers being involved with the city, performing tasks that can benefit the stakeholders. Currently, the limitations of the previous management system is that it takes longer than usual to get volunteer requests. This makes it less likely that volunteers will take on the request. Taking longer to post new requests, will cause a shortage in volunteers due to the late posting time. This new volunteer management system will help reduce the possibility of the volunteer shortage to two times per year. It will also be able to predict and deduce if there will not be enough volunteers by notifying management if cases don’t have volunteers by a one-week notice.

#### 1.3. Business Objectives and Success Criteria
The volunteer management system's business objective is to create a system that is easily accessible to all the stakeholders, such as clients, volunteers, and clients with different tasks and needs. This system will help speed up the process of getting more volunteer requests, which will make volunteer assignments quicker and reduce the possibility of volunteer shortages. Volunteers can check to see if there are openings through the system rather than going in person. The volunteer management system should be able to track 60% of senior cases and support up to 85% of cases. It should be able to handle approximately 6000 to 9000 cases with a low bound of 5100 and an upper bound of 7650 cases. The system should also help reduce the last-minute volunteer shortages to two times per year by getting volunteer support within three days.

The success metric for the volunteer management system is that the system can forecast the needed cases ahead of time by one week in advance. This successfully meets the business objective by limiting volunteer shortages to two times per year. It also reduces the volunteer assignment time to 30% which allows clients/senior people to get volunteer support within three days and will limit limbo time for clients waiting for help. With the increase of volunteers being able to apply quicker with the new background check system that is in development, it will help increase beneficial activities that can decrease the crime rate in the city. This will also increase business transactions in the downtown area and local shops by 10%. This could lead to possible sponsors in the area with different promotions to volunteers as an incentive.

#### 1.4. Customer or Market Needs
The clients are needing help with day-to-day routines. or they are just looking for someone to hang out with. There has been a steady decrease in volunteering to aid the clients in recent years and we are trying to fix that gap by building this management software. We are currently seeing that due to the extended wait times for people to volunteer some of the clients go without aid for quite a while. Although we are not directly involved in the police checks we are aware that the government is building a system to streamline this process which will aid us in the long run. We will be working closely with the downtown area and businesses to develop an endorsement plan to get people to sign up through a rewards system. This will allow us to pick up new volunteers quickly and effectively.

#### 1.5. Business Risks
**RI-1**: Too few employees managing the management system, which can cause stress on the employees as well as make the volunteer management system vulnerable to glitches and hacks. (Impact = 6)</br>
**RI-2**: The clients may not use or own an electronic device, reducing the number of volunteer cases in the city. (Impact = 8) </br>
**RI-3**: Overloading of cases on the volunteer management system could cause many volunteer cases to be missed, lowering the use of the management system. (Impact = 9)

### 2. Vision of the Solution

#### 2.1. Vision Statement
**For** customers and volunteers **who** require assistance with daily tasks or want to help the community, **the** Volunteer Management system is an online database system **that** accepts both volunteer requests and allows volunteers to sign up to participate and help the community. **Unlike** going in person, emailing, or calling to request, customers and volunteers who use the Volunteer Management system do not have to go in person or use phones and email to request help, **which** will save time for both customers and volunteers when applying for either request or volunteering positions.

#### 2.2. Major Features
**F.E-1**: Registration system for clients and volunteers to keep information about personal data. </br>
**F.E-2**: Background Check system that checks the credentials of users to see if any users have criminal records. </br>
**F.E-3**: Help request system for the client to request help. </br>
**F.E-4**: Subautomated system that connects the management system with the background check system. </br>
**F.E-5**: Predictive management system that tracks cases for 7 days from the current date. </br>
**F.E-6**: Assignment system to assign the volunteer with the help requests. </br>
**F.E-7**: Feedback system to allow feedback for volunteers from the client. </br>
**F.E-8**: The volunteer time sheet limits the amount of time a volunteer spends out to 30% of the original and then updates the volunteer list with the exclusions.

<p align=center>
<img src="https://github.com/lukaaitken/SENG-3130---Final-Report/blob/main/Figures/PartialFigureTree.JPG?raw=true" alt="Figure Tree" width="600"/></p>

<div align="center"> Figure 1: Partial feature tree for the Volunteer Management System.</div>

#### 2.3. Assumptions and Dependencies
**A1.1**: We are assuming that the background check system to reduce the time it takes for background checks will be done in the few months that were stated, meaning that it will be done when we are ready to roll out version 1.0 of the management software. </br>
**A2.1**: We are assuming that this program will reduce the crime rate in the downtown area leading to an increase in sales and visitation to the downtown core. </br>
**D1.1**: We are dependent on the speed of the rollout for the police background check improvement. Without it, we will be stuck to some timelines that we cannot improve on quickly.

### 3. Scope and Limitations

#### 3.1. Scope of Initial Release
Within the initial release of the volunteer management system, the system will allow users to interact with the system by registering either as a client or a volunteer. Volunteers will be able to register for cases involving seniors. The system will save and keep the information about the user. User information will be sent to the background check system, which will check the credentials of clients and volunteers. Both the management system and background check system will send information through a sub-automated system. The system will have a predictive management system that tracks cases that are from seven days from the current date. In addition, the system will be able to increase the number of volunteers by making a system that can get back to the user about their credentials, allowing them to start volunteering.This will reduce the number of last-minute volunteer shortages and allow management to get the volunteer record for each client promptly.

#### 3.2. Scope of Subsequent Releases
With later releases over time, the volunteer management system's major features will be able to provide other volunteering cases such as for young elementary school students. This will offer additional teaching and coaching for students who need more dedicated hours due to the limited capacity of teachers. The system would need to provide a way to provide additional training and coaching for special cases as well as ensure that volunteers have the minimum educational skills.

#### 3.3. Limitations and Exclusions
**LI-1**: Management will not be able to directly connect with a user who is trying to become a volunteer through the system itself. Management must connect with users through email or phone numbers. </br>
**LI-2**: The volunteer management system shall be used only for volunteering for clients who require assistance.

### 4. Business Context

#### 4.1. Stakeholder Profiles
| **Stakeholder** | **Major Value** | **Attitudes** | **Major Interests** | **Constraints** | 
| --- | --- | --- | --- | --- |
| `Volunteers` | Better volunteer experience| Positive about quicker registration system but may not be just interested in senior volunteer work| Faster and easier registering system| Minimal knowledge; training|
| `Clients (Seniors)` | More volunteers available| Receptive but positive| Easy to use system for older users|Some may be technology illiterate|
| `Sponsors` | Increase in volunteer activity| High enthusiasm if system is improved| Increase activity downtown/local shops; Decrease in criminal activity| None identified|
| `Mayor` | Improved volunteer management system; Improved volunteer activity|Concern with the number of volunteer shortages due to number of volunteer cases| System that decreases the number of volunteer shortages per year| Volunteer management system that only deals with clients|

#### 4.2. Project Priorities
| **Dimension** | **Driver (state objective)** | **Constraint (state limits)** | **Degree of Freedom (state allowable range)** | 
| --- | --- | --- | --- |
| `Schedule` | Release 1.0 to be available by the time of the new background check system release| | |
| `Features ` | Registration Background check Help request Predictive tracking Assignment system Feedback system Volunteer time sheet| Main features for release 1.0 to be fully operational| 80-90% of high priority features must be included in release 1.0|
| `Quality` | | | 80-90% of user acceptance tests must pass for release 1.0|
| `Staff` | N/A | N/A | N/A |
| `Cost` | budget N/A | budget N/A | budget N/A |

#### 4.3. Operating Environment
The environment that our system lives in will be as far as a single city to start however if the system works superbly then we could expand to a wider range and this will affect our availability. Our system will allow the users to access the system with an internet connection 24/7 for signup and requests. Data is generated in user reports for the volunteers as well as for the clients. This data is generated only as far as a city length across. The only data that should be combined from different locations is the data from the police background checks and our servers to keep them up to date. Effectively making sure that when a background check runs out that a new appeal is placed to receive one and that our records are up to date. Continuous access to the system is a crucial feature for our system so that we know that the people needing help are receiving the help they have requested. There will need to be protocols set up for protecting the data of both the volunteers and the clients of the system. There will need to be security measures taken that allow for partial info to be released when a volunteer is sent to a location to help. As for access to the site, if you are registering as a client you will need to provide specific login credentials every time you log in to stop someone from abusing the system. As for volunteers the same login credentials will also be provided as well as a police background check will occur for us to know that you are a safe person to be sent to help these people.
