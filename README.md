# 📚 StudyBud

A collaborative platform for students to find study partners around the world! 🌍

## 🌟 Overview

StudyBud is a Django web application that connects students with similar academic interests. Users can create study rooms, join existing ones, and engage in meaningful discussions with fellow learners. The platform encourages knowledge sharing and community building in a user-friendly environment.

## ✨ Features

- 👤 User authentication system (register, login, logout)
- 👥 User profiles with customizable avatars and bio
- 🔍 Search functionality to find relevant study rooms
- 📝 Topic-based room organization
- 💬 Real-time messaging within study rooms
- 📊 Activity feed to track recent conversations
- 🔄 Create, update and delete study rooms
- 📱 Mobile-responsive design

## 🛠️ Technologies Used

- **Backend:** Django (Python web framework)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (default Django database)
- **Authentication:** Django's built-in authentication system
- **Template Engine:** Django Templates

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- pip (Python package manager)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/studybud.git
   cd studybud
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

5. Create a superuser:

   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```bash
   python manage.py runserver
   ```

7. Visit `http://127.0.0.1:8000/` in your browser to see the application.

## 📋 Project Structure

- **models.py**: Defines the data models (User, Topic, Room, Message)
- **views.py**: Contains the application logic and request handlers
- **urls.py**: Maps URLs to corresponding views
- **forms.py**: Handles form creation and validation
- **templates/**: Contains HTML templates for rendering pages

## 💻 Usage

1. **Register/Login**: Create an account or log in to access the platform
2. **Browse Topics**: Explore study rooms filtered by topics of interest
3. **Join Rooms**: Participate in existing study rooms
4. **Create Rooms**: Start your own study room on a specific topic
5. **Communicate**: Exchange messages with other participants
6. **Manage Profile**: Update your profile information and preferences

## 🔒 User Roles

- **Regular Users**: Can create profiles, join rooms, and participate in discussions
- **Room Hosts**: Can create, edit, and delete their own rooms
- **Admin**: Has full access to all features and management capabilities

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact

Your Name - [bansalsujal2021@gmail.com](mailto:your.email@example.com)

Project Link: [https://github.com/sujal-bansal/StudyBud-BlogApp.git](https://github.com/yourusername/studybud)

---

Happy Studying! 🎓
