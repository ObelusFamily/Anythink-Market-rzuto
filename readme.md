# Welcome to the Anythink Market repo

So first thing’s first - install Docker
You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.
Then, run docker-compose up from the project root directory to load Anythink's backend and frontend.

If Docker is working correctly, the backend should be running and able to connect to your local database.
Let's test this by pointing your browser to http://localhost:3000/api/ping

check the frontend and make sure it’s connected to the backend.
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register