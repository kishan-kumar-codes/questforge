# QuestForge ![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![Version](https://img.shields.io/badge/version-1.0.0-blue)

## Project Description
QuestForge is a web application that allows players to create, share, and embark on custom quests in their favorite games. Utilizing advanced AI and database technologies, players can generate quests tailored to their interests and collaborate with friends to enhance their gaming experience. The platform leverages FastAPI for backend services, Langchain for natural language processing, and Pinecone for efficient data retrieval.

## Features
- 🎮 Dynamic quest generation based on player preferences
- 🤝 Real-time collaboration for multiplayer quest creation
- 🗣️ Integration with AI-driven NPC dialogue systems

## Tech Stack
### Frontend
- ReactJS

### Backend
- FastAPI
- Langchain

### Database
- QdrantDB
- Pinecone

## Installation
To set up QuestForge locally, follow these steps:

- Clone the repository
bash
git clone https://github.com/kishan-kumar-codes/questforge
- Navigate to the project directory
bash
cd questforge
- Install the required dependencies
bash
pip install -r requirements.txt
- Start the backend server
bash
uvicorn app.main:app --reload
- Navigate to the frontend directory
bash
cd frontend
- Install frontend dependencies
bash
npm install
- Start the frontend server
bash
npm start
## Usage
Once the application is running, open your web browser and navigate to `http://localhost:3000` to access QuestForge. You can create quests, collaborate with friends, and explore AI-driven NPC dialogues.

## API Documentation
For detailed API documentation, please refer to the [API Documentation](https://github.com/kishan-kumar-codes/questforge/wiki/API-Documentation).

## Testing
To run the tests for QuestForge, follow these steps:

- Navigate to the project directory
bash
cd questforge
- Run the tests
bash
pytest
## Deployment
For deploying QuestForge, you can use platforms like Heroku, AWS, or DigitalOcean. Ensure that you set up the environment variables and database connections as per your deployment platform's requirements.

## Contributing
We welcome contributions to QuestForge! If you'd like to contribute, please follow these steps:

1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Make your changes and commit them
4. Push your branch to your forked repository
5. Create a pull request

For more details, please refer to our [CONTRIBUTING.md](https://github.com/kishan-kumar-codes/questforge/blob/main/CONTRIBUTING.md). 

Thank you for your interest in QuestForge! Happy questing! 🚀