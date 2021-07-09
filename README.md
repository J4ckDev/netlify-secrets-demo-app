# Netlify Secrets Demo

This app was created using [create-react-app](https://create-react-app.dev/). It is for demonstrating how to store netlify secrets. 

[Here you can find how to do this practice.](https://www.freecodecamp.org/news/how-to-access-secret-api-keys-using-netlify-functions-in-a-react-app/)

## How to run the app locally

To run the app locally on your machine, follow the steps below:

1. Clone the app to your local machine using the command `git clone`.
2. Run the command `npm install` to install dependencies.
3. Create `.env` file at the root of the project directory. Copy and paste the contents of [example.env](./example.env) file. Set the value of the environment variable `REACT_APP_TODO_BASE_URL` to `"https://jsonplaceholder.typicode.com/todos"` for the purpose of this demonstration.
4. Install netlify-cli globally (`npm install netlify-cli -g`) to test the netlify functions and run `netlify dev`.