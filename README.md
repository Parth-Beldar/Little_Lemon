# Little_Lemon
Little Lemon Restaurant API - Back-End Developer Capstone Project

## API Endpoints for Peer Testing:
1. User Registration & Authentication:
   - Register User: POST /auth/users/
   - Login / Obtain Token: POST /auth/token/login/
   - Logout / Destroy Token: POST /auth/token/logout/

2. Menu Items:
   - List & Create Menu Items: GET, POST /api/menu-items/
   - Retrieve, Update, Delete Menu Item: GET, PUT, DELETE /api/menu-items/{id}/

3. Table Bookings:
   - List & Create Bookings: GET, POST /api/bookings/tables/
   - Retrieve, Update, Delete Booking: GET, PUT, DELETE /api/bookings/tables/{id}/

## Running Unit Tests:
Run the test suite using:
python manage.py test restaurant
