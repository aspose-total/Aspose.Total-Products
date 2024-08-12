---
title: המרת מסמכים באמצעות C++  

description: המר פורמטים שונים של מסמכים כגון Word, Excel, PowerPoint, PDF, JSON, תמונות ועוד באמצעות C++ API.  
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="המרת מסמכים באמצעות C++" h2="המר את Microsoft Office Word, Excel, PowerPoint, PDF, תמונות ופורמטים שונים אחרים באמצעות ספריית C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[ממשק API של אנדרואיד](https://products.aspose.com/total/android-java/) פותר את הנושא של המרת מסמכים ומפתחים יכולים להפוך את פתרון ניהול המסמכים והמניפולציה לאוטומטי בקלות על ידי שילוב API בתוך יישומים מפותחים חדשים או ביישומים קיימים.  מתכנתי C++ יכולים להוסיף פונקציונליות כמו יצירה, עריכה או המרת מסמכים בפורמטים שונים בתוך הפתרון שלהם מבלי להסתמך על תוכנה כלשהי.  כמה מקרים גנריים כמו txt ל-PDF, SVG ל-PNG, XLSX ל-CSV, JSON ל-CSV, Word ל-PDF, HTML ל-PDF, אפשר להמיר בקלות.  יתר על כן, מעט מקרים בהם עוסק API המפורטים להלן ומעט קישורים שניתנו למקרי ההמרה הרלוונטיים.  

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="המר את Microsoft Word לאקסל" %}}
Total C++ API תומך ב-Microsoft Word DOC/DOCX להמרת Excel.    התהליך הוא, טען קובץ Word DOC / DOCX באמצעות הפניה לכיתה [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) והפעל את פונקציית חבר [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) כדי להמיר ל-HTML תחילה.  לאחר מכן טען מסמך HTML באמצעות הפניה לכיתה [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) והפעל את פונקציית חבר [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) כדי לשמור את המסמך בפורמט Excel.  

{{% blocks/products/pf/feature-page-code h3="C++ - המרת Word לאקסל" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="המרת PDF ל-Word" %}}
ספריית ההמרה C++ תומכת גם ב-PDF למילה DOC, DOCX והמרת פורמטים אחרים.  בהתחשב במקרה של עיבוד PDF ל-RTF, זהו תהליך דו-שלבי, ראשית המר את PDF לפורמט Word DOC/DOCX ואז עבד אותו ל-RTF.  השלבים הכלולים לכך, טעינת קובץ PDF באמצעות הפניה לכיתה [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) והפעלת פונקציית חבר [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) להמרת PDF ל-Word.  כעת טען שוב את קובץ Word DOC / DOCX באמצעות הפניה לכיתה [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) של Aspose.Words API ושמור אותו בפורמט RTF באמצעות פונקציית חבר [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).

{{% blocks/products/pf/feature-page-code h3="C++ - המרת PDF ל-Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="המרת JSON ל-Word" %}}
עבור המרת JSON, C++ API תומך בשילובים שונים כגון JSON ל-Word, Json ל-PowerPoint, Word ל-JSON וכו'.  בהתחשב במקרה של המרת Word, Process הוא לקרוא נתוני JSON חוקיים מהקובץ באמצעות אובייקט [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) חדש ולאחר מכן להפעיל את שיטת [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) כדי לשמור JSON כקובץ PDF.  אז עכשיו טען קובץ שמור באמצעות מחלקה [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) ושמור אותו בפורמט מסמך Word בשיטת [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
{{% blocks/products/pf/feature-page-code h3="C++ - המרת JSON ל-Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}