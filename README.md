\# Chatzen - AI Chatbot Integration



\## Project Overview



Chatzen is an ASP.NET Core MVC web application integrated with a Botpress AI chatbot. The chatbot provides answers based on the knowledge files configured in the Botpress platform and is embedded into the website through the `Index.cshtml` page.



\## Technologies Used



\* ASP.NET Core MVC

\* Bootstrap

\* Botpress Cloud WebChat



\## How to Run the Project in Visual Studio



\### Step 1: Open the Project



1\. Open \*\*Microsoft Visual Studio\*\*.

2\. Click \*\*Open a project or solution\*\*.

3\. Select the project `.sln` file.



\### Step 2: Build the Project



1\. Click \*\*Build\*\* → \*\*Build Solution\*\*.

2\. Verify the build completes successfully



\### Step 3: Run the Project



1\. Press \*\*F5\*\* or click \*\*Start Debugging\*\*.

2\. The application will launch in your default browser.



\### Step 4: Verify Chatbot



1\. Open the home page.

2\. Check the chatbot widget displayed in the bottom-right corner of the Dashboard.

3\. Start a conversation and verify that responses are returned from the Botpress AI chatbot.



\## Notes



\* Botpress chatbot integration is implemented through JavaScript script references in the `Index.cshtml` file.

\* Chatbot responses are managed through the Botpress platform configuration and uploaded knowledge files.





\## ChatBot Image

\### Chatbot Home Screen
<img src="@Url.Content("~/Images/ChatBot.png")" alt="Chatbot Home" width="800" height="800" />

\### Chatbot Conversation
<img src="@Url.Content("~/Images/Chat.png")" alt="Chatbot Chat" width="800" height="800" />

\### Chatbot Conversation
<img src="@Url.Content("~/Images/Conversation.png")" alt="Chatbot Chat" width="800" height="800" />








