# To Run the Application Locally in you system

You need to First of all open the file in VS Code or any other ICE which you are using. 
You can follow the steps:
1. Extract the file after downloading it from the github.
2. Then after opening it in a IDE (ex. Vs Code), open the terminal in the IDE and run 
 :=  npm install 
 to download all the relevant packages.
 After that run,
 :=  npm run dev
 to run the project locally.

For developing the I've used React+vite as the Tech Stack. I've used Rapid Api to fetch: 
(i) Location
(ii) Temperature, Wind Speed, Humidity and Heat Index
(iii) Also fetches the weather forecast for next 7 Days.
According to the weather conditions the background image of the Application gets changed,
for ex. If the weather is sunny, the bg image will get changed to sunny picture.

I've used visual crossing Weather API for fetching the weather details and also I've set the default location as the Jaipur because it is where I belong.
