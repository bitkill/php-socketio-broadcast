php-socketio-broadcast
===================
simple class to send messages from PHP to socket.io

How to use:
```
/**                     | server    | port */
$socketio = new SocketIO('127.0.0.1', 8080);;
/**                 | command |     data        */
if ($socketio->send('message','Hello world!')){
    echo 'we sent the message and disconnected';
} else {
    echo 'Sorry, we have a mistake :\'(';
}
```
Documentation
https://tools.ietf.org/html/rfc6455

Initially based on https://github.com/psinetron/PHP_SocketIO_Client
