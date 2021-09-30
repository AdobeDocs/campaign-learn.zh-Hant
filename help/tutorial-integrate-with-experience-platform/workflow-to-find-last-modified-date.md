---
title: 建立導出工作流（第1部分） — 查找收件人清單的上次修改日期
description: 在建立匯出工作流程教學課程的第一部分，了解如何建立工作流程，以尋找從Experience Platform區段建立的收件者清單的上次修改日期。
feature: Data Import/Export, Workflows
kt: 8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
source-git-commit: 9a75069ee3bb9352ba7fa5350eb54e421e9427c8
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# 建立導出工作流（第1部分） — 查找收件人清單的上次修改日期

在建立匯出工作流程教學課程的第一部分，了解如何建立工作流程，以尋找從Experience Platform區段建立的收件者清單的上次修改日期。

>[!VIDEO](https://video.tv.adobe.com/v/336387?quality=12)

## 資產

建立日期範圍的JavaScript:

```java
var DEFAULT_LOOKBACK_DAYS = 90;
vars.OPTION_NAME = "BroadLog_CaptureTime";

logInfo("=====================");
logInfo("Starting Execution...");

// Establish the last and next RunTimes
var lastRunTime = getOption(vars.OPTION_NAME);
var nextRunTime = getCurrentDate();

//To reset and run through DEFAULT_LOOKBACK, uncomment the following line.
//lastRunTime = null;

logInfo("NEXT Run Date Set: [" + nextRunTime + "]");
logInfo("LAST Run Date Retrieved (" + lastRunTime + ")");

//Check for null so we can default the lastRunTime using the DEFAULT_LOOKBACK 
if (lastRunTime == null || lastRunTime == "null" || lastRunTime == "") {

 logInfo("Empty Date Retrieved, setting to default lookback (-" + DEFAULT_LOOKBACK_DAYS + " days)");
 lastRunTime = new Date();
 lastRunTime.setDate(nextRunTime.getDate() - DEFAULT_LOOKBACK_DAYS);
 logInfo("LAST Run Date Set: [" + lastRunTime + "]");

} 

//Persist values through execution of this instance of the workflow.
vars.lastRunTime = lastRunTime;
vars.nextRunTime = nextRunTime;

logInfo("Finished Execution.");
logInfo("===================");
```

## 下一部影片

[建立匯出工作流程（第2部分） — 擷取、格式化資料並儲存至外部帳戶](extract-format-save-data-to-external-account.md)
