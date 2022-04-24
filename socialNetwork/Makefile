compose-up:
	docker-compose -p jfaro up -d

compose-down:
	docker-compose -p jfaro down

rebuild:
	docker build -t jfaro:test .

logs:
	docker logs jfaro_compose-post-service_1


.PHONY: compose-up compose-down rebuild logs