# Django Chat Application

A real-time chat application built with Django following the Model-View-Template (MVT) architecture. Users can create accounts, join chat rooms, and communicate in real-time.

## Features

- **User Authentication**: Sign up, log in, and log out functionality.
- **Real-Time Messaging**: Instant message updates using MVT architecture.
- **Chat Rooms**: Create or join existing chat rooms.
- **Message History**: View previous messages in chat rooms.
- **Responsive Design**: Works on both desktop and mobile devices.

## Technologies Used

- **Backend**: Django 4.x
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: SQLite 
- **Real-Time Communication**: Model and Views

## Installation

Follow these steps to set up the project locally:

1. **Prerequisites**:
   - Python 3.9+
   - pip package manager

2. **Clone the repository**:
   ```bash
   git clone https://github.com/Rishav-Upadhaya/django-chat-app.git
   cd django-chat-app
   ```

3. **Create a virtual environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply database migrations**:
   ```bash
   python manage.py migrate
   ```

6. **Create a superuser** (optional for admin access):
   ```bash
   python manage.py createsuperuser
   ```

7. **Run the development server**:
   ```bash
   python manage.py runserver
   ```

8. Access the app at `http://localhost:8000` in your browser.

## Usage

1. **Home Page**:
   - Sign up or log in if you have an account.
   - View existing chat rooms or create a new one.

2. **Chat Room**:
   - Join a room to start messaging.
   - Messages are displayed in real-time.
   - All users in the room can see sent messages immediately.

3. **Admin Panel**:
   - Access at `http://localhost:8000/admin` (requires superuser credentials).
   - Manage users, rooms, and messages.

### Key Components:
- **Models**:
  - `ChatRoom`: Stores room name, description, and creation time.
  - `Message`: Stores message content, timestamp, and relationships with User/ChatRoom.
- **Views**:
  - Handle user authentication, room creation, and message retrieval.
- **Templates**:
  - Dynamic HTML pages rendered with Django template language.
- **Consumers** (WebSockets):
  - Manage WebSocket connections for real-time messaging.

## License

Distributed under the MIT License. See `LICENSE` for details.
