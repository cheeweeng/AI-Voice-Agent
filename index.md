In this exercise, I will build an [AI voice agent](https://youtu.be/7ZWvIUkOAmI) for a fictitious dental clinic who is capable of booking dental appointments for call-in customers using Retell AI.  

<img width="650" height="400" alt="Image" src="https://github.com/user-attachments/assets/e0dcfb8f-9015-4e1f-a401-4de35d5dcbfc" />   

Go to Retell AI and create an account. At the dashboard, click on create agent and select voice agent.  
For agent type, select Single Prompt Agent which is capable of holding free-form conversations.  
Next, select start from blank.  

<img width="857" height="527" alt="Image" src="https://github.com/user-attachments/assets/2d885b66-b049-4522-9915-b519aaa9c4fc" />  

At the canvas, paste in the system prompt.  The system prompt will give the AI agent a personality, its tone, some guardrails, the tools available at its disposal, and most importantly the goals it has to serve.  Since it is an agent handling inbound calls, select AI speaks first at the left bottom dropdown menu.

<p float="left">
  <img src="https://github.com/user-attachments/assets/204fe7e9-369e-4888-8ecd-3b5c61d77214" width="420" />
  <img src="https://github.com/user-attachments/assets/a088f412-a362-46ae-838a-e638e3eafc44" width="550" />
</p>

Next, add knowledge base for the AI agent to use for answering users' queries. PDFs or text files can be uploaded into knowledge base.

<img src="https://github.com/user-attachments/assets/fcb62b5a-bb0d-4c05-94ca-17c834f3d4ca" 
     width="300" align="left" style="margin-right:15px;" />

There are various preset functions we can add for the agent. The end-call function is added by default.
For this exercise, we will need a check calendar avaliability and book on calendar function.  
<br clear="left"/>

<img width="400" height="550" alt="Image" src="https://github.com/user-attachments/assets/ebd77c3b-e722-44b1-8f83-fa42166f2757" align="left" style="margin-right:15px;"/>
First, let's add the check calendar availability function. In this function, we need to input the Name, API Key and Event Type ID.
The name given for this function must match the tool name stated in the system prompt. 
Go to cal.com and create an account, follow the prompt until your Google calendar got connected.
<img width="550" height="437" alt="Image" src="https://github.com/user-attachments/assets/14843361-e660-49ac-83f9-7e3021ec3d2b" />

<br clear="left"/>

<img width="450" height="550" alt="Image" src="https://github.com/user-attachments/assets/5d66e221-7b43-4daa-a941-d233debf79ed" align="left" style="margin-right:15px;"/>
Then go to add new event type to set up a  new event. Next, go to Advanced settings and change the user to event type.
<img width="450" height="400" alt="Image" src="https://github.com/user-attachments/assets/2260bdf0-0a1b-4617-9f8e-37747d328e2a" />
<br clear="left"/>

<img width="500" height="80" alt="Image" src="https://github.com/user-attachments/assets/2555a6b9-e9d4-4473-bf63-d788c619dbb9" align="left" style="margin-right:15px;"/>  
The event type ID can be seen from the url bar. Insert this ID into the field of the check calendar availbility function.
<br clear="left"/>
<img width="500" height="380" alt="Image" src="https://github.com/user-attachments/assets/c19217d3-1f65-425b-b2a5-1305d174052c" align="left" style="margin-right:15px;" />
Still at cal.com, navigate to API Key and set up a new API key. Copy/paste this key into the field of the check calendar availbility function.
<br clear="left"/>

<img width="380" height="535" alt="Image" src="https://github.com/user-attachments/assets/e5c55ab9-f8ba-48f4-9925-b1a50d826ea1" align="left" style="margin-right:15px;" />
Next, we add the book on the calendar function. The API key and the event type ID is the same as the previous function.
<br clear="left"/>

<img width="380" height="200" alt="Image" src="https://github.com/user-attachments/assets/0c25809e-efe2-4f38-bba9-73827687400a" align="left" style="margin-right:15px;"/>
The three essential functions for this AI voice agent are completed. Click here to see the [AI voice agent in action](https://youtu.be/7ZWvIUkOAmI).
In the video demo, I have placed the Google calendar beside the AI voice agent test page to demo its ability to check and book an appointment on the calendar.
<br clear="left"/>
