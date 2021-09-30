---
title: 建立匯出工作流程（第2部分） — 擷取、格式化資料並儲存至外部帳戶
description: 在建立匯出工作流程教學課程的第二部分，您將了解如何設定匯出資料的格式，以及如何將資料儲存至外部帳戶。 
feature: Data Import/Export, Workflows
kt: 8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
source-git-commit: 75131bcf23154c05621bb6b63224ad906ec96ecd
workflow-type: tm+mt
source-wordcount: '92'
ht-degree: 0%

---


# 建立導出工作流（第2部分）:擷取、格式化資料並儲存至外部帳戶

在建立匯出工作流程教學課程的第二部分，您將了解如何設定匯出資料的格式，以及如何將資料儲存至外部帳戶。

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12)

## 資產

JavaScript:儲存日期

```java
 logInfo("=====================")
 logInfo("Starting Execution...")

 optionName = vars.OPTION_NAME;
 logInfo("optionName: " + optionName);
 logInfo("NEXT Run Date: " + vars.nextRunTime);
 
 //Make sure we have valid values before saving for next run
 if (vars.nextRunTime == null || optionName == null){

   logInfo("Unable to find non-null values for optionName/nextRunTime! Throwing Error.")
   throw new Error('Unable to find non-null values for optionName/nextRunTime!  Ending Execution.');

 } else {

   // Save the nextRunTime to the database to establish starting point for next run.
   setOption(optionName, vars.nextRunTime);
   logInfo("Date Saved. [" + optionName + "] = [" + vars.lastRunTime + "]")

 }

 logInfo("Finished Execution.") 
 logInfo("===================")
```
