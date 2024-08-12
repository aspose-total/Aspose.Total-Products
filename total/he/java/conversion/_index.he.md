---
title: המרת פורמט קובץ באמצעות Java 
url_ignore: /java/conversion/
description: המר את Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, תמונות תלת-ממד, דיאגרמות, פורמטי וידאו ופורמטים שונים אחרים עם כמה שורות של קוד Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="המרת פורמט קובץ באמצעות Java" h2="המר מסמכי Microsoft Office, PDF, תמונות, HTML וקבצים רבים אחרים ללא שימוש בתוכנה אחרת." >}}

{{% blocks/products/pf/feature-page-summary %}}
[ספריית ג'אווה כוללת](https://products.aspose.com/total/java/) מאיץ את פיתוח פתרונות מניפולציה של מסמכים מאפס או שיפור יישומים קיימים כדי להתמודד עם ניהול מסמכים בקלות.  API לא רק יוצר, עורך וממיר מסמכי Microsoft Office אלא גם מטפל ב-PDF, HTML, תמונות TIFF, JPG, PNG, BMP ו-SVG, קבצי דוא"ל, פורמטים של וידאו, תלת מימד, CAD ועוד.  זהו אוסף של ממשקי API של פתרונות ניהול ומניפולציה של מסמכים ללא כל תלות בתוכנה בתוך יישומי Java J2SE, J2EE, J2ME. מתכנתים יכולים ליצור, לעדכן, לעבד, להדפיס ולהמיר בקלות בין הפורמטים הפופולריים ביותר בכל יישומים מבוססי Java.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="המרת Word לאקסל" %}}
Total API תומך לא רק בהמרה בין פורמטים של Microsoft Word אלא גם בהמרת Word ל-Excel, PDF, HTML, תמונות, EPUB, Markdown ו-XPS.  תהליך ההמרה הוא פשוט. הבה נבחן את המקרה של המרת **Word ל-Excel**.  טען קובץ Microsoft Word באמצעות מחלקת [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) והמר את **WORD ל-HTML** באמצעות שיטת [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)).  לאחר מכן, פתח את מסמך ה-HTML שהומר באמצעות מחלקת [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ושמור את המסמך בפורמט XLSX בשיטת [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
 מפתחים יכולים גם להמיר [Word ל-PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="המרת Java Word לאקסל" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="המרת PDF לתמונות" %}}
API תומך בהמרת PDF לתמונות כמו JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel ופורמטים אחרים.  עבור המרת PDF לתמונה, בואו ניקח בחשבון את תמונת JPG כקובץ יעד.  התהליך הוא, טעינת קובץ PDF באמצעות מחלקת Document ואתחול אובייקט [JpegDevice class](https://reference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) ועיבוד PDF ל-JPEG באמצעות שיטת [Process](https://reference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1)
טען קובץ JPEG באמצעות מחלקה [Image](https://reference.aspose.com/imaging/java/aspose.imaging/image) ולבסוף קרא לשיטת השמירה.

{{% blocks/products/pf/feature-page-code h3="המרת Java PDF לתמונה" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="המרת PowerPoint לקבצי Excel" %}}

להמרת קבצי Microsoft PowerPoint לקבצים שונים כולל Excel Word, MHTML, ממשקי משנה רלוונטיים הכרוכים ב-Aspose.Total הראשי עבור Java API. תהליך המרת קבצי PowerPoint למסמך Excel, טעינת קובץ PowerPoint באמצעות מחלקת [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) והמרת **PowerPoint ל-HTML** באמצעות שיטת [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). לאחר מכן טען את מסמך ה-HTML שהומר באמצעות מחלקה [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ושמור את המסמך בפורמט EXCEL בשיטת [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).  מופיע גם קוד להמרת **PowerPoint to Word**.

{{% blocks/products/pf/feature-page-code h3="המרת Java PowerPoint לאקסל" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="המרת Java PowerPoint ל-Word" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}