# Kafka_Assignment

Produce a user message into a Kafka topic and consume it using the Kafka Consumer APIs. Once the
message is consumed from a consumer, it should be sinked(written) into a file.
Message structure would be like this.
1. Message Structure
2. User message ---&gt;{&quot;id&quot;:&quot;1&quot;,&quot;name&quot;:&quot;some_name&quot;,&quot;age&quot;:&quot;24&quot;,&quot;course&quot;:&quot;BTech.&quot;}
// serialized
User user = new User (“id”, “1”, “any_name”, “age”, “25”, “course”,”Btech”); // deserialized
