# async-kafka-pipeline

# Python Kafka Producer Consumer

A simple real-time event streaming project built using Python and Apache Kafka.
This project demonstrates asynchronous Kafka producers and consumers using the Confluent Kafka Python client.

## Features

* Real-time Kafka producer
* Real-time Kafka consumer
* Async programming with asyncio
* Fake purchase event generation using Faker
* JSON serialization/deserialization
* Kafka topic communication
* Dataclass-based event modeling

---

## Tech Stack

* Python
* Apache Kafka
* Confluent Kafka Python Client
* asyncio
* Faker

---

## Project Structure

```bash
python-kafka-producer-consumer/
│
├── main.py
├── requirements.txt
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/python-kafka-producer-consumer.git
cd python-kafka-producer-consumer
```

### Install dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install confluent-kafka faker
```

---

## Start Kafka

Make sure Apache Kafka and Zookeeper are running locally.

Default Kafka broker:

```bash
localhost:9092
```

---

## Run the Project

```bash
python main.py
```

---

## Example Output

```bash
Produced: Purchase(username='john123', currency='USD', amount=5420)

Consumed: Purchase(username='john123', currency='USD', amount=5420)
```

---

## Concepts Covered

* Kafka Producer
* Kafka Consumer
* Event Streaming
* Serialization & Deserialization
* Async Tasks
* Consumer Groups
* Real-Time Data Pipelines

---

## Future Improvements

* Add Kafka topic auto-creation
* Add Docker support
* Integrate Apache Spark Streaming
* Add Stream Processing
* Add Logging & Monitoring
* Deploy on Cloud

---

## Author

Priyadarshi Gupta
