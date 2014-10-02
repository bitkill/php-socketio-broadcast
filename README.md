php-socketio-broadcast
===================
simple class to send messages from PHP to socket.io

How to use:
```
$socketio = new SocketIO();
if ($socketio->send('localhost', 9090, 'message','Hello world!')){
    echo 'we sent the message and disconnected';
} else {
    echo 'Sorry, we have a mistake :\'(';
}
```
Documentation
https://tools.ietf.org/html/rfc6455
