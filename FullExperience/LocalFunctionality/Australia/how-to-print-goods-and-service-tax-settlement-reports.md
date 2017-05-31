---
title: "How to: Print Goods and Service Tax Settlement Reports"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "goods and services tax (GST), settlement reports"
  - "GST, settlement reports"
ms.assetid: 5d2b72a9-3271-4da6-8799-e7b73eee9ef3
caps.latest.revision: 13
ms.author: "edupont"
manager: "terryaus"
translation.priority.ht: 
  - "en-au"
---
# How to: Print Goods and Service Tax Settlement Reports
You must submit a periodic report of goods and services tax \(GST\) settlement. You can create this settlement from the **\($ N\_11603 BAS Calc. Schedule List $\)** window.  
  
> [!IMPORTANT]  
>  Before you calculate the GST settlement, you must export the business activity statement \(BAS\). For more information, see [How to: Export Business Activity Statements](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Australia/how-to-export-business-activity-statements.md).  
  
### To print a goods and service tax settlement  
  
1.  In the **Search** box, enter **BAS Calculation Sheets**, and then choose the related link.  
  
2.  Choose the appropriate BAS calculation sheet, and then, on the **Actions** tab, choose **Calculate GST Statement**.  
  
3.  On the **[!INCLUDE[bp_optionsheading](../../DesignAndEngineering/includes/bp_optionsheading_md.md)]** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ R\_11603\_N\_2\_1 Settlement Account Type $\)**|The settlement account type.|  
    |**\($ R\_11603\_N\_2\_3 Settlement Account No. $\)**|The general ledger account number or vendor number, based on the type selected in the **Settlement Account Type** field.|  
    |**\($ R\_11603\_N\_2\_5 Rounding G\/L Account No. $\)**|The account to which the truncated cents will be posted.|  
    |**\($ R\_11603\_N\_2\_9 Posting Date $\)**|The posting date for the settlement entries.|  
    |**\($ R\_11603\_N\_2\_17 Document No. $\)**|The document number of the settlement entries.|  
    |**\($ R\_11603\_N\_2\_7 Description $\)**|The settlement description.|  
    |**\($ R\_11603\_N\_2\_13 Post $\)**|Select to post the withholding tax settlement entries.|  
    |**\($ R\_11603\_N\_2\_1500000 Inter Company $\)**|Select if the posting is inter company.|  
  
4.  On the **BAS Calculation Sheet** FastTab, select the appropriate filters.  
  
5.  Choose the **Print** button to print the report or choose the **Preview** button to view it on the screen.  
  
## See Also  
 [How to: Print Goods and Services Tax Sales and Purchase Reports](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Australia/how-to-print-goods-and-services-tax-sales-and-purchase-reports.md)   
 [How to: Set Up Goods and Service Tax Posting](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Australia/how-to-set-up-goods-and-service-tax-posting.md)   
 [Business Activity Statements](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Australia/business-activity-statements.md)