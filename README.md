# Django Chat Application

A modern, real-time chat application built with Django following the Model-View-Template (MVT) architecture. Users can create accounts, join chat rooms, and communicate in real-time with a beautiful, responsive interface.

## Features

- **User Authentication**: Sign up, log in, and log out functionality.
- **Real-Time Messaging**: Instant message updates using MVT architecture.
- **Chat Rooms**: Create or join existing chat rooms.
- **Message History**: View previous messages in chat rooms.
- **Modern UI/UX**:
  - Clean and intuitive interface
  - Beautiful gradient backgrounds
  - Modern typography with Inter font
  - Smooth animations and transitions
  - Enhanced message bubbles
  - Better visual hierarchy
  - Auto-scrolling to latest messages
- **Fully Responsive**: Optimized for all devices (mobile, tablet, desktop)
- **Enhanced User Experience**:
  - Real-time message updates
  - Visual feedback on actions
  - Improved form validation
  - Better error handling
  - Message status indicators

## Technologies Used

- **Backend**: Django 4.x
- **Frontend**: 
  - HTML5
  - Modern CSS3 (Flexbox, Grid, Custom Properties)
  - JavaScript (ES6+)
  - jQuery for AJAX
  - Google Fonts (Inter)
- **Database**: SQLite 
- **Real-Time Communication**: Model and Views
- **UI Framework**: Custom CSS with modern design principles

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
   source venv/bin/activate  # On Windows: venv\\Scripts\\activate
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
   - Clean, modern interface for user registration and login
   - Intuitive room creation and joining process
   - Visual feedback on form interactions
   - Responsive design adapts to all screen sizes

2. **Chat Room**:
   - Modern chat interface with enhanced message bubbles
   - Clear visual distinction between sent and received messages
   - Real-time message updates with smooth animations
   - Auto-scrolling to latest messages
   - Improved message input with instant feedback
   - Better error handling and user notifications

3. **Admin Panel**:
   - Access at `http://localhost:8000/admin` (requires superuser credentials)
   - Manage users, rooms, and messages
   - Monitor chat activity and user engagement

### Key Components:
- **Models**:
  - `ChatRoom`: Stores room name, description, and creation time
  - `Message`: Stores message content, timestamp, and relationships with User/ChatRoom
- **Views**:
  - Handle user authentication, room creation, and message retrieval
  - Improved error handling and response formatting
- **Templates**:
  - Modern, responsive HTML templates with enhanced styling
  - Dynamic content rendering with Django template language
  - Improved user interface components
- **Static Files**:
  - Custom CSS with modern design principles
  - Enhanced JavaScript for better interactivity
  - Optimized assets for better performance

## Recent Updates

### UI Enhancements (April 2025):
- Implemented modern gradient backgrounds
- Added Inter font for better typography
- Enhanced chat message bubbles with better visual hierarchy
- Improved form styling and input fields
- Added smooth animations and transitions
- Implemented better mobile responsiveness
- Enhanced error handling and user feedback
- Improved message organization and display
- Added auto-scrolling to latest messages
- Implemented modern shadow effects

## License

Distributed under the MIT License. See `LICENSE` for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.