# muping

__muping__ is a tool written in `Python` to ping multiple hosts.

I like ping command interface, and I was bored to open/split tabs to ping multiple hosts, so I created a wrapper to do so.

It supports IPv4 and IPv6.

### Compiling

First clone the repo and `cd` into the directory:

```bash
$ git clone https://github.com/sevi42/muping 
$ cd muping && chmod +x muping
```

## Usages

Simply run:

```bash
$ ./muping 127.0.0.1,10.42.42.42
```

and we are done here, it will split your window in 2 subwindows and ping the given hosts.

You can change the split view by pressing `<1>` or `<2>` on your keyboard

To quit, you can press `<q>` on your keyboard, and `<ctrl+c>` to send SIGINT signal to all process
