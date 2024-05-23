Overview
========
This project consists of several SQL files, each responsible for different tables in a database related to events in our association. Below is a description of each SQL file and the tables they interact with.

Files and tables 
================ 

event_user.sql
--------------
This table contains information about users. This includes details such as user ID, name, lastname, email.

event_admin.sql
---------------
This table stores information about event administrators. This includes details like admin ID, name, lastname, permission level and password to log in.

event_events.sql
----------------
This table contains details about the events. Information such as event ID, language of the event, date, location, and status of the event are stored here.

event_languages.sql
-------------------
This table stores information about the languages levels of each users in events. This might include language ID, language, and level.

event_registered.sql
--------------------
This table contains information about participants who have registered for events. This includes details like user ID, event ID, and the money paid.
