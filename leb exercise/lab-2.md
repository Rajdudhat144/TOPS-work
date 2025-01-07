Research and create a diagram of how data is transmitted from a client to a server
over the internet.

           +----------------+       HTTP Request       +-------------------+
|   HTTP Client  |  --------------------->  |    HTTP Server    |
|                |                           |                   |
|  (e.g., Browser|                           | (e.g., Web Server)|
|   or App)      |                           |                   |
|                |                           |                   |
|   1. Sends     |                           |  2. Receives      |
|      Request   |                           |     Request       |
+----------------+                           +-------------------+
       ^                                               |
       |   3. Processes the request                   |
       |   and prepares the response                   |
       |                                               |
       |   <--------------------- HTTP Response -----|
       |                                               |
+----------------+       HTTP Response      +-------------------+
|   HTTP Client  |  <---------------------  |    HTTP Server    |
|                |                           |                   |
|  (e.g., Browser|                           | (e.g., Web Server)|
|   or App)      |                           |                   |
|                |                           |                   |
|   4. Receives  |                           |  5. Sends Response|
|      Response  |                           |                   |
+----------------+                           +-------------------+
