---
title: 控制面板疑難排解
description: 瞭解如何進行控制面板疑難排解
feature: Control Panel
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 0dca4676-2d5e-411b-9fdf-fbfd1081cb0e
source-git-commit: 28e209b6c9dad98a649b0b49eee7bb886c3d8431
workflow-type: tm+mt
source-wordcount: '337'
ht-degree: 95%

---

# [!UICONTROL 控制面板]疑難排解

瞭解如何進行控制面板疑難排解。

## 登入和首頁

### 症狀：無法登入 Experience Cloud

**該怎麼辦：**
用戶必須找到其組織的ID(xxx)。 系統管理員需要將使用者新增到他們想要管理的每個執行個體的產品設定檔「Campaign-xxx-Admins」。如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 症狀：使用者看不到 Experience Cloud 首頁存取[!UICONTROL 控制面板]的連結

**原因：**
使用者直到新增為產品設定檔 _Campaign-xxx-Administrators/Admin_ 的使用者後，才能看到連結。

**該做什麼：**
管理員需要將使用者新增至產品設定檔 _Campaign-xxx-Admins_，以便管理執行個體。如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 症狀：執行個體未列於[!UICONTROL 控制面板]

**原因：**
可能是，使用者需要新增為消失的執行個體的*使用者* 產品設定檔&#x200B;_Campaign-xxx-Administrators/Admin_

**該做什麼：**
管理員需要將使用者新增至產品設定檔 _Campaign-xxx-Admins_，以便管理執行個體。如果使用者是所有執行個體的管理員，則他們仍需將自己新增為「使用者」。

### 有用的影片

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*檢查組織的ID（00:26分鐘）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*如何為產品設定檔管理員新增管理員，以便使用[!UICONTROL 控制面板] (01:03 分鐘)*

### 實用文件

* [探索「控制面板」](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant)
* [管理「[!UICONTROL 控制面板]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)」的權限

## 建立與 SFTP 伺服器（用戶端或 API）的連線

連線至 SFTP 伺服器需要：

* [!UICONTROL 允許列出]您連線至 SFTP 伺服器的 IP 位址
* 需要以 Adobe Campaign 註冊私人/公有金鑰組
* 如需直接連接到 SFTP 伺服器，您還需要 SFTP 用戶端軟體

### 實用文件 {#helpful-docs}

* [登入您的 SFTP 伺服器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
