---
title: הסר הערות PDF באינטרנט או נהל הערות באמצעות אפליקציות Android לנייד
description: מחק הערות מקובץ PDF דרך האפליקציה המקוונת בחינם. קוד API של Android לניהול הערות של קבצי PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="נקה הערות מ-PDF Document Online או נהל באמצעות אפליקציות אנדרואיד" h2="פתח אפליקציה חזקה מבוססת אנדרואיד להערות מסמכים PDF. קוד רשום לניהול הערות של קובץ PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="הסר הערות PDF באופן מקוון" %}}

1. ייבא קובץ PDF כדי למחוק הערות על ידי העלאתו
1. עשה זאת על ידי לחיצה בתוך אזור השחרור באמצעות גרירה ושחרור של אפליקציית ההערות
1. בהתאם לגודל קובץ PDF ולמהירות האינטרנט המתן מספר שניות
1. לחץ על הלחצן 'הסר' כדי לנקות הערות
1. הורד את הקובץ באופן מיידי

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="הסר הערות למסמך PDF באמצעות API של אפליקציית Android" %}}

1. הוסף הפניה לספרייה לפרויקט אנדרואיד 
1. טען מסמך באמצעות אובייקט מחלקה Document
1. בחר את הדף הספציפי באמצעות getPages().get_Item(Index) 
1. השתמש ב-AnnotationSelector וקבל את כל הערות הטקסט באמצעות annotationSelector.getSelected()
1. חזור על כל הערה וקרא לשיטת המחיקה כדי להסיר אותה.
1. התקשר לשיטת השמירה כדי לשמור את הקובץ.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד: מחק הערות מקובץ PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="הוסף הערה באמצעות API של אפליקציית Android" %}}

1. הוסף הפניה לספרייה לפרויקט אנדרואיד 
1. צור אובייקט בכיתה Document
1. הוסף את הדף והתוכן החדשים באמצעות getPages().add() 
1. השתמש ב-getPages().get_Item(Index) של המחלקה TextAnnotation
1. הגדר את ההערות הרלוונטיות כגון כותרת, נושא, תוכן וכו'
1. השתמש ב-getAnnotations().add כדי להוסיף את ההערות
1. התקשר לשיטת השמירה כדי לשמור את הקובץ עם הערות נוספות
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד: הוסף ביאור PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>פתח את אפליקציית Android הערת מסמכים PDF</h2>

צריך לפתח אפליקציה או כלי עזר ניידים להערות PDF כדי לספק משוב, להציע הצעות או לשתף פעולה עם אחרים במסמך? עם [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/iw/android-java/), ילד API של [Aspose.Total for Android via Java](https://products.aspose.com/total/iw/android-java/), כל מפתח אנדרואיד יכול לשלב את קוד ה-API הנ"ל בתוך יישום הערות המסמכים שלו. ספריית אנדרואיד רבת עוצמה מאפשרת לתכנת כל פתרון להערות מסמכים. יתר על כן, זה יכול לתמוך בפורמטים פופולריים רבים כולל פורמט PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ספריית אנדרואיד להוספת הערות לקבצי PDF" %}}

- אנו מארחים את חבילות ה-Java שלנו ב-[מאגרי מייבן](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java הוא קובץ JAR נפוץ המכיל קוד בתים. 
- עקוב אחר ה-[הוראות שלב אחר שלב](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) כיצד להתקין Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

- אנדרואיד API 31 ו-32
- אנדרואיד 4.0 ומעלה
- כלי Android Studio ו-SDK

<br />
לפרטים נוספים על תלות אופציונלית בחבילות, כגון JogAmp JOGL, מנוע הגופנים Harfbuzz, Java Advanced Imaging JAI, עיין ב-[תיעוד המוצר](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}