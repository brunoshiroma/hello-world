# Hello World, Erlang
Tested on Ubuntu 20.04 Erlang/OTP 22 - From official Ubuntu repo

## Running
```shell
erlc hello_world.erl
erl -noshell -s hello_world start -s init stop
```