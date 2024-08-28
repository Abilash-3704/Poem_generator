# Poem Generator

This Poem Generator is a web application that generates poems based on user input using the Claude-3.5 sonnet model. It supports real-time poem generation and provides a user-friendly interface to interact with the AI model.

## Features
- Generate poems based on user prompts using Claude AI.
- Real-time poem generation.
- User-friendly interface built with React and enhanced using animations.
- Deployed on Azure for scalability and reliability.

# Live Demo
Check out the website:[Visit](https://poemgenerator-bpaxemhgehasaqf5.southindia-01.azurewebsites.net/)

## Installation
create a virtual environment in the backend folder
```bash
cd backend
pip install -r requirements.txt
```
```bash
cd ../frontend
npm install
```

change the socket io url and the fetch url in axios request to localhost with a preferred port
set the proxy value in package.json to the localhost with the port where the server.py file sets the server up
set origin value in CORS method to "*" in server.py file

setup a .env file in the root directory

CLAUDE_API_KEY={your claude api key generated from anthropic}

## Usage

Run the backend server:
```
cd backend
python server.py
```

Start the react server
```
cd ../frontend
npm run start
```
