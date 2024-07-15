<h2>E-com set-up instruction on localhost</h2>
<br>
<h2>##step:</h2>
1. open command prompt from where you open the folder.
2. composer install or composer update
3. open project in your desired IDE(eg.VS CODE)
4. rename .env.example file as .env
5. Create a database & name as E-com
6. update .env file.Database name should similar with your created database name .
7. php artisan migrate
8. php artisan key:generate
9. php artisan storage:link
10. npm install
11. npm run dev
12. php artisan migrate
13.Now browse the E-com. If you register as user role should be 2 .and for admin role should be 1.(you also direct change this role  from mysql database)
User only see the products and buy and Admin can do Create,Update,Delete.
If you new register then it will go a profile page (if you cannt get design .just browse the url eg.http://127.0.0.1:8000/ )Then you see the functionality with design.
