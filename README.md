<h2>E-com set-up instruction on localhost</h2>
<br>
<h2>##step:</h2>
1. open command prompt from where you open the folder.<br>
2. composer install or composer update<br>
3. open project in your desired IDE(eg.VS CODE)<br>
4. rename .env.example file as .env<br>
5. Create a database & name as E-com<br>
6. update .env file.Database name should similar with your created database name .<br>
7. php artisan migrate<br>
8. php artisan key:generate<br>
9. php artisan storage:link<br>
10. npm install<br>
11. npm run dev<br>
12. php artisan migrate<br>
13.Now browse the E-com. If you register as user role should be 2 .and for admin role should be 1.(you also direct change this role  from mysql database)
User only see the products and buy and Admin can do Create,Update,Delete.
If you new register then it will go a profile page (if you cannt get design .just browse the url eg.http://127.0.0.1:8000/ )Then you see the functionality with design.
