**DISCLAIMER: This code should not be used for production environments or environments where sensitive data will be stored since it uses the default access credentials.**

# titan-hud-messaging
RabbitMQ messaging for the TITAN HUD project


# Building and Running with Docker

* Build the image: `docker build -t titan-hud-messaging .`
* Run the container: `docker run -d -p 5672:5672 -p 15672:15672 titan-hud-messaging`

# Accessing the UI

* Navigate to [RabbitMQ](http://localhost:15672)
* Login with the default RabbbitMQ credentials
    * username = guest
    * password = guest
