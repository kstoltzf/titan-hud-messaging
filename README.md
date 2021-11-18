**DISCLAIMER: This code should not be used for production environments or environments where sensitive data will be stored since it uses the default access credentials.**

# titan-hud-messaging
RabbitMQ messaging for the TITAN HUD project


# Building and Running with Docker

* Build the image: `docker build -t titan-hud-messaging .`
* Run the container: `docker run -d -p 5672:5672 -p 15672:15672 --name titan-hud-messaging titan-hud-messaging`

# Accessing the UI

* Navigate to [RabbitMQ](http://localhost:15672)
* Login with the default RabbbitMQ credentials
    * username = guest
    * password = guest

# Queue and Message Information

* abs-warning-light
    * Controls the state of the ABS warning light
    * Data Type: boolean
* battery-light
    * Controls the state of the battery light
    * Data Type: boolean
* brake-warning-light
    * Controls the state of the brake warning light
    * Data Type: boolean
* check-engine-light
    * Controls the state of the check engine light
    * Data Type: boolean
* coolant-temperature-light
    * Controls the state of the coolant temperature light
    * Data Type: boolean
* fuel-gauge
    * Controls the state of the fuel gauge
    * Data Type: number
* low-fuel-light
    * Controls the state of the low fuel light
    * Data Type: boolean
* oil-pressure-light
    * Controls the state of the oil pressure light
    * Data Type: boolean
* speedometer
    * Controls the state of the speedometer
    * Data Type: number
* tachometer
    * Controls the state of the tachometer
    * Data Type: number
* temperature-gauge
    * Controls the state of the temperature gauge
    * Data Type: number
* traction-control-light
    * Controls the state of the traction control light
    * Data Type: boolean

