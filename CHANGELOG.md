# Changelog

<!--next-version-placeholder-->

## 1.0.4
- Fixed BM6 devices no longer updating until the Bluetooth proxy was restarted. Waiting for the device response now times out, so a lost notification no longer keeps the connection (and a connection slot of an ESPHome Bluetooth proxy) open forever. The connection is released and retried on the next update.

## 1.0.3
- Added support for multiple Bluetooth scanners/gateways. Now the BM6 device is supported by more than one Bluetooth scanner/gateway. The scanner with the best signal strength is automatically selected to connect to the BM6. If you have more than one scanner/gateway, this version is just for you.
## 1.0.2
- Improvement of code especially translation.
## 1.0.1
- Improvement of code especially translation.
## 1.0.0
- First release.