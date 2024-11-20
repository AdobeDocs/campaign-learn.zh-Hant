---
title: 建立核准和驗證工作流程 — 簡介
description: 瞭解如何設定不同的核准驗證工作流程。
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Intermediate
recommendations: noDisplay
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: 4d21755204c22fbeb4ac3a2916e9ee68cd2e0f9a
workflow-type: ht
source-wordcount: '255'
ht-degree: 100%

---

# 建立核准和驗證工作流程 — 簡介

Adobe Campaign 提供數個選項，供行銷人員檢閱及提供傳遞內容、行銷活動目標、資料擷取和預算核准。瞭解如何 [管理核准](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md)。

## 先決條件 {#prerequisite}

在啟用核准步驟之前，行銷團隊必須定義個別審核者：

* 核准活動中的 Adobe Campaign 審核者角色可以是單一審核者 (操作員) 或一組審核者 (操作員角色)。
* 若要讓行銷活動開發人員將審核者選為行銷活動或傳送中的核准者，審核者和審核者群組必須由管理員在 Adobe Campaign 中設定。

## 設定核准 {#configuring-approvals}

1. [設定行銷活動核准](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.md)：
如果您的行銷活動工作流程中的所有傳遞都有相同審核者集，請在行銷活動層級設定核准和審核者，以套用行銷活動核准功能。 執行工作流程後，核准工作和審核者會下推至工作流程的每個傳遞活動。
2. [設定傳遞的核准](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.md)：
您也可以在傳遞層級設定核准。 如果傳遞核准步驟及審核者與行銷活動核准步驟及審核者有所不同，則傳遞設定會覆寫行銷活動設定。
3. [在工作流程中建立核准流程](/help/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.md)：
您可藉由核准活動在工作流程中建立核准流程。 如此一來，即可在傳遞啟動前核准目標定位選擇邏輯。 如有需要，也可在工作流程中的多個層級進行核准。

如需詳細資訊，請參閱[文件](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=zh-Hant)，以瞭解詳情。
