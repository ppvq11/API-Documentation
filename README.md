# API-Documentation


<details>
<summary>App Statement</summary>

Conference Management Software is an system to facilitate the planning, coordination, and execution of conferences and events. This robust system caters to the core components of conference management by incorporating a suite of functionalities tailored to enhance the collaboration between speakers, organizers, and attendees


</details>


<details>
<summary>Tables</summary>


1-Session Table 

| Column           | TYPE          |
|-----------------:|---------------|
|         Sessionid|uuid           |
|             Title|String         |
|              Desc|String         |
|       SpeakerName|String         |
|        HallNumber|String         |
|ScheduledStartTime|String         |
|   ScheduledEndime|String         |
|            Status|String         |
|          Location|String         |


2-Attendee Table 

| Column           | TYPE          |
|-----------------:|---------------|
|        AttendeeID|uuid           |
|          FullName|String         |
|             Email|String         |


3-SessionAttendee Table

| Column           | TYPE          |
|-----------------:|---------------|
|        AttendeeID|uuid           |
|         Sessionid|uuid           |
|            Status|String         |




</details>




<details>
<summary>RelationShip</summary>



</details>






