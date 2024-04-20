# laravel-portfolio
Personal Portfolio site made using Laravel
>*Linux is only free if your time has no value*
## how to run this website on your local machine
1. ```git clone https://github.com/KevinLubbers/laravel-portfolio.git```
2. cd into cloned repo and run ```composer install``` command
3. ```cp .env.example .env```
4. run ```vendor/bin/sail up -d``` command
	- instead of typing vendor/bin/sail over and over again you can create an alias
	- in ~/.bashrc or ~/.zshrc paste the following code to shorten "vendor/bin/sail" to just "sail"

	- ```alias sail='sh $([ -f sail ] && echo sail || echo vendor/bin/sail)'```

5. run ```vendor/bin/sail npm install```
6. run ```vendor/bin/sail php artisan key:generate```
7. run ```vendor/bin/sail php artisan migrate```
8. run ```vendor/bin/sail npm run dev```
9. open web browser and visit localhost
 


