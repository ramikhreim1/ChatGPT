Build and Deploy Your Own ChatGPT AI Application That Will Help You Code
![image](https://user-images.githubusercontent.com/99683327/214826132-c0d4f4cd-4212-4630-abae-4f18368ded7e.png)

In order to run the ChatGPT app on your PC, and hosted online for free you will need to have the following installed:

Python 3.x
pip (Python Package Manager)
Node.js
OpenAI API key, you can get it from the OpenAI website.
After you have those installed, you can follow these steps to run the project:
Navigate to the root directory of the cloned repository in your command prompt or terminal.
Create .env file in the root directory and place your openai API key like this (OPENAI_API_KEY=YOUR_KEY):
![image](https://user-images.githubusercontent.com/99683327/215259501-2aef7832-26e6-459c-abf4-ffdca50f214d.png)

Run the command npm create vite@latest client --template vanilla
Navigate to the Client folder and Run the command npm run dev to start the FrontEnd.
Open your web browser and navigate to http://localhost:5173 to view the project FrontEnd.
Navigate to the Server folder and Run the command npm run server to start the BackEnd.
Open your web browser and navigate to http://localhost:5000 to view the project BackEnd.

You can host your  Backedn for free here render.com , make sure you point your github server folder. 
Your can host your fronend for free here vercel.com, make sure you point your github client folder.



Try it https://chat-gpt-symplify.vercel.app/
