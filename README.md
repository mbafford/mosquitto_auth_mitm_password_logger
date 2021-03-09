Placeholder for a plugin for Mosquitto that uses the auth plugin framework to log the username/password a client is using to authenticate with. 

Hopefully entirely unnecessary, but I could only make Mosquitto log the username, not the password.

Context, MITM (Man in the Middle) attacking an IOT product brought into my house so I can monitor/manipulate the behavior of the device without relying on the external server.

The repository this is forked from accomplishes that, with some issues: 1) it tries to do actual authentication, which I don't care about 2) it doesn't compile against recent mosquitto builds.
