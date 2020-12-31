# email-signatures
PHP Laravel 5.8 email signatures system

## Tecnologias adotadas
- Framework de ORM, **Laravel**, 5.8.
- Frontend nativo, em Blade
- Banco de dados MySql.
- Apache local, XAMMP ou HTTP Apache
- Todas as tecnologias listadas acima podem ser executadas em apache local ou servidor cloud/hospedagem.

## Para executar o laravel em um apache:
1. criar um banco de dados com o configurar no arquivo .env na raiz:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=yourbd
DB_USERNAME=root
DB_PASSWORD=yourpass

2. abrir o cmd na raiz do projeto

3. Para regenerar corretamente as classes e seus componentes:
``` $ composer dump-autoload ``` 

4. Para executar criar as tabelas no banco de dados usamos o migration:
``` $ php artisan migrate ``` 

5.  Para popular o banco de dados executamos o seeder:
``` $ php artisan db:seed ```

6. iniciar o laravel com:
``` $ php artisan serve ```

O aplicativo(local) irá executar em http://127.0.0.1:8000
