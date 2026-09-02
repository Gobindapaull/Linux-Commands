# Linux Network Commands

## Install `net-tools`

```bash
sudo apt install net-tools
```

* `net-tools` → Networking utilities

## `ifconfig`

```bash
ifconfig
```

* `eth0` → Network interface name
* `inet` → IPv4 address

## Modern Ubuntu

`ifconfig` is a legacy command. On modern Ubuntu, use:

```bash
ip addr
```

or:

```bash
ip a
```
