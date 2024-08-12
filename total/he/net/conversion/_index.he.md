---
title: המרת פורמט קובץ באמצעות C#  

description: המר את Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, תמונות תלת מימד, דיאגרמות, פורמטי וידאו וקבצים פופולריים רבים אחרים עם מספר שורות של קוד C# בלבד.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="המרת פורמט קובץ באמצעות C#  .NET" h2="המר קבצי Microsoft Office, PDF, תמונות, HTML ופורמטים שונים אחרים ללא שימוש בתוכנה אחרת." >}}

{{% blocks/products/pf/feature-page-summary %}}
[.NET Total Library](https://products.aspose.com/total/net/) מאיץ את פיתוח פתרונות ניהול מסמכים מאפס או שיפור יישומים קיימים כדי להתמודד עם מניפולציה של מסמכים בקלות.  API לא רק מנהל מסמכי Microsoft Office אלא גם מטפל ב-PDF, HTML, תמונות TIFF, JPG, PNG, BMP ו-SVG, קבצי דוא"ל, פורמטים של וידאו, פורמטים של נתונים GIS ועוד הרבה יותר.  זהו סט שלם של ממשקי API של פתרונות ניהול ומניפולציה של מסמכים ללא תלות בתוכנה.    מתכנתים יכולים ליצור, לעדכן, לעבד, להדפיס ולהמיר בקלות בין הפורמטים הפופולריים ביותר בכל יישום מבוסס NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="המרת וורד ל-PDF" %}}
Total API תומך לא רק בהמרה בין פורמטים של Microsoft Word אלא גם בהמרת Word ל-PDF, HTML, תמונות, EPUB, Markdown ו-XPS.  תהליך ההמרה הוא פשוט.  טען את המחלקה Document via Document ופשוט קרא לשיטת Save with target format.  זה כל כך פשוט. מפתחים יכולים לבדוק את ה-[תוצאת המרה](https://products.aspose.com/words/net/conversion/word-to-pdf/) לפני שילוב הקוד של **Word ל-PDF**


{{% blocks/products/pf/feature-page-code h3="C# - המרת Word ל-PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="המרת PDF לתמונות" %}}
API תומך בהמרת PDF לתמונות, Powerpoint, Excel ופורמטים אחרים. עבור המרת PDF לתמונה, בואו ניקח בחשבון את תמונת JPG כקובץ יעד. התהליך הוא, טעינת קובץ PDF באמצעות מחלקת Document ואתחול אובייקט [JpegDevice class](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) ועיבוד PDF ל-JPEG באמצעות שיטת [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1)
טען קובץ JPEG באמצעות מחלקה [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) ולבסוף קרא לשיטת השמירה.

{{% blocks/products/pf/feature-page-code h3="C# - המרת PDF לתמונה" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="המרת Excel ל-Word ו-PowerPoint" %}}

להמרת פורמטים של Microsoft Excel לקבצים שונים, כולל Word ו-PowerPoint, ממשקי משנה רלוונטיים הכרוכים ב-Aspose.Total הראשי עבור .NET API. תהליך המרת קבצי Excel למסמך Word, טען קובץ EXCEL באמצעות מחלקת [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) והמרת EXCEL ל-PDF תחילה והגדר את SaveFormat ל-Auto.  לאחר מכן טען את קובץ ה-PDF שהומר באמצעות מחלקה Document וקרא לשיטת Save והגדר את Doc, Docx כ-SaveFormat. הקוד רשום גם עבור המרה של Microsoft **Excel ל-Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="C# - המרת JSON לאקסל" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - המרת אקסל ל-JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}