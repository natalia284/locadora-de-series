# :movie_camera: Sistema de Cadastro Séries
O projeto desenvolvido em Laravel faz o cadastro e exposição de séries. Utilizou-se Blade para compor o frontend.

# :anchor: Endpoints 
Os endpoints do projeto se encontram em `routes/web.php`. Você pode utilizar o Postman para consumir a API. 

# :gear: Configuração
A instalação da API está descrita a seguir: 
```bash
# Instalando as dependẽncias usando o Composer
composer install

# Na pasta /database crie o banco de dados SQLite
touch banco.sqlite

# Em seguida, crie as migrations utilizando o artisan
php artisan migrate

# Inicie o servidor na porta 8080
php artisan serve --port=8080
```
