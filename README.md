# Spotify Clone

A full-stack Spotify clone built with React (frontend) and Django (backend).

## Technologies Used

- **Frontend:** React, TypeScript, TailwindCSS, Redux Toolkit, Material UI
- **Backend:** Django, Django Rest Framework
- **Database:** SQLite (configured for local development)
- **Other:** Axios for API calls

## Features

- User authentication (login/register)
- Music playback
- Playlists management
- Artist and genre pages
- Search functionality
- Admin panel for content management

## Setup Instructions

### Prerequisites

- Python 3.8+
- Node.js 14+
- Git

### Backend Setup

1. Navigate to the backend directory:
   ```
   cd backend
   ```

2. Install Python dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run database migrations:
   ```
   python manage.py migrate
   ```

4. Create superuser (optional, for admin access):
   ```
   python manage.py createsuperuser
   ```

5. Start the Django server:
   ```
   python manage.py runserver
   ```

   The backend will run on http://localhost:8000

### Frontend Setup

1. Navigate to the frontend directory:
   ```
   cd frontend
   ```

2. Install Node.js dependencies:
   ```
   npm install
   ```

3. Start the React development server:
   ```
   npm start
   ```

   The frontend will run on http://localhost:3000

## Admin Panel

Access the Django admin panel at http://localhost:8000/admin/

Default credentials:
- Username: admin
- Password: admin

## API Documentation

Use the provided Postman collection (`Spotify.postman_collection.json`) for API testing and documentation.

## Screenshots

(Add screenshots here if available)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is for educational purposes.

### Admin Panel
![admin_panel](./screenshots/admin_panel.PNG)

### Admin Panel Customer
![admin_panel_customer](./screenshots/admin_panel_customer.PNG)

### Admin Panel Genre
![admin_panel_genre](./screenshots/admin_panel_genre.PNG)

we want to deploy 