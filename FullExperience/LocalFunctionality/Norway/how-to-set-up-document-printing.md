---
title: "How to: Set Up Document Printing"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "KID, printing documents"
  - "paper trays"
ms.assetid: d762ad2a-ba6b-4302-a45d-7e8a2672a189
caps.latest.revision: 2
ms.author: "edupont"
translation.priority.ht: 
  - "nb-no"
---
# How to: Set Up Document Printing
In [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)], you can print the sales reports that use the required giro specifications by using different paper types and paper trays.  
  
 When you use tray numbers and paper sources for Norwegian sales documents, you must consider how the printer and printer driver interpret this information. You may have to specify other tray numbers for your specific printer.  
  
> [!NOTE]  
>  KID information will also print where the giro information is printed.  
  
 The following documents require a printed giro:  
  
-   Invoices  
  
-   Credit memos  
  
-   Finance charge memos  
  
-   Reminders  
  
 The Norwegian version of [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] contains the following sets of sales documents.  
  
|**Set**|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
|-------------|---------------------------------------|  
|1|The standard [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] documents. No giro information is printed.|  
|2|The giro is printed on every page. The last page prints the giro total.|  
  
### To set up paper trays  
  
1.  In the **Search** box, enter **Printer Selections**, and then choose the related link.  
  
2.  Select the report.  
  
3.  On the **Navigate** tab, in the **Setup** group, select **Sales Document Paper Tray Setup**.  
  
4.  Select a paper source from the **\($ T\_78\_10600 First Page \- Paper Source $\)** field.  
  
5.  The **\($ T\_78\_10601 First Page – Tray Number $\)** field will automatically display the selected paper source. You can also manually enter a tray number.  
  
    > [!IMPORTANT]  
    >  Not all printers will have the same paper source names. You can specify a number in the **Tray Number** field. The number may correspond to a paper source. To find the number that a specific printer is using, see the technical documentation for the printer.  
  
     The **Other Pages** and **Giro Page** fields are set up the same way.  
  
6.  Choose the **OK** button.  
  
## See Also  
 [\($ T\_78 Printer Selection $\)](assetId:///e7c3bf24-9d03-418b-9826-d6125b34a516)   
 [Paper Sources and Tray Numbers](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/paper-sources-and-tray-numbers.md)   
 [Norwegian Giro and OCR\-B Font](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/norwegian-giro-and-ocr-b-font.md)   
 [How to: Set Up KID Numbers on Sales Documents](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-set-up-kid-numbers-on-sales-documents.md)