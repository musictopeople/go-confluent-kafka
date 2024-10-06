# go-confluent-kafka

This is the Confluent Go example with a couple nice add ons.

I work on a linux computer so this is how I start the project up and tear it down

```bash
# Start local Kafka
cd bootstrap
sudo docker-compose -f local-kafka.yml up -d
```

```bash
# Remove local Kafka
sudo docker-compose.yml down

# or manually remove them
sudo docker rm kafka -f
sudo docker rm zoo -f
```
The Producer and Consumer are in the same project so you can run it locally and see the message be consumed after it is published

### Check out the actual Kafka Confluent Page for more info

[Confluent Kafka For Golang](https://developer.confluent.io/get-started/go/)
[Here is the documentation](https://github.com/confluentinc/confluent-kafka-go/blob/master/kafka/kafka.go)
