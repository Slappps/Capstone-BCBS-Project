

**Care Signals work requirement part one, Create a proof of concept with the following propertes:**<br>

**Milestone1:** Working Broadcast POC - broadcast messages to all test members ("flu shot campaign") AND LLM generated samples pertinent to member segmentations. Complete data mapping for both broad outreach segments 
and individual needs. Basic routing infrastructure in place.<br>

User can request many user's to be messaged about medical relatied topics<br>
Project must convert english to SQL<br>
Project must query datsbase<br>
Project must send this info to an mailing agent<br>
Mail agent must send out message to recieved users<br>
Third agent must generate email template to send out<br>

**Execution:**<br>
Currently the broadcast functionality and english to sql is working.<br><br>
Project must be run in N8N which is an online automation software solution<br>
Simply enter in your data to the chat feild and the automation will do the rest<br>
May need to set up SMTP account<br>
May need to set up DB connection<br>

**Milestone2:** Working Broadcast POC - broadcast messages to all test members ("flu shot campaign"). Use a doctor's note to pull correlating CPT codes from vector storage. This will later be followed by personalized messages.<br>

User must be able to send messages to anyone, but also pay attention to their preferred contact method<br>
User must be able to pull CPT codes based on a doctors note<br>
Project must implement CPT codes<br>

**Execution:**<br>
The broadcasting functionality works, and now can send messages based on preferred contact method.<br>
Project must be run in N8N which is an online automation software solution<br>
Simply enter in your data to the chat feild and the automation will do the rest<br>
May need to set up SMTP account<br>
May need to set up DB connection<br>
Must need to set up vector storage<br>

**Release Notes**<br>
Version 1<br>
Include a section called, "Release notes" - explain what is working in this submission (add explanation if this is not consistent with the milestone as described in the Project Plan)<br>

Current iteration can recieve requests in english form, and return the requested data<br>
Basic mailing function set up using SMTP, mail is sent between two test accounts<br>

Version 2<br>

Cleaned up automation workflow by using a central AI Agent with many sub workflow tools<br>
Added a communication agent to broadcast messages<br>
Added a vector storage to hold and chunk CPT information<br>
User can now request informaiton about a user in the database more effectively<br>

  
  

