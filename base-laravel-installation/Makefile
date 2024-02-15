setup:
	@make build
	@make up
	@make install

build:
	docker-compose build

up:
	docker-compose up

install:
	docker exec app bash -c "composer install"

migrate:
	docker exec app bash -c "php artisan migrate"