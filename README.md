# Marcação de pontos no mapa
Micro aplicação web que possibilita marca pontos de interesse no mapa.

## Tecnologia
### Front-End
- [Node]()
- [VueCLI]() 
- [Vuetify]() 
- [Axios]() 
- [Leaflet]()

### Back-End
- [PHP]()
- [Lumen]()
- [PostgreSQL]()

## Inicar o projeto
### back-End
Após clonar o repositório abra o termianl na pasta raiz da aplicação e execute esses comandos:
```php
cd api
cp .env.exemple .env
compose install
```

Após executar esses comandos, vamos executar as migrations, assim irá criar as tabelas do banco de dados:
```php
php artisan migrate
```
Após executar as migrations, vamos executar a aplicação:
```php
php artisan serve
```
A aplicação está rodando em `localhost:8000`;

### Front-End
Na pasta raiz da aplicação execute esses comandos:
```npm
cd client
npm i
```

Para starta a aplicação, execute esse comando:
```npm
npm run serve
```

A aplicação vai está rodando em `localhost:8080`.

## Video demonstrativo

![Watch the video](https://youtu.be/XaNIttsvxGA)
