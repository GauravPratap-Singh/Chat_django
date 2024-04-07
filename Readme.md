# Project Title: Django Chat App with WebSocket, JS and Tailwind CSS

## Description:
This is a demo project showcasing the implementation of a real-time chat application using Django, WebSocket, and Tailwind CSS. The project utilizes Django Channels to enable WebSocket communication between clients and the server, allowing for instant messaging in a web-based chat interface. Tailwind CSS is used for styling to provide a modern and responsive user interface.

## Features:
- Real-time chat functionality using WebSocket.
- User authentication and authorization.
- Routing for different pages such as login, registration, and chat room.
- Styling with Tailwind CSS for a visually appealing interface.
- Django Channels consumers for handling WebSocket connections.

## Installation:
1. Clone the repository:
    git clone <https://github.com/GauravPratap-Singh/Chat_django.git>
    cd django-chat-app
3. Install dependencies:
    pip install -r requirements.txt
4. Apply migrations:
    python manage.py migrate
5. Run the development server:
    python manage.py runserver

6. Access the application in your web browser at `http://localhost:8000/rooms`.

## Usage:
1. Register a new account or log in with existing credentials.
2. Navigate to the chat room page.
3. Start sending and receiving messages in real-time with other users.

## Project Structure:
- **`chatapp/`**: Django app directory containing the main application logic.
- `models.py`: Defines database models for user authentication and chat messages.
- `views.py`: Implements views for rendering HTML templates and handling user interactions.
- `urls.py`: Defines URL patterns for routing requests to appropriate views.
- `consumers.py`: Contains Django Channels consumers for WebSocket communication.
- **`templates/`**: Directory for HTML templates.
- **`static/`**: Directory for static files such as CSS and JavaScript.
- `styles.css`: Custom CSS styles for the chat interface.
- **`requirements.txt`**: File listing project dependencies.
- **`README.md`**: Project documentation and instructions.

## Technologies Used:
- Django: Web framework for backend development.
- Django Channels: Extension for handling WebSocket connections.
- Tailwind CSS: Utility-first CSS framework for styling.
- HTML/CSS/JavaScript: Frontend technologies for building the user interface.

## Contribution:
Contributions to the project are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

