Client - CURL

curl -v -X POST  -d "{\"name\":\"Join the Slack community\"}" -H "Idempotency-Key:94a980d2-5a78-48bf-af43-41bb9029631ec"  -H "Content-Type: application/json" http://localhost:8080/tasks



Kafka topics

1. test2 - takes the input.
2. output-topic1 - Has inputs provided to test2 and then grouped by key and summed.
