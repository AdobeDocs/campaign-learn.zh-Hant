---
title: 技術教學課程 - 為 Adobe Campaign 設定簡訊
description: 了解如何為 SMTP 提供者設定簡訊帳戶以及如何分析和針對設定進行疑難排解。
feature: SMS
role: Admin, Developer
badgeV7V8: label="適用於 V7 & V8" type="Positive"
thumbnail: 340957.jpg
exl-id: c1eaabbf-c349-431d-9bbb-6ae987926d99
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: d0e9f0b2-1f2b-4134-9844-49cd4e950f27
    internal-label: Campaign v8
feature_v2:
  - id: a4671286-a59f-47e3-b97b-90627a1977d5
    internal-label: Communication channels
subfeature_v2:
  - id: b1bd1421-1927-4c59-9bc6-ce292360e43b
    internal-label: SMS Messaging
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
source-git-commit: 369f9c3691b6326e521ebc9139aac1d2ee7c3ce2
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 100%
---
# 技術教學課程 - 為 Adobe Campaign 設定簡訊

本部分的教學課程是針對負責為 Adobe Campaign 設定簡訊通道的管理員設計的。

以下主題將涵蓋介紹：

* **[簡訊簡介](/help/tutorial-sms/introduction-to-sms.md)**：
  *了解簡訊的工作原理和 Adobe Campaign 傳送簡訊的方式*

* **[為標準 SMPP 提供者設定簡訊帳戶](/help/tutorial-sms/set-up-account-for-standard-smpp-provider.md)**
  *了解如何將簡訊連接器調整至您的 SMPP 提供者。 微調簡訊設定以處理連線限制。  瞭解如何設定最大輸送量、傳送視窗和 TLS 加密。*

* **[根據您的 SMPP 提供者調整簡訊連接器](/help/tutorial-sms/adapt-sms-connector-to-smpp-provider.md)**
  *瞭解如何微調簡訊設定以處理連線限制。 瞭解如何設定最大輸送量、傳送視窗和 TLS 加密。*

* **[SMPP 協定深入剖析和疑難排解](/help/tutorial-sms/smpp-deep-dive-and-troubleshooting.md)**
  *瞭解如何建立 SMPP 連線以及 SMPP 如何通過 PDU 交換資料。 瞭解如何疑難排解連線問題。*

>[!NOTE]
>
>本教學課程適用於 Adobe Campaign V7 和 Campaign V8。 可在產品文件中找到其他資源：[簡訊連接器通訊協定與設定](https://experienceleague.adobe.com/zh-hant/docs/campaign-classic/using/sending-messages/sending-messages-on-mobiles/sms-set-up/sms-protocol)。
