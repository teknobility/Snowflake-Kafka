## This branch is to hold any UMLs/Diagrams
This repository contains items UML diagrams and the source code for the same.
# DB_KAFKA_SNOWFLAKE.*
These files represent use case scenarios for end to end integration between source of customer data to data warehouse (snowflake).

# KSQL_STREAM.* 
These files represnt the current state of POC with KSQL. They represent how data from two tables/databases are brought into Kafka topics and then joined into one enriched customer account relationship topic. This new topic can act as single source of truth if all customer and account information is dumped into the customer and account topics.
