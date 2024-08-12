---
title: המרת מסמכים באמצעות אנדרואיד API  

description: המר פורמטים של Word, Excel, PowerPoint, HTML, PDF ותמונה באמצעות API להמרה של אנדרואיד.  אנדרואיד להמיר את Office docx, xlsx, pptx ל-PDF.  
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="המרת מסמכים באמצעות Android API" h2="המר את Microsoft Office Word, Excel, PowerPoint, PDF, תמונות ופורמטים שונים אחרים באמצעות Aspose.Total עבור אנדרואיד באמצעות Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[סה"כ אנדרואיד API](https://products.aspose.com/total/android-java/) מספק את פתרון המרת וניהול המסמכים עבור יישומי אנדרואיד מבלי להסתמך על תוכנה אחרת.  מתכנתים יכולים להפוך את פתרון ניהול המסמכים והמניפולציה לאוטומטי בקלות על ידי שילוב API בתוך יישומים מפותחים חדשים או ביישומים קיימים.  על ידי שילוב ה-API, מתכנת יכול להוסיף בקלות פונקציונליות ליצירה, עריכה או המרת מסמכי פורמט שונים בתוך האפליקציה.  PDF Converter API באנדרואיד מטפל במקרים של המרה כמו Office DOCX, XLSX, PPTX ל-PDF או להיפך.  יתר על כן, מעט מקרים שבהם עוסק API המפורטים להלן ומעט קישורים שניתנו למקרי ההמרה הרלוונטיים.  

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="המר PDF ל-CSV" %}}
Total Android API תומך בהמרת PDF ל-Excel XLSX ו-CSV.  זה תהליך בן שני שלבים. שני ממשקי API הכוללים [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ו-[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) מעורבים.  התהליך הוא שאתה יכול קודם כל תבנית PDF ל-Excel XLSX סמויה ולאחר מכן XLSX ל-CSV.  ביתר פירוט, טען קובץ PDF באמצעות מחלקה [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) ועיבוד ל-XLSX באמצעות שיטת [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-).  לאחר מכן, טען את מסמך ה-XLSX המעובד באמצעות מחלקה [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) והפעל את שיטת [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).

{{% blocks/products/pf/feature-page-code h3="אנדרואיד - המרת PDF לאקסל" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="המרת אקסל ל-Word" %}}
אנדרואיד API מטפל גם בהמרת אקסל.  התהליך הוא, טען קובץ EXCEL XLSX באמצעות מחלקה [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) והמרת EXCEL ל-PDF על ידי הגדרת SaveFormat ל-AUTO תחילה.  לאחר מכן טען את קובץ ה-PDF השמור באמצעות מחלקה [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) והפעל את שיטת [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) כדי לשמור את המסמך בפורמט Word DOC / DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - המרת אקסל ל-Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="המרת POWERPOINT ל-HTML ו-MHTML" %}}
Android Total API עוסק בפורמטים שונים כולל קבצי PowerPoint ולכן יכול להמיר מצגות ל-HTML ו-MHTML.  התהליך הוא, טען קובץ POWERPOINT PPT/PPTX באמצעות מחלקה [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) והפעל את שיטת [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) כדי להמיר POWERPOINT ל-HTML.  יתר על כן, כעת טען את מסמך ה-HTML שהומר באמצעות מחלקה [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) וקרא לשיטת [save](https://reference.aspose.com/cells/java/com.aspose.cells/) להמרת MHTML.  
{{% blocks/products/pf/feature-page-code h3="אנדרואיד - המרת PowerPoint ל-HTML ו-MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}