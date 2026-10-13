# [viltrum](https://github.com/Tuntii/viltrum) Benchmarking Test

Viltrum is an HTTP framework for V with its own HTTP/1.1 engine. This test runs one process with
one epoll loop per CPU (`epoll_cores`, `SO_REUSEPORT`).

### Test Type Implementation Source Code

* [JSON](main.v)
* [PLAINTEXT](main.v)

## Test URLs

### JSON

http://localhost:8080/json

### PLAINTEXT

http://localhost:8080/plaintext
