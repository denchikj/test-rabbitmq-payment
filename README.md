# RabbitMQ payment process

Modeling the behavior of the payment process using RabbitMQ

## How to run?


```shell
docker-compose up -d
```

- Api

    ```bash
    cd ./Application/Api
    dotnet run
    ```

- PaymentProcessor

    ```bash
    cd ./Application/PaymentProcessor
    dotnet run
    ```

- Logger

    ```bash
    cd ./Application/Logger
    dotnet run
    ```

    or
    ```bash
    cd ./Application/Logger
    dotnet run | tee ../../payments.log
    ```
