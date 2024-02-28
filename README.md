# ws_chat-master

- composer update
- copy .env.example .env
  
  DB_CONNECTION=mysql
  DB_HOST=localhost
  DB_PORT=3306
  DB_DATABASE=database_name
  DB_USERNAME=database_username
  DB_PASSWORD=database_password
  
- php artisan key:generate
- php artisan migrate
- npm install
- npm run dev 
