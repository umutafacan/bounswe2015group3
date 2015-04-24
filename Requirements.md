Version1.1

![http://asmarterplanet.com/mobile-enterprise/files/mobile-application-project-management.png](http://asmarterplanet.com/mobile-enterprise/files/mobile-application-project-management.png)


# Summary #
> This project  is about  providing a web and mobile application for only members of the CMPE Community to create and organize content and connect with each other in meaningful ways such as interests, experience, etc. Also System provides the ability to create events and to announce them. By the way this project mainly aims to increase communication among the members of CMPE department in non-academic manners by creating a closed network platform which has many functionalties to ease that.


# Background #
> The aim of this document is explaining the requirements of ‘CMPE Social       Life’ with glossary part, detailed explanations of requirements and references   part.  There are two parts of ‘Requirements’ section; ‘Functional Requirements’   and ‘Non-Functional Requirements’.

> Glossary part consists of keywords that are used very much in ‘Requirements’ part and their explanations.  This section is totally for giving prior knowledge about our project.

> Requierements part is divided two main parts. The part of ‘Functional requirements’ covers behavior of system and services the system provides. Basically, there will be topics includes applications  features for users. There are four subtopics in this part: User Requirements, Event Requirements, Group Requirements and System Requirements. The part of ‘Non-Functional requirements’ consists of information about system properties, constraints and process requirements. In other words, this part will be technical perspective of the project requirements.

![http://agafonovslava.com/image.axd?picture=%2F2013%2F11%2Frequirements.jpg](http://agafonovslava.com/image.axd?picture=%2F2013%2F11%2Frequirements.jpg)

# Requirements #

## 1. Functional Requirements ##
  * **1.1 User Requirements**
    * _**1.1.1 Guests**_
      * 1.1.1.1 Guests from Boğaziçi University Computer Engineering department shall be able to register to the system by writing an e-mail address and a password.
      * 1.1.1.2 Guests should be able to  see only introduction provided by the system.
    * _**1.1.2 Members**_
      * 1.1.1.1 There shall be five account types: undergraduate, graduate, alumni, faculty member and staff.
      * 1.1.1.2 Members should be able to login to the system via their registered e-mail address and the password.
      * 1.1.1.3 Members shall have a profile page which includes information, his/her interests, subscribed groups and events etc.
      * 1.1.1.4 Members should be able to reset their password by an e-mail from the system when they forget their password.
      * 1.1.1.5 Members should be able to decide privacy settings.
      * 1.1.1.6 Members should be able to edit their profiles.
      * 1.1.1.7 Members should be able to change the account type in case of status changes.
      * 1.1.1.8 Members should be able to create a group or an event.
      * 1.1.1.9 Members should be able to search an event, a group or a member
  * **1.2 Event Requirements**
    * 1.2.1 Members should be able to join events with this application
    * 1.2.2 Members should be able to configure specify privacy settings of events.
    * 1.2.3 Members should be able to create and edit events by special tool of application.
    * 1.2.4 System should be able to keep created events as much time as possible.
    * 1.2.5 Members should be able to see according to their permission.
    * 1.2.6 People who attend to the event should be able to communicate with other people under the event page.
    * 1.2.7 Members should be able to share photograph albums and videos of the event.
    * 1.2.8 Members should be able to see events which they attended on the their  user profile page and the others profile pages if they have permission.
    * 1.2.9 System shall record all previous events which are created on the group on the event catalogue of the group .
  * **1.3 Group Requirements**
    * _**1.3.1 The Creator**_
      * 1.3.1.1 The creator should be able to set the name of the group.
      * 1.3.1.2 The creator should be able to set the privacy options of the group, such as which contents shall be visible to the member who are not in the group.
      * 1.3.1.3 The creator should be able to decide who may apply to the group, i.e. the groups shall be open or closed for certain member types, or invitation-only.
      * 1.3.1.4 The creator should be able to assign a moderator to the group.
      * 1.3.1.5 The creator should be able to delete the group.
      * 1.3.1.6 The creator is a moderator of the group.
    * _**1.3.2 Moderators**_
      * 1.3.2.1 Moderators should be able to view and accept the applications made by the member to the group.
      * 1.3.2.2 Moderators should be able to  warn and remove an ill-behaving member.
      * 1.3.2.3 Moderators should be able to delete inappropriate or not-related content.
      * 1.3.2.4 Moderators shall be group members.
    * _**1.3.3 Group Members**_
      * 1.3.3.1 Group members should be able to share content related to the interest of the group. The content may be in the form of multimedia files.
      * 1.3.3.2 Group members should be able to invite other member to join the group.
  * **1.4 System Requirements**
    * 1.4.1 _**Automoderation**_
      * 1.4.1.1 A person who misuses the system shall be banned such that people who shares inappropriate posts like commercial.
      * 1.4.1.2 System shall defects the ad bots to prevent ads and commercial entries by outside of verified members.
      * 1.4.1.3 Voting system should be able to provide an ability to remove unwanted topics by reporting from users.
    * 1.4.2  _**Platform Supports**_
      * 1.4.2.1 The application shall provide support for android 2.3 or later versions.
      * 1.4.2.2 The website shall provide support for IE 8 or later, Mozilla Firefox, Google Chrome, Opera, and Safari browsers.
    * _**1.4.3 Semantic Tagging and Searching**_
      * 1.4.3.1 The system should be able to tag topics and events by many aspects such kind of book, type of event, or creator of content, target group, etc.
      * 1.4.3.2 The system shall provide search by user name, event name and group name options.
      * 1.4.3.3 The system shall provide quick and accurate searching function to users to find the closest topics which user want to see by using tags of contents.
      * 1.4.3.4 The system shall bring on results in case of a search, not only by word matching, but also considering the contextual meaning of the query.
      * 1.4.3.5 The system shall relate the cases and make recommendations through cases by  bringing on contextually and semantically related cases as recommendations.
    * _**1.4.4 Notifications**_
      * 1.4.4.1 System should be able to send e-mail to users who followed topics or events about changes.
      * 1.4.4.2 System should be able to send remote push notifications to Android Users about changes about interested contents.

## 2. Non-Functional Requirements ##

  * _**2.1 Security and Reliability**
    * 2.1.1 There should be a system for protecting private informations, database, encrypted informations from unwanted people.
    * 2.1.2 All the records and database shall be copied monthly for possible failures.
  *_**2.2 Usability**
    * 2.2.1 The application should have a helpful, understandable and not complicated user interface so that everyone can easliy use it.
    * 2.2.2 The language of the application should be plain so that there will no any confusion.
    * 2.2.3 Usability shall be tested with several user groups by user tests.
    * 2.2.4 In the web page, member should be able to see what he or she wants to see in 3 clicks.
  * _**2.3 Server Capacity**
    * 2.3.1 All the user should be able to use application simultaneously.
    * 2.3.2 The system should be able to used by 1000 users simultaneously.
  *_**2.4 Efficiency**
    * 2.4.1 The user shall be responsed in maximum 2 seconds.
  * _**2.5 Availability**
    * 2.5.1 The system should be implemented as both Android application and web application
    * 2.5.2 The system shall run everytime except the maintenance periods.
    * 2.5.3 The android application shall also be available for mobile devices.
    * 2.5.4 When the system crushes down, it should be available in one day._


![http://www.zeiss.com/content/microscopy/international/website/en_de/desktop/service-support/glossary/jcr%3Acontent/stagepar/stage/slide/stageimage/image.img.jpg/1391094697983.jpg/glossary-stage.jpg](http://www.zeiss.com/content/microscopy/international/website/en_de/desktop/service-support/glossary/jcr%3Acontent/stagepar/stage/slide/stageimage/image.img.jpg/1391094697983.jpg/glossary-stage.jpg)
# Glossary #

  * **Member:** A person who can create account and enter the system as a user.

  * **Guest:** A person who can temporarily enter website and see limited things according to policies.

  * **Admin:** A person who responsible for managing   a computer or network , updating security settings, providing valuable help about  the problem etc. . Also, that person  has full access to the system because of  his/her responsibilties.

  * **Profile:** A brief written description that provides information about that user. Also, some photos and sharings may include in profile.

  * **Account:** An account is a collection of information that tells the system which information you can access, what changes you can make to the system, and your personal preferences, such as your profile page and sharings.

  * **Password:** A secret series of characters that enables a user to access his/her own account. The password helps ensure that unauthorized users do not access the that account. In addition, data files and programs may require a password.

  * **Username(email):** A unique sequence of characters used to identify a user and allow access to a his/her own  account.

  * **Database:** A database is an organized collection of data. The data is typically organized to model aspects of reality in a way that supports processes requiring information.

  * **Encryption:** Encryption is the process of encoding messages or information in such a way that only authorized parties can read it.

  * **Interface:** The visual part of website or application where user can interact with application.

  * **Creator:** The creator of a group is the member who creates the group. The creator is the only member who can set/change the privacy options of a group and delete a group.

  * **Moderator:** A member of a group who is responsible of moderating the group by accepting new members, banning ill-behaving members etc.

  * **Group member:** A group member is a member who has joined a group and can share content on the group page.

  * **Event:** Something that occurs in a certain place during a particular interval of time.

  * **Group:** A number of persons or things ranged or considered together as being related in some way.