---
title: "How to: Set Up 340 Reports for Small Businesses"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
ms.assetid: 5b8a7e68-7bbf-4841-896e-ae0495997386
caps.latest.revision: 3
ms.author: "edupont"
translation.priority.ht: 
  - "es-es"
---
# How to: Set Up 340 Reports for Small Businesses
Use the following procedure to set up your business to report on a cash basis, that is, Cash Accounting Criteria \(CAC\). If you have not already done so, you can set up posting groups for cash\-based VAT accounting for purchases and sales.  
  
 When you file a report 340, any transaction lines that are associated with unrealized VAT are assumed to have taken place under cash accounting.  
  
 After VAT posting is set up to handle unrealized VAT, any printed sales order, purchase order, and so forth will be modified to have the following label in bold font added to the report just before the section reporting the document lines: **Régimen especial del criterio de caja**.  
  
### To set up reporting under CAC  
  
1.  In the **Search** box, enter **General Ledger Setup**, and then choose the related link.  
  
2.  On the **General** FastTab, select the **\($ T\_98\_48 Unrealized VAT $\)** check box in the **\($ N\_118 General Ledger Setup $\)** window. Choose the **OK** button.  
  
3.  In the **Search** box, enter **VAT Posting Setup**, and then choose the related link.  
  
4.  In the **\($ N\_472 VAT Posting Setup $\)** window, select a group to modify or create a posting group that has general ledger accounts to treat the VAT amounts for the various unrealized VAT accounts in your VAT Posting Setup. On the **Home** tab, in the **Manage** group, choose **Edit**.  
  
5.  On the **General** FastTab, set the **\($ T\_325\_5 Unrealized VAT Type $\)** to **Percentage**.  
  
6.  On the **Sales** and **Purchase** FastTabs, specify general ledger accounts for the various **VAT Unreal. Account** fields.  
  
## See Also  
 [How to: Use Accounts for Unrealized VAT](../../Finance/how-to-use-accounts-for-unrealized-vat.md)