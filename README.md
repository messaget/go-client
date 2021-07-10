<p align="center">
  <img src="https://i.imgur.com/7dtHykL.png" />
</p>

This is a simple Client/Controller implementation for the [MessaGet Server](https://github.com/messaget/messaget-server). Please visit the main repository for details about the project. This library can be used to add real time listeners to your go applications and to publish data from services. Please note that you should never use the controller from public sources to protect your password and sensitive user data. Reverse-messaging (sending data from the client to a controller) is planned and will be added in the near future.


### Private Controller
The Controller is a privileged connection (using both REST and WebSocket) which is used to query clients, send data and manage connections. Websocket can be disabled, which would enable usage in headless workers (like cloudflare or fastly workers, to send messages from your backend service infrastructure)
