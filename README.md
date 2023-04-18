# Kafka Learning Project
This project is a tutorial on how to set up and use Kafka, a distributed streaming platform, using Docker.<br>
This project/tutorial covers the basics of creating and managing Kafka topics, producing and consuming messages, and configuring consumer groups. By following the steps in this tutorial, I was able to gain a solid understanding of Kafka's core concepts and now I'm able to apply them in future projects.

You can also find my notes about the basics of Apache Kafka <a href="https://medium.com/@grisonrf/understanding-apache-kafka-42100d569a1a">here</a> and <a href="https://medium.com/@grisonrf/basic-concepts-of-kafka-e4eff0db4acd">here</a>.

## Getting Started
To get started with this project, you need to have Docker installed on your machine. If you don't have Docker, you can download it from the official website `https://www.docker.com/products/docker-desktop`. Once you have Docker installed, follow these steps:

2- Clone this repository:<br>
Clone this repository to your local machine using `git clone https://github.com/GRISONRF/apache-kafka-studies.git`.<br>

3- Navigate to the project directory: <br>
In your terminal or command prompt, navigate to the directory where you cloned the repository.<br>

4- Run Docker:<br>
Execute the following command from this directory: <br>
`docker-compose -f kafka-single-node.yml up -d`.<br>

5- Check if the containers are up and running: <br>
Run the command `docker ps` to see if the Kafka containers are up and running.<br>

6- Start producing and consuming messages:<br>
Now that Kafka is up and running, you can start producing and consuming messages by following the steps provided under `resources`.<br>

7- Shutdown and remove the setup: <br>
When you're finished, execute this command in the same directory:<br>
`docker-compose -f kafka-single-node.yml down`.<br>


## Usage
This project provides a step-by-step guide on how to use Kafka, including creating and managing Kafka topics, producing and consuming messages, and configuring consumer groups. It's a great resource for beginners like me, who want to learn about Kafka's core concepts and use them in their projects.


