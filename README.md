cp .env.example .env
docker-compose up -d
rebuild: docker-compose build --no-cache 
