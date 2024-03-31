
CURRENCY CONVERSION SERVICE

This project can also be run from command line 
Only docker compose file is needed and docker desktop should be installed
Run following command in terminal from file location of docker-compose.yaml

docker-compose up


APIs

Currency Exchange Service
- http://localhost:8765/currency-exchange/from/USD/to/INR

Currency Conversion Service
- http://localhost:8765/currency-conversion-feign/from/USD/to/INR/quantity/10

Eureka Server 
- http://localhost:8761/

Zipkin Trace(Docker Only
- http://localhost:9411/zipkin/