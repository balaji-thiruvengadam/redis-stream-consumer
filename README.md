Using redis-cli, create a stream and group

127.0.0.1:6379> XGROUP create purchase-events purchase-events $ MKSTREAM
OK
