# Nginx, MySQL, PHP for Docker

## How to use

1. Build the image

```
docker-compose build;
```

2. Run the image

```
docker-compose up -d;
```

3. Create your php file

```
mkdir -p app/public
echo "<?='Hello'?>" > app/public/index.php
```

4. Or, create your laravel app

```
docker-compose exec app composer create-project laravel/laravel --prefer-dist app
```

5. Now, you can point your browser to localhost, http://localhost:8000/

Thats it. The boilerplate is running.

Enjoy.
