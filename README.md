# apache-kafka-studies



# Getting Started
To run this Kafka project, please follow these steps:

1- Install Docker: <br>
If you haven't already, download and install Docker from the official website at<br>
`https://www.docker.com/products/docker-desktop`.

2- Clone this repository:<br>
Clone this repository to your local machine using `git clone https://github.com/your-username/your-repo.git`.<br>

3- Navigate to the project directory: <br>
In your terminal or command prompt, navigate to the directory where you cloned the repository.<br>

4- Run Docker:<br>
Execute the following command from this directory: <br>
`docker-compose -f kafka-single-node.yml up -d`.<br>

5- Check if the containers are up and running: <br>
Run the command `docker ps` to see if the Kafka containers are up and running.<br>

6- Start producing and consuming messages:<br>
Now that Kafka is up and running, you can start producing and consuming messages.<br>

7- Shutdown and remove the setup: <br>
When you're finished, execute this command in the same directory:<br>
`docker-compose -f kafka-single-node.yml down`.<br>

That's it! With these steps, you should be able to set up and run this Kafka project on your local machine.


