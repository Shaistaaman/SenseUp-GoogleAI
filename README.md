# SenseUp-GoogleAI

Imagine a revolutionary tool that empowers people with vision and hearing impairments to experience the world in a whole new way. This is a tool, leveraging the power of Google AI to bridge the gap.

<iframe width="500" height="300" src="https://youtu.be/Uzr7o0tp7To" frameborder="0" allowfullscreen></iframe>

# Setting Up the Development Environment:

Ensure you have Node.js and npm (Node Package Manager) installed on your system.
Choose your preferred code editor (e.g., Visual Studio Code, Atom).
`npm install` to install neccessary packages in both the backend and frontend folders in two different terminals.

For Nodejs project write `npm run start` in the terminal. As nodemon is installed you will see the running server in the background in case of code changes.
Assign your API key to an environment variable: export API_KEY=API_KEY.
Libraries used in backend are cors, express, multer, nodemon, path, google/generative-ai, dotenv.

For Reactjs app write `npm start` in the respective terminal to run the forntend. Bootstrap is used for UI.

# Interacting with UI

Upload any image document with some text on it.
Write detailed prompt in the prompt input otherwise default prompt will be handled.
Click Go button to see the response in textarea.
You can zoom in the output to see it in magnified fonts.
