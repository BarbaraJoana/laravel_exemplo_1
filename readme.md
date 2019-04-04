<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>
<p align="center">Projeto disponível em: https://laravelexemplo.herokuapp.com/</p>

### Pré requisitos

- instalar composer
  * https://getcomposer.org/Composer-Setup.exe
- criar projeto
  * $composer create-project laravel/laravel laravelexemplo
- adicionar projeto ao GitHub
  
### Após adicionar projeto ao GitHub

- remover arquivo <strong>.env</strong> de <strong>gitignore</strong>

### Adicionar projeto ao heroku

- criar arquivo <strong>Procfile</strong> na raiz do projeto e adicionar código:
  * web: vendor/bin/heroku-app-apache2 public/
- criar app no heroku
  
### Outros comandos:

- verificar se composer está instalado
  * $composer -v
- criar servidor
  * $php artisan serve
- cria autentificação
  * $php artisan make:auth
  
### Baixar projeto:

- após fazer clone, executar na pasta do projeto para instalar dependências
  * $composer install
- gerar uma chave para a aplicação funcionar
  * $php artisan key:generate
