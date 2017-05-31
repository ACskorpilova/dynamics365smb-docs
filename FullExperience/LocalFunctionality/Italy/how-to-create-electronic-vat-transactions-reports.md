---
title: "How to: Create Electronic VAT Transactions Reports"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "VAT, reporting electronically"
  - "VAT reports, submitting"
ms.assetid: 5d23de11-70e9-4e78-9abc-83d3c123728c
caps.latest.revision: 10
ms.author: "edupont"
manager: "terryaus"
translation.priority.ht: 
  - "it-it"
---
# How to: Create Electronic VAT Transactions Reports
You must create a list of transactions that include VAT with amounts over the current threshold on or before the specified occurrence date. You submit this report to the tax authorities.  
  
### To create a VAT transactions report  
  
1.  In the **Search** box, enter **\($ N\_740 VAT Report $\)**, and then choose the related link.  
  
2.  Fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ T\_740\_1 No. $\)**|Specify the report number.<br /><br /> Depending on the type of report, and the configuration in your company, you can use the automatically generated number, select a different number series, or enter a different number manually.|  
    |**\($ T\_740\_2 VAT Report Config. Code $\)**|Select the **VAT Transactions Report** configuration code.<br /><br /> The configuration code specifies how the VAT report is generated. For more information, see [Italian VAT](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/italian-vat.md).|  
    |**\($ T\_740\_3 VAT Report Type $\)**|Specify if you want to create a standard or corrective VAT report, or if you want to delete \(cancellation\) a submitted VAT report.|  
    |**\($ T\_740\_4 Reference VAT Report $\)**|Specify the original VAT report if you selected **Corrective** or **Deletion** in the **\($ T\_740\_3 VAT Report Type $\)** field.|  
    |**\($ T\_740\_5 Start Date $\)**|Specify the start date of the report period.|  
    |**\($ T\_740\_6 End Date $\)**|Specify the end date of the report period.|  
  
     Now, you must import the VAT ledger entries that are to be included in this VAT report.  
  
3.  On the **Actions** tab, choose **Suggest Lines**.  
  
     This adds lines to the window. The lines are based on VAT entries where the [\($ T\_254\_12120 Include in VAT Transac. Rep. $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/-$-t_254_12120-include-in-vat-transac.-rep.-$-.md) field is selected.  
  
     If a document that is suggested does not contain a VAT Registration number or a Fiscal code, the report cannot be released until you fill in the missing information on the Customer or Vendor card.  
  
     Optionally, for each line, in the **\($ T\_741\_9 Amount $\)** field, you can drill down to see the VAT ledger entries that resulted in the line.  
  
4.  For each line, select the \($ T\_741\_12111 Incl. in Report $\) check box to specify whether the report line should be exported and submitted to the tax authority. The **Incl. in Report** check box provides an extra dimension on a document level, whereas the **Include in VAT Transac Rep.** check box provides it on a line level. You can use the check box, for example, when a line cannot go through the validator or is causing submission problems at the tax authority.  
  
5.  Verify that the **\($ T\_741\_12102 Contract Payment Type $\)** field is set to the appropriate value in each suggested line. The following table describes the options.  
  
    |[!INCLUDE[bp_tableoption](../../ApplicationDesign/includes/bp_tableoption_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |----------------------------------|---------------------------------------|  
    |**Without Contract**|The VAT entries that resulted in this line are not associated with a contract.|  
    |**Contract**|The VAT entries that resulted in this line are associated with a contract.|  
    |**Other**|The VAT entries that resulted in this line are not associated with a special contract, such as ongoing maintenance or other exceptions.|  
  
    > [!TIP]  
    >  In [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)], the contract that the tax authorities are looking for can be blanket orders or service contracts. To identify if the VAT report line belongs to a blanket order or service contract, you can drill down to see the underlying VAT entries from the **\($ T\_741\_9 Amount $\)** field.  
  
     Credit memos are included in the VAT transaction report if the customer or vendor is from a country\/region that is outside the EU and not black\-listed. For more information, see [Italian VAT](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/italian-vat.md).  
  
 Now that you have created the VAT report, you must submit it to the tax authorities. For more information, see [How to: Export VAT Transactions Reports](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/how-to-export-vat-transactions-reports.md).  
  
## See Also  
 [Italian VAT](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/italian-vat.md)   
 [\($ N\_740 VAT Report $\)](assetId:///30b3e164-8489-4b47-990e-a6a3e85a24a5)   
 [\($ N\_745 VAT Report Error Log $\)](assetId:///c35e6992-b833-484f-9026-d9ba5e4d528b)   
 [\($ B\_12193 Export VAT Transactions $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/-$-b_12193-export-vat-transactions-$-.md)