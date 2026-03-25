This is a FLASK based application. To run the app, you would need to create an env file and place your credentials there for following placehodlers


Create a .env file in the root directory of your project:

# ---------------------------
# Database Configuration
# ---------------------------
DB_HOST=localhost
DB_PORT=3306
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_NAME=your_database_name

# ---------------------------
# API Configuration
# ---------------------------
TOGETHER_API_KEY=your_together_api_key
POLICIES_API_URL=https://insurance-crm-backend.vercel.app/api/policies
POLICIES_API_TOKEN=your_jwt_token_here
