<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

##Servidor Laravel Restfull

##Servidor restfull feito em Laravel para consumo de usuários.

1 - git clone https://github.com/thurdelima/Laravel-Restfull.git servidor

2 - Entrar no diretório servidor
3 - Configurar o banco de dados no arquivo .env.example (renomear para .env)
4-  Digitar e rodar o comando composer install e php artisan key:generate
5 - Digitar e rodar o comando php artisan migrate (banco de dados conectado!)
6 - Digitar e rodar o comando php artisan passport:install
7 - Copiar os clients ids gerados e colar no arquivo keys (guardar por precaução)
8 - Rodar o comando php artisan serve
9 - Clicar em register, crie uma conta
10 - Após a conta criada, crie um personal access token (usaremos ele para realizar o consumo do servidor no front). Caso ocorrer problema, crie um oauth e depois o personal access.

11 - Baixar o repositório Angular client for Laravel Restfull para realizarmos o consumo.

