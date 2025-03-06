# Tweet Application

## Overview
The **Tweet Application** is a Django-based web app that allows users to register, log in, log out, and post tweets. Users can edit their own tweets, and all tweets are displayed on a dashboard. Additionally, users can search for tweets using keywords.

## Features
- **User Authentication**: Registration, Login, and Logout
- **Tweet Management**:
  - Post new tweets
  - Edit own tweets
  - View all tweets on the dashboard
- **Search Functionality**:
  - Users can search for tweets using keywords
- **Responsive Dashboard**: Displays tweets from all users

## Installation

### Prerequisites
Ensure you have the following installed:
- Python (>=3.8)
- Django (>=4.0)
- Git

### Steps to Set Up the Project

1. **Clone the repository**
   ```sh
   git clone https://github.com/harsh721827/Tweet-Application.git
   cd Tweet-Application
   ```

2. **Create and Activate a Virtual Environment**
   ```sh
   python -m venv venv
   # Activate the virtual environment:
   # On Windows:
   venv\Scripts\activate
   # On Mac/Linux:
   source venv/bin/activate
   ```

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Apply Migrations**
   ```sh
   python manage.py migrate
   ```

5. **Run the Development Server**
   ```sh
   python manage.py runserver
   ```

6. **Access the App**
   Open your browser and go to:
   ```
   http://127.0.0.1:8000/
   ```

## Usage

### Register & Login
- New users can register using the registration form.
- After registering, users can log in and access the dashboard.

### Tweet Management
- Users can create a tweet from the dashboard.
- Each user can edit only their own tweets.
- All tweets are displayed on the dashboard.

### Search Functionality
- Users can search for tweets using keywords to find specific tweets quickly.

### Logout
- Users can log out using the logout option.

## Contributing
If you'd like to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.


Enjoy tweeting! 🚀

