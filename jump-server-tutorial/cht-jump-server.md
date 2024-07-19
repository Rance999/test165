---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: false
  pagination:
    visible: true
---

# 📱 CHT jump server

<details>

<summary>Jump server  Instruction</summary>

#### This document primarily introduces the usage of the jump server.

&#x20; (1).Plantynet have the usage of a jump server for system maintenance to facilitate platform  switching   (fixed network/mobile network) or to use other maintenance-related jump servers.&#x20;

&#x20; (2).The required password may vary depending on the specific jump server being used.

&#x20; (3).To save time on password retrieval, we will directly provide the passwords for easier login.

&#x20; (4).We will first introduce the fixed network side before discussing the mobile network side.

</details>

## 1. Connection operation of the CHT jump server

&#x20; (1).First, click on the bottom-left corner of the desktop, then click on Remote Desktop Connection."

&#x20; (2).Remote Desktop Connection = 遠端桌面連線

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption><p>Picture-1  Remote Desktop Connection</p></figcaption></figure>

&#x20;(3).After selecting the jump server for the CHT jump server (210.65.193.115).

&#x20;     \-> Enter the password to establish the connection."

&#x20;     \-> Password is plantynet

&#x20;     \-> Connection = 連線(N)

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>Picture-2 210.65.193.115</p></figcaption></figure>

(4).Please fill in the corresponding fields in order.

&#x20;    \-> VPN Name: CHTS-SSL-VPN

&#x20;    \-> UserName: plantynet

&#x20;    \-> Password: fire\_in\_hole

&#x20;    \-> Client Certificate: plantynet / CHTSecurt-ServiceCA

(5).after fill and click Connect.

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption><p>Picture-3 FortiClient VPN -1</p></figcaption></figure>

(6).Please refer to the following image for a successful connection.

(7).and click on the 中華資安跳板機 circled in red.

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption><p>Picture-4 FortiClient VPN -2</p></figcaption></figure>

**(8).Successfully accessed the CHT jump server desktop and click SecureCRT-捷徑 to enter list.**

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption><p>Picture-5 <strong>CHT jump server desktop</strong></p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption><p>Picture-6 SecureCRT List</p></figcaption></figure>
