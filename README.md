# Laravel-6-Google-ReCAPTCHA-Form-Validation-Example
In this project, i will create simple registration form and implement google captcha code in Laravel  for my 100daysofcode 

# USAGE
- Clone the repository with ```git clone```
- Run ```composer install```
- Run ```composer require anhskohbo/no-captcha``
- Run ```php artisan key:generate```
- Copy ```.env.example``` file to ```.env```
- configure your [Google API Key](https://www.google.com/recaptcha/admin)
- open .env file and add this two variable: 
    ```NOCAPTCHA_SITEKEY=[site-key]```
    ```NOCAPTCHA_SECRET=[secret-key]```
- Open your terminal in the folder and run ```php artisan serve```
- Open your browser and type ```http://127.0.0.1:8000/site-register```
