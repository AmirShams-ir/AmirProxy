# AmirProxy

A simple and lightweight VPN over SOCKS5 proxy for Android. AmirProxy is based on the upstream SocksTun project and keeps the original networking engine intact while applying the Amir family branding.

## Features

* Redirect TCP connections.
* Redirect UDP packets.
* Simple username/password authentication.
* Specifying DNS addresses.
* IPv4/IPv6 dual stack.
* Global/per-App modes.

## How to Build

```bash
git clone --recursive https://github.com/AmirShams-ir/sockstun
cd sockstun
gradle assembleDebug
```

## Upstream

Based on [SocksTun](https://github.com/heiher/sockstun) by hev and contributors.

## License

MIT
