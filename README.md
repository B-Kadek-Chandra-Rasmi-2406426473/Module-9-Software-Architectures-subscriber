# Subscriber

## Understanding Subscriber and Message Broker

### a. What is AMQP?
AMQP (Advanced Message Queuing Protocol) adalah protokol komunikasi jaringan yang memungkinkan aplikasi untuk berkomunikasi satu sama lain melalui perantara pesan (message broker). AMQP mendefinisikan format pesan, antrian, dan cara pengiriman pesan secara standar, sehingga aplikasi yang dibuat dengan bahasa berbeda pun bisa saling bertukar pesan.

### b. What does guest:guest@localhost:5672 mean?
- **guest** (pertama) = username untuk login ke RabbitMQ
- **guest** (kedua)  = password untuk login ke RabbitMQ
- **localhost:5672** = alamat dan port tempat RabbitMQ berjalan.
localhost artinya RabbitMQ berjalan di komputer yang sama, dan 5672 adalah port default protokol AMQP pada RabbitMQ.

