# Bookinfo details service

Details service has been developed on Ruby

## License

MIT License

## Prerequisite

* Ruby 2.7

## How to run
```bash

ruby details.rb 8081
```

## How to run with Docker
```bash
# Build Docker Image for details service
docker build -t details .

# Run details service on port 8081
docker run -d --name details -p 8081:8081 details
```

## How to run with Docker Compose

```bash
docker-compose up
```