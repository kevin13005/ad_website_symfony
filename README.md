TUTORIAL :

Elements of the project :
- Create an user entity with make:user
- Authentificate it on a secure way with make:auth
- Registrate user and send a confirmation email with make:registration-form
- Give possibility to user to reset his password with make:reset-password
- Add category to database by creating a form with make:form
- Enable users getting changes on their content's style who is published with ckeditor bundle
- Enable user to change his profile editing his name or firstname or password


RUN IN LOCAL :

- tap on terminal --> git clone https://github.com/kevin13005/ad_website_symfony.git
- in terminal --> php -S 127.0.0.1:8000 -t public
- go to navigator
- localhost:8000 for home page
- localhost:8000/users for user page
- localhost:8000/register to register an user
- localhost:8000/admin/categories/ajout to add a categorie in database


INSTALL PACKAGES :

- composer require symfonycasts/verify-email-bundle 
- composer require symfonycasts/reset-password-bundle
- composer require antishov/doctrine-extensions-bundle
- composer require friendsofsymfony/ckeditor-bundle   
- symfony console ckeditor:install 
- assets:install public 
