---
title: Android 推送通知教學課程快速入門 - 簡介
description: 本教學課程將逐步帶您瞭解從 Adobe Campaign 傳送推送通知以及在 Android™ 應用程式接收這些通知的相關步驟。
feature: Push
jira: KT-6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noCatalog
exl-id: 91ff4bae-8598-4227-b4c9-4e436ce7400d
source-git-commit: 116a24a8aa123f615e08fa4ebd187b3c4c460ba2
workflow-type: tm+mt
source-wordcount: '314'
ht-degree: 100%

---

# Android 推播通知教學課程快速入門 - 簡介

Adobe Campaign 可讓您將個人化和分段的 [!DNL push] 通知傳送至 [!DNL iOS] 和 [!DNL Android™] 行動裝置。本教學課程將引導您完成從 Adobe Campaign 傳送 [!DNL push] 通知至 [!DNL Android™] 應用程式的相關步驟。

## 先決條件

開始之前，您必須具備下列條件：

1) **Android™ 行動應用程式**

   本教學課程不包含設定行動應用程式所需的詳細步驟。您必須擁有 **[!DNL Android™]行動應用程式，且已整合 [!DNL Campaign SDK]**。

   您可在產品檔案中找到所需步驟的詳細說明：

   [將 Campaign SDK 整合至行動應用程式](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=zh-Hant)

2) **[!DNL Mobile App channel]軟體套件已安裝**

   [!DNL Mobile App channel] 套件必須安裝在您的 [!DNL Campaign] 執行個體上。下列影片說明如何檢查是否已在您的執行個體上安裝 [!DNL Mobile App channel]，若未安裝，則會指導您進行安裝。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on){transcript=true}

## 教學課程概觀

我們想要傳送個人化優惠 [!DNL push] 通知給[!DNL Neotrip] [!DNL Android™]行動應用程式的訂閱者。[!DNL Neotrip]應用程式已使用 [!DNL Campaign SDK] 進行設定，而 [!DNL Mobile App channel] 已在[!DNL Campaign]執行個體上啟用。

需要下列設定步驟：

### 步驟 1：擴充應用程式訂閱結構以個人化 [!DNL push] 通知

若要個人化 [!DNL push] 通知，您必須先[擴充應用程式訂閱綱要](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)。 這可讓系統儲存使用者訂閱服務時從應用程式收到的個人化值。

### 步驟 2：設定 Android™ 服務並在 Campaign 中建立行動應用程式

接下來，必須設定 [Android™ 服務，並在 Campaign](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md) 中建立行動應用程式。 在此步驟中，[!DNL Neotrip]應用程式定義為推送通知的目標。

### 步驟 3：設定並傳送推送通知

現在推送通知已準備好進行[設定並傳送](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md)。

## 開始教學課程

步驟 1：[擴充應用程式訂閱綱要](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
