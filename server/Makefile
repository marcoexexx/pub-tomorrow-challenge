run:
	docker-compos -f ./docker-compose.yaml --env-file ./.production.env pull
	docker-compos -f ./docker-compose.yaml --env-file ./.production.env up -d --build

dev:
	docker-compose -f ./docker-compose.local.yaml --env-file ./.production.env pull
	docker-compose -f ./docker-compose.local.yaml --env-file ./.production.env up --build
