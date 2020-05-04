# bayard-rest start

## DESCRIPTION
Start REST server

## USAGE
bayard-rest start [OPTIONS]

## FLAGS
- `-h`, `--help`  
&nbsp;&nbsp;&nbsp;&nbsp; Prints help information.

- `-v`, `--version`  
&nbsp;&nbsp;&nbsp;&nbsp; Prints version information.

## OPTIONS
- `-H`, `--host` `<HOST>`  
&nbsp;&nbsp;&nbsp;&nbsp; Node address. [default: 0.0.0.0]

- `-p`, `--port` `<PORT>`  
&nbsp;&nbsp;&nbsp;&nbsp; HTTP service port number. [default: 8000]

- `-s`, `--server` `<IP:PORT>`  
&nbsp;&nbsp;&nbsp;&nbsp; Index service address. [default: 127.0.0.1:5000]

## EXAMPLES

To start a server with default options:

```shell script
$ bayard start --host=192.168.1.22 --port=8080 --server=192.168.1.12:5001
```