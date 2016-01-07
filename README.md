## docker-test

A simple java web application runing in Docker container.

$docker build -t dejan/pingpong .

$docker run -d -p 8080:8080 dejan/pingpong

$curl http://localhost:8080/ping

If all goes well, you should see the response:
$pong
