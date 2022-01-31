<h1 align="center">  Binance Proxy</h1>
<p align="center">
A fast and simple <b>Websocket Proxy</b> for the <b>Binance API</b> written in <b>GoLang</b>. Mimics the behavior of API endpoints to avoid rate limiting imposed on IP's when using REST queries. Intended Usage for multiple instances of applications querying the Binance API at a rate that might lead to banning or blocking, like for example the <a href="https://github.com/freqtrade/freqtrade">Freqtrade Trading Bot</a>, or any other similar application. </p>

<p align="center"><a href="https://github.com/nightshift2k/binance-proxy/releases" target="_blank"><img src="https://img.shields.io/github/v/release/nightshift2k/binance-proxy?style=for-the-badge" alt="latest version" /></a>&nbsp;<img src="https://img.shields.io/github/go-mod/go-version/nightshift2k/binance-proxy?style=for-the-badge" alt="go version" />&nbsp;<img src="https://img.shields.io/tokei/lines/github/nightshift2k/binance-proxy?color=pink&style=for-the-badge" />&nbsp;<a href="https://github.com/nightshift2k/binance-proxy/issues" target="_blank"><img src="https://img.shields.io/github/issues/nightshift2k/binance-proxy?color=purple&style=for-the-badge" alt="github issues" /></a>&nbsp;<img src="https://img.shields.io/github/license/nightshift2k/binance-proxy?color=red&style=for-the-badge" alt="license" /></p>

## ⚡ Quick Start

```bash
docker pull pnmice/binanceus-proxy:1.2.4
```

## 🙏 Credits
+ [@adrianceding](https://github.com/adrianceding) for creating the original version, available [here](https://github.com/adrianceding/binance-proxy).
+ [@nightshift2k](https://github.com/nightshift2k) for creating the original version, available [here](https://github.com/nightshift2k/binance-proxy).
## ⚠️ License

`binance-proxy` is free and open-source software licensed under the [MIT License](https://github.com/nightshift2k/binance-proxy/blob/main/LICENSE). 

By submitting a pull request to this project, you agree to license your contribution under the MIT license to this project.

### 🧬 Third-party library licenses
+ [go-binance](https://github.com/adshao/go-binance/blob/master/LICENSE)
+ [go-flags](https://github.com/jessevdk/go-flags/blob/master/LICENSE)
+ [logrus](https://github.com/sirupsen/logrus/blob/master/LICENSE)
+ [go-time](https://cs.opensource.google/go/x/time/+/master:LICENSE)
+ [go-simplejson](https://github.com/bitly/go-simplejson/blob/master/LICENSE)
+ [websocket](https://github.com/gorilla/websocket/blob/master/LICENSE)
+ [objx](https://github.com/stretchr/objx/blob/master/LICENSE)
+ [testify](https://github.com/stretchr/testify/blob/master/LICENSE)