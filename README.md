PHP_SocketIO_Client
===================

EN: PHP client for socket.io (websocket client)

How to use:
```
$socketio = new SocketIO();
if ($socketio->send('localhost', 9090, 'message','Hello world!')){
    echo 'we sent the message and disconnected';
} else {
    echo 'Sorry, we have a mistake :\'(';
}
