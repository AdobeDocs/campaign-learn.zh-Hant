---
title: 控制面板疑難排解
description: 了解控制面板疑難排解
feature: 控制面板
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
source-git-commit: 4fc34f56e13c3df5f1c42c24c87a6c7c5caff04b
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 19%

---

# 疑難排解[!UICONTROL 控制面板]

了解控制面板疑難排解。

## 登入和首頁

### 症狀：無法登入Experience Cloud

**該做什麼：**
使用者必須找到其IMS組織ID(xxx)。管理員必須將使用者新增至產品設定檔「Campaign-xxx-Admins」，以管理其要管理的每個執行個體。 如果使用者是所有執行個體的管理員，則他們必須將自己新增為使用者。

### 症狀：使用者看不到Experience Cloud首頁中存取[!UICONTROL 控制面板]的連結

**原因：**
使用者新增為產品設定檔的使用者Campaign-xxx-Administrators/Admin _之前，不會看到連結_。

**該做什麼：**
管理員必須將使用者新增至產品設 _定檔Campaign-xxx-_  Admin，以管理他們想要管理的每個執行個體。如果使用者是所有執行個體的管理員，則他們必須將自己新增為使用者。

### 症狀：[!UICONTROL 控制面板]中未列出例項

**原因：**
可能是，使用者必須新增為 ** 遺 _失的執行個體的使用者產品設定檔Campaign-xxx-Administrators/_ Admin

**該做什麼：**
管理員必須將使用者新增至產品設 _定檔Campaign-xxx-_  Admin，以管理他們想要管理的每個執行個體。如果使用者是所有執行個體的管理員，則他們必須將自己新增為「使用者」。

### 有用的影片

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*檢查 IMS 組織 ID (00:26分鐘)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*如何為產品設定檔管理員新增管理員，以便使用「 [!UICONTROL 控制面板] 」（01:03分鐘）*

### 實用文件

* [探索「控制面板」](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant)
* [管理「控制面板」 [!UICONTROL 的權限]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## 建立與 SFTP 伺服器（用戶端或 API）的連線

連線至 SFTP 伺服器需要：

* [!UICONTROL 允] 許列出您連線至SFTP伺服器的IP位址
* 必須向Adobe Campaign註冊的私密/公開金鑰組
* 若要直接連線至SFTP伺服器，您還需要SFTP用戶端軟體

### 實用文件 {#helpful-docs}

* [登入您的 SFTP 伺服器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
