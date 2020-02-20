# Applications

## Application types

## [Entity-Relationship Diagram](https://en.wikipedia.org/wiki/Entity–relationship_model)

![Applications](./docs/erd.png?raw=true "Applications")

This ERD is made with [Database schema designer](https://github.com/Agontuk/schema-designer).

## Code generation

### [Laravel Migrations](https://laravel.com/docs/master/migrations) to [SQL](https://en.wikipedia.org/wiki/SQL)

```
php artisan migrate
```
### [SQL](https://en.wikipedia.org/wiki/SQL) to [Eloquent Models](https://laravel.com/docs/master/eloquent)

```
php artisan code:models
```
In the target project development environment this shell script is part of the [Reliese](https://github.com/reliese/laravel) [Laravel](https://github.com/laravel/laravel) package.