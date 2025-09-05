# Movie Booking System

A Django-based movie ticket booking system inspired by BookMyShow.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-booking-system.git
   cd movie-booking-system
   ```

2. Create virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Setup environment variables:
   - Create `.env` file in root directory
   - Add required environment variables:
     ```env
     SECRET_KEY=your-secret-key
     DEBUG=True
     DATABASE_URL=sqlite:///db.sqlite3
     ALLOWED_HOSTS=localhost,127.0.0.1
     ```

5. Run migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. Create superuser:
   ```bash
   python manage.py createsuperuser
   ```

7. Run server:
   ```bash
   python manage.py runserver
   ```

## Features

- User Authentication & Authorization
- Movie Listings and Details
- Interactive Seat Selection
- Secure Ticket Booking
- Payment Integration
- Booking History

## Project Structure

```
movie-booking-system/
├── movies/              # Movie app
├── users/              # User authentication app
├── templates/          # HTML templates
├── static/            # Static files (CSS, JS, images)
├── media/             # User uploaded content
├── manage.py          # Django management script
├── requirements.txt   # Project dependencies
├── .env              # Environment variables
├── .gitignore        # Git ignore rules
└── README.md         # Project documentation
```

## Tech Stack

- Backend: Django 5.2.6
- Frontend: HTML5, CSS3, Bootstrap
- Database: SQLite/PostgreSQL
- Authentication: Django Auth
- Payment: Integration Ready

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.