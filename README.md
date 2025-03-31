🛠️ Installation Guide
🔹 Step 1: Clone the Repository
git clone https://github.com/D071na/laravel-project.git
cd laravel-project
🔹 Step 2: Install Dependencies
composer install
npm install
🔹 Step 3: Environment Setup
cp .env.example .env
php artisan key:generate
Update .env with database credentials.

🔹 Step 4: Database Configuration
php artisan migrate --seed
Import database/crudposts.sql into your database manually (if needed).

🔹 Step 5: Run the Application
php artisan serve
🔗 Open http://localhost:8000

