## Documentation

## Gropu MEMBERS
ODOCH NELSON OCHAN	  23/U/16508/EVE	2300716508
NAMUJJU SHAMIM	      23/U/1134	        2300701134
MASEREKA BRIGHT	      23/U/0738	        2300700738
KUTENTSA HAPPY	      23/U/0654	        2300700654
KASEMIIRE BRIDGET	  23/U/27044	    2300727044

CONFIGURATION FILES
Here are the steps to run the web app:

First, you need to set up the environment:
    - cp .env.example .env

2. Install PHP dependencies:
    - composer install

3. Generate application key:
    - php artisan key:generate

4. Run database migrations (make sure your database is configured in .env first):
        - php artisan migrate

5. To run the application, you'll need two terminal windows:
    In the first terminal, run the Laravel development server:
         - php artisan serve

6. In the second terminal, run the Vite development server for the frontend:
        - npm run dev


