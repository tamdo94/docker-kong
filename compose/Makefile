kong-postgres:
	COMPOSE_PROFILES=database KONG_DATABASE=postgres docker-compose up -d

kong-dbless:
	docker-compose up -d

clean:
	COMPOSE_PROFILES=database KONG_DATABASE=postgres docker-compose kill
	COMPOSE_PROFILES=database KONG_DATABASE=postgres docker-compose rm -f
