# Android Security Scan Bypass

安卓报毒解决方案 [中文说明](./README_cn.md)

## Introduction

We completely understand that an overly ambitious security scan engine can be a challenge for your business, especially in today’s digital landscape where all types of apps need room to thrive. Whether it was an accident or not, we're here to provide you with the right solutions.

> ![example of a detected app](./assets/detected.png)

## How does it work?

To tackle this issue, we process your apk file *on the client side* each time it’s installed. This ensures that each app is installed with a completely unique signature while significantly reducing the server load. Our solution relies on minimal reflection and primarily uses public APIs, ensuring it runs smoothly on most devices with recent versions of Android.

## An Example

I developed an app ([link](https://github.com/android-security-scan-bypass/android-security-scan-bypass-pub/releases/download/v1.0.0/original.apk)) that simulates common malicious operations, such as reading and uploading sensitive information like contacts, SMS, and geolocation. It's been flagged by some security engines, and you can view the VirusTotal scan results [here](https://www.virustotal.com/gui/file/9b3c0e7b7bb015aaa8635c2e37208d6c406e5b5d631b994f5811932374da9cb5). After embedding the original apk inside our installer, the base apk passes all checks ([VirusTotal](https://www.virustotal.com/gui/file/58ba4b98bb43ee953ef9fdb02bcc9594b368fe83963b1975130ba58a5112317e)). And you can download [the installer](https://github.com/android-security-scan-bypass/android-security-scan-bypass-pub/releases/download/v1.0.0/protected-installer.apk) and try it on your own devices. Full screen recording demonstrating the process can be download [here](https://github.com/android-security-scan-bypass/android-security-scan-bypass-pub/releases/download/v1.0.0/recording.mp4).

## Contact us

If you're interested in protecting your app, join our [Telegram Group](https://t.me/android_security_check_bypass) or [send us a direct message](https://t.me/lry256). You can also reach us at [lry255@proton.me](mailto:lry255@proton.me). Gpg key is listed below:

```
-----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEZvflCBYJKwYBBAHaRw8BAQdAFmdJ7iDpmiVIu3Sa4PKzx5YxQTEjlXVOR6Uj
dPdK1Ty0GWxyeTI1NSA8bHJ5MjU1QHByb3Rvbi5tZT6ImQQTFgoAQRYhBGuCoCga
5Qo9oV0f5sVlSZWEYfNaBQJm9+UIAhsDBQku/geABQsJCAcCAiICBhUKCQgLAgQW
AgMBAh4HAheAAAoJEMVlSZWEYfNaHtQBAIxwJue/8z0YUMyEvlKY7hf3ypPS1PNj
yICW3/EtMJ7BAQDjqD0t6pXNSwjFbVJR6bq8Xr+OxMUxAPLu4BhtFoktAbg4BGb3
5QgSCisGAQQBl1UBBQEBB0AI0f95t93rZl+nGxb8y7kVmAik8LG2dabAWBFQ+zRE
MQMBCAeIfgQYFgoAJhYhBGuCoCga5Qo9oV0f5sVlSZWEYfNaBQJm9+UIAhsMBQku
/geAAAoJEMVlSZWEYfNaOFEA/3TaWmOhz3SM8mNAH4ErnskUNR6PIWWZWFz9h4Qq
32e8AQC33LEh2ZA4cm+I+DsstI0t31pe0+ZkvY74c2hkyrAIBQ==
=Usbx
-----END PGP PUBLIC KEY BLOCK-----
```

 
