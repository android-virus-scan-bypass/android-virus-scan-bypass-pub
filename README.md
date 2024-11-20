# Google Play Protect Bypass (Android Virus Scan Bypass)

安卓报毒解决方案 [中文说明](./README_CN.md)

## Introduction

We completely understand that an overly ambitious security scan engine can be a challenge for your business, especially in today’s digital landscape where all types of apps need room to thrive. Whether it was an accident or not, we're here to provide you with the right solutions.

> ![example of a detected app](./assets/detected.png)

## How does it work?

To tackle this issue, we process your apk file *on the client side* each time it’s installed. This ensures that each app is installed with a completely unique signature while significantly reducing the server load. Our solution relies on minimal reflection and primarily uses public APIs, ensuring it runs smoothly on most devices with recent versions of Android.

## Tested Security Engines

Our solution is tested on real devices to bypass scans from the following security engines:

- Google Play Protect

- Ahnlab V3

- Mcafee

It will likely work well with other engines, as shown below. Feel free to contact us for a free trial of our installer and try it out yourself.

## An Example

We developed an app ([link](https://github.com/android-security-scan-bypass/android-security-scan-bypass-pub/releases/download/v1.0.0/original.apk)) that simulates common malicious operations, such as reading and uploading sensitive information like contacts, SMS, and geolocation. It's been flagged by some security engines, and you can view the VirusTotal scan results [here](https://www.virustotal.com/gui/file/9b3c0e7b7bb015aaa8635c2e37208d6c406e5b5d631b994f5811932374da9cb5). After embedding the original apk inside our installer, the base apk passes all checks ([VirusTotal](https://www.virustotal.com/gui/file/58ba4b98bb43ee953ef9fdb02bcc9594b368fe83963b1975130ba58a5112317e)). And you can download [the installer](https://github.com/android-security-scan-bypass/android-security-scan-bypass-pub/releases/download/v1.0.0/protected-installer.apk) and try it on your own devices. 

Complete screen recording demonstrating this process: 

https://github.com/user-attachments/assets/9a74b45e-f142-442e-b5d1-4c8033cd712d

## Contact us

- Recommended: the [telegram bot](https://t.me/google_protect_bypass_bot) (try it for free). 

- Price
  
  protect one apk for one month consumes one token
  
  - $35 for 1 token
  - $100 for 5 tokens
  - $500 for 35 tokens
  - let's chat if you have more than 70 apk or can't accept the monthly plan

If you're interested in protecting your app, [send us a direct message on Telegram](https://t.me/m/Vrkx6ng1MmJh). You can also reach us at [play-protect-bypass@proton.me](mailto:play-protect-bypass@proton.me) (optionally) encrypted with the GPG public key listed below:

```
-----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEZvrbKRYJKwYBBAHaRw8BAQdApMYCkhGrg8nJ1wC/MCHQdPT2xt29HiGbVbSq
eNB1sQS0Okdvb2dsZSBQbGF5IFByb3RlY3QgQnlwYXNzIDxwbGF5LXByb3RlY3Qt
YnlwYXNzQHByb3Rvbi5tZT6ImQQTFgoAQRYhBLM8aXFLSzHAqgcvKlIrif955Crn
BQJm+tspAhsDBQku/geABQsJCAcCAiICBhUKCQgLAgQWAgMBAh4HAheAAAoJEFIr
if955Crns2wA/jbAlrZtVP11aNHvERHCne3NgjquyIHyaR2fj43ZlnGxAP49RtMJ
WlfM/dXGQhzGB/+NkZFZ0q+FygJfK0wqfW6BBrg4BGb62ykSCisGAQQBl1UBBQEB
B0CqaCwWRUGgqHMHrO5c479kPWpM4vUVArkCX85I4XHIEwMBCAeIfgQYFgoAJhYh
BLM8aXFLSzHAqgcvKlIrif955CrnBQJm+tspAhsMBQku/geAAAoJEFIrif955Crn
NUUBAIYqWiAmUsSsxWlDUu02E6lcGfxETrryN0Qvdsaf8UIIAP9865wxleWEGU8h
gZgME+G1kY91nNTyu2ucn/G7Y8eAAQ==
=q6GV
-----END PGP PUBLIC KEY BLOCK-----
```

## Notice

If this GitHub repository is taken down, you can check out our website hosted on tor network for the latest updates.

- ```
  http://bypass7vckrcx6e3655el3a74236ixvxwtivhqirdh6rmrtaqvwzjqyd.onion/
  ```
