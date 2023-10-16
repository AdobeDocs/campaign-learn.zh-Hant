---
title: 建立匯出工作流程 (第一部分)— 尋找收件人清單的最後修改日期
description: 在建立匯出工作流程的教學課程第一部分，了解如何建立工作流程，尋找從 Experience Platform 區段建立的收件者清單的最後修改日期。
feature: Data Management, Workflows
jira: KT-8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: 6fd70eea-3be7-4589-a608-05b0a8de93a6
source-git-commit: 116a24a8aa123f615e08fa4ebd187b3c4c460ba2
workflow-type: ht
source-wordcount: '122'
ht-degree: 100%

---

# 建立匯出工作流程 (第一部分)— 尋找收件人清單的最後修改日期

在建立匯出工作流程的教學課程第一部分，了解如何建立工作流程，尋找從 Experience Platform 區段建立的收件者清單的最後修改日期。

>[!VIDEO](https://video.tv.adobe.com/v/336387?quality=12&learn=on){transcript=true}

## 資產

利用 JavaScript 建立日期範圍：

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

[建立匯出工作流程 (第二部分)— 擷取、格式化資料並儲存至外部帳戶](extract-format-save-data-to-external-account.md)
