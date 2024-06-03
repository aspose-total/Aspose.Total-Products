---
title: הסר הערות POTX באינטרנט או נהל הערות באמצעות אפליקציות Android לנייד
description: מחק הערות מקובץ POTX דרך האפליקציה המקוונת בחינם. קוד API של Android לניהול הערות של קבצי POTX.

family: total
platformtag: Android
feature: Annotate
informat: POTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="נקה הערות ממצגת POTX באינטרנט או נהל באמצעות אפליקציות אנדרואיד" h2="פתח יישום כלי עזר להערות מצגת POTX מבוסס אנדרואיד רב עוצמה. קוד רשום לניהול הערות של קובץ POTX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="הסר הערות POTX באופן מקוון" %}}

1. ייבא קובץ POTX כדי למחוק הערות על ידי העלאתו
1. עשה זאת על ידי לחיצה בתוך אזור השחרור באמצעות גרירה ושחרור של אפליקציית ההערות
1. בהתאם לגודל קובץ POTX ולמהירות האינטרנט המתן מספר שניות
1. לחץ על הלחצן 'הסר' כדי לנקות הערות
1. הורד את הקובץ באופן מיידי

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="הסר הערות מצגת POTX באמצעות אפליקציית אנדרואיד" %}}

1. הוסף הפניה לספרייה לפרויקט אנדרואיד 
1. טען POTX באמצעות אובייקט מחלקת מצגת
1. חזור על כל מחבר באמצעות אוסף Presentation.getCommentAuthors() 
1. הפעל את שיטת clear() כדי למחוק את ההערה שלה
1. לבסוף התקשר ל-getCommentAuthors().clear() כדי להסיר את כל המחברים
1. התקשר לשיטת השמירה כדי לשמור את הקובץ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד: מחק הערות ומחברים ממצגת POTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="הוסף הערות למצגת POTX באמצעות אפליקציית אנדרואיד" %}}

1. הוסף הפניה לספרייה לפרויקט אנדרואיד 
1. טען POTX באמצעות אובייקט מחלקת מצגת
1. הפעל את Presentation.getCommentAuthors().addAuthor(String, String) כדי להוסיף את המחברים
1. השתמש ב-ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date) להוספת הערות 
1. התקשר לשיטת השמירה כדי לשמור את הקובץ with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד: הוספת הערות" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>פתח את אפליקציית Android הערת מסמכים POTX</h2>

צריך לפתח אפליקציה או כלי עזר ניידים להערות POTX כדי לספק משוב, להציע הצעות או לשתף פעולה עם אחרים במסמך? עם [Aspose.Slides for Android via Java](https://products.aspose.com/slides/iw/android-java/), ילד API של [Aspose.Total for Android via Java](https://products.aspose.com/total/iw/android-java/), כל מפתח אנדרואיד יכול לשלב את קוד ה-API שלעיל בתוך אפליקציית הערת המסמכים שלו. ספריית אנדרואיד רבת עוצמה מאפשרת לתכנת כל פתרון להערות מסמכים. יתר על כן, זה יכול לתמוך בפורמטים פופולריים רבים כולל פורמט POTX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ספריית אנדרואיד להוספת הערות לקבצי POTX" %}}

- אנו מארחים את חבילות ה-Java שלנו ב-[מאגרי מייבן](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/). 
- Aspose.Slides for Java הוא קובץ JAR נפוץ המכיל קוד בתים. 
- עקוב אחר ה-[הוראות שלב אחר שלב](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) כיצד להתקין Aspose.Slides for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

- J2SE 6.0 (Java 1.6) ומעלה
- חבילת Java היא חוצת פלטפורמות ופועלת על כל מערכות ההפעלה עם הטמעת JVM.

<br />
לפרטים נוספים, עיין ב-[תיעוד המוצר](https://docs.aspose.com/slides/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}