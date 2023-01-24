# hamkorbank


### Requirements
1. Docker
2. Docker compose management
3. Golang version 1.8


## Follow guide below

### Clone all 4 repository
1. [Devops](https://github.com/abrorbeksoft/hamkorbank_devops)
   ``https://github.com/abrorbeksoft/hamkorbank_rest_service``
2. [Trigger listener service](https://github.com/abrorbeksoft/hamkorbank_trigger_listener_service)
   ``https://github.com/abrorbeksoft/hamkorbank_trigger_listener_service``
3. [Logger service](https://github.com/abrorbeksoft/hamkorbank_logger_service)
   ``https://github.com/abrorbeksoft/hamkorbank_logger_service``
4. [Http Rest service](https://github.com/abrorbeksoft/hamkorbank_rest_service)
   ``https://github.com/abrorbeksoft/hamkorbank_rest_service``

### Devops
1. Run in terminal ``docker-compose up -d``

### Rest service
1. Run in terminal ``go mod tidy``
2. Run in terminal ``go mod vendor``
3. Run in terminal ``go run cmd/main``

### Logger service
1. Run in terminal ``go mod tidy``
2. Run in terminal ``go mod vendor``
3. Run in terminal ``go run cmd/main``


### Trigger listener service
1. Run in terminal ``go mod tidy``
2. Run in terminal ``go mod vendor``
3. Run in terminal ``go run cmd/main``