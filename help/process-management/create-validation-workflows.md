---
title: 建立驗證工作流程
description: 了解如何設定不同的核准驗證工作流程。
feature: 工作流程，核准
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
source-git-commit: f6bb16306773a4b6ff7aa390a514e9b31fe047d6
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# 建立驗證工作流程

Adobe Campaign提供數個選項，供行銷人員檢閱及提供傳遞內容、行銷活動目標、資料擷取和預算核准。

本教學課程說明如何設定不同的核准驗證工作流程。

## 先決條件 {#prerequisite}

在啟用核准步驟之前，行銷團隊必須定義個別審核者：

* 核准活動中的Adobe Campaign審核者角色可以是單一審核者（運算元）或一組審核者（運算元角色）。
* 若要讓行銷活動開發人員將審核者選為行銷活動或傳送中的核准者，審核者和審核者群組必須由管理員在Adobe Campaign中設定。

## 設定促銷活動的核准{#configuring-approvals-for-campaigns}

如果您的行銷活動工作流程中的所有傳送都有相同的審核者集，請在行銷活動層級設定核准和審核者，以套用行銷活動核准功能。 執行工作流程後，核准工作和審核者會下推至工作流程的每個傳送活動。

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## 配置傳遞的批准{#configuring-approvals-for-deliveries}

您也可以在傳送層級設定核准。 如果傳遞核准步驟和審核者與促銷活動核准步驟和審核者不同，則傳遞設定會覆寫促銷活動設定。

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## 配置批准活動{#configuring-an-approval-activity}

與傳送或促銷活動核准不同，核准活動可讓使用者在工作流程中建立核准程式。 如此一來，即可在傳送啟動前核准目標選擇邏輯。 如有需要，也可允許在工作流程中的多個層級進行核准。

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

如需詳細資訊，請參閱[核准檔案](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
