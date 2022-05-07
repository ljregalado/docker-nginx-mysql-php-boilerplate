# Nginx, MySQL, PHP for Docker

## How to use

1. Copy and customize the configuration options

```
cp .env.example .env
```

2. Build the image

```
docker-compose build;
```

3. Run the image

```
docker-compose up -d;
```

4. Create your php file

```
mkdir -p app/public
echo "<?='Hello'?>" > app/public/index.php
```

5. Or, create your laravel app

```
docker-compose exec app composer create-project laravel/laravel --prefer-dist app
```

5. Now, you can point your browser to localhost, http://localhost:8000/

Thats it. The boilerplate is running.

Enjoy.
