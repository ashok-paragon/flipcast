Flipcast - Push Messaging platform
==================================

About
-----
A scalable & easily customizable push messaging platform for mobile, devices and web.

Supported platforms:
* iOS
* Android
* Windows Phone 8 (WIP)

Supported Features:
* Device register/unregister API
* Configurable push message payloads
* Automatic housekeeping for invalid devices
* Automatic/Transparent retry and sidelining
* Message history management
* Pluggable data source (Default: MongoDB)
* Automatic backpressure management

Library Dependencies
--------------------
* spray 1.2.0
* Scala 2.10.2
* Akka 2.2.4
* amqp-client - 1.3-ML4
* apns - 0.2.3

Infrastructure Dependencies
---------------------------
* RabbitMQ
* MongoDB


