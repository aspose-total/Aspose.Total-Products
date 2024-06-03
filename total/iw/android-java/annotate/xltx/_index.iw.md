---
title: הסר הערות XLTX באינטרנט או נהל הערות באמצעות אפליקציות Android לנייד
description: מחק הערות מקובץ XLTX דרך אפליקציה מקוונת בחינם. קוד API של Android לניהול הערות של קבצי XLTX.

family: total
platformtag: Android
feature: Annotate
informat: XLTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="נקה הערות מ-XLTX Document Online או נהל באמצעות אפליקציות אנדרואיד" h2="פתח אפליקציה חזקה מבוססת אנדרואיד להערות מסמכים XLTX. קוד רשום לניהול הערות של קובץ XLTX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="הסר הערות XLTX באופן מקוון" %}}

1. ייבא קובץ XLTX כדי למחוק הערות על ידי העלאתו
1. עשה זאת על ידי לחיצה בתוך אזור השחרור באמצעות גרירה ושחרור של אפליקציית ההערות
1. בהתאם לגודל קובץ XLTX ולמהירות האינטרנט המתן מספר שניות
1. לחץ על הלחצן 'הסר' כדי לנקות הערות
1. הורד את הקובץ באופן מיידי

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="הסר הערות למסמך XLTX באמצעות API של אפליקציית אנדרואיד" %}}

1. הוסף הפניה לספרייה לפרויקט אנדרואיד 
1. טען מסמך באמצעות אובייקט מחלקה של חוברת עבודה
1. בחר את גליון העבודה הספציפי
1. קבל את כל ההערות מהשימוש ב-[getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. קבל את כל ההערות עם שרשור באמצעות getThreadedComments
1. השתמש ב- removeAt כדי להסיר תגובות ומחברים בהתאמה
1. התקשר לשיטת השמירה כדי לשמור את הקובץ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד: הסר הערות ממסמך XLTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="עדכן הערות XLTX עם שרשור" %}}

1. טען מסמך באמצעות אובייקט מחלקה של חוברת עבודה
1. קבל את גיליון העבודה הספציפי 
1. קבל את ההערה השרשור באמצעות getComments().getThreadedComments(Index).get(Index)
1. השתמש בשיטת setNotes כדי לעדכן את ההערה 
1. התקשר לשיטת השמירה כדי לשמור את הקובץ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="הוסף הערות באמצעות API של אפליקציית אנדרואיד" %}}

1. צור מסמך באמצעות אובייקט מחלקה של חוברת עבודה
1. קבל את גיליון העבודה הספציפי
1. הוסף אינדקס הערות באמצעות getComments().add
1. השתמש בשיטת setNotes כדי להוסיף הערה  
1. התקשר לשיטת השמירה כדי לשמור את הקובץ with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד: עדכון הערה משורשרת של קובץ XLTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="קוד: הוספת הערות" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>פתח את אפליקציית Android הערת מסמכים XLTX</h2>

צריך לפתח אפליקציית הערות XLTX מבוססת אנדרואיד או כלי עזר כדי לספק משוב, להציע הצעות או לשתף פעולה עם אחרים במסמך? עם [Aspose.Cells for Android via Java](https://products.aspose.com/cells/iw/android-java/), ילד API של [Aspose.Total for Android via Java](https://products.aspose.com/total/iw/android-java/), כל מפתח אנדרואיד יכול לשלב את קוד ה-API שלעיל בתוך אפליקציית הערת המסמכים שלו. ספריית אנדרואיד רבת עוצמה מאפשרת לתכנת כל פתרון להערות מסמכים. יתר על כן, זה יכול לתמוך בפורמטים פופולריים רבים כולל פורמט XLTX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API של אנדרואיד להוספת הערות לקבצי XLTX" %}}

- אנו מארחים את חבילות ה-Java שלנו ב-[מאגרי מייבן](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/). 
- Aspose.Cells for Java הוא קובץ JAR נפוץ המכיל קוד בתים. 
- עקוב אחר ה-[הוראות שלב אחר שלב](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) כיצד להתקין Aspose.Cells for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

- מערכת ההפעלה אנדרואיד 2.0 ומעלה.
- חבילת Java היא חוצת פלטפורמות ופועלת על כל מערכות ההפעלה עם הטמעת JVM.

<br />
לפרטים נוספים, עיין ב-[תיעוד המוצר](https://docs.aspose.com/cells/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}