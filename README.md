## Local 실행 환경
### MySQL, Redis, MongoDB start
`./tools` directory에서 \
`docker-compose up -d`

### MySQL, Redis, MongoDB stop
`docker-compose down`

### Spring Boot application 실행
`./gradlew bootRun`

## docker 실행 상태에서 DB/Redis 접근
### MySQL
`docker exec -it mytv-mysql bash` \
`mysql -u local -p`

### Redis
`docker exec -it mytv-redis sh` \
`redis-cli`

### MongoDB
`docker exec -it mytv-mongodb sh` \
`mongosh -u local -p local`
