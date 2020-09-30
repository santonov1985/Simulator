restart:
	docker-compose down && docker-compose up -d

migrate:
	docker-compose exec -T php-fpm php artisan migrate

fresh:
	docker-compose exec -T php-fpm php artisan migrate:fresh

up:
	docker-compose up -d

down:
	docker-compose down

php-bash:
	docker-compose exec php-fpm bash
