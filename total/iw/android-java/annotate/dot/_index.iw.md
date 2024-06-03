---
title: הסר הערות DOT באינטרנט או נהל הערות באמצעות אפליקציות Android לנייד
description: מחק הערות מקובץ DOT דרך אפליקציה מקוונת בחינם. קוד API של Android לניהול הערות של קבצי DOT.

family: total
platformtag: Android
feature: Annotate
informat: DOT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="נקה הערות מ-DOT Document Online או נהל באמצעות אפליקציות אנדרואיד" h2="פתח אפליקציה חזקה מבוססת אנדרואיד להערות מסמכים DOT. קוד רשום לניהול הערות של קובץ DOT." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="הסר הערות DOT באופן מקוון" %}}

1. ייבא קובץ DOT כדי למחוק הערות על ידי העלאתו
1. עשה זאת על ידי לחיצה בתוך אזור השחרור באמצעות גרירה ושחרור של אפליקציית ההערות
1. בהתאם לגודל קובץ DOT ולמהירות האינטרנט המתן מספר שניות
1. לחץ על הלחצן 'הסר' כדי לנקות הערות
1. הורד את הקובץ באופן מיידי

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="הסר הערות למסמך DOT באמצעות אפליקציית אנדרואיד" %}}

1. הוסף הפניה לספרייה לפרויקט אנדרואיד 
1. טען מסמך באמצעות אובייקט מחלקה Document
1. קבל את כל ההערות מכל הצמתים באמצעות [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) ו-NodeType.COMMENT 
1. הפעל את שיטת [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) כדי למחוק את כל ההערות
1. התקשר לשיטת השמירה כדי לשמור את הקובץ.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד: מחק הערות מקובץ DOT" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="הסר והוסף DOT תגובה תגובה" %}}

1. הוסף הפניה לספרייה לפרויקט אנדרואיד 
1. טען מסמך באמצעות אובייקט מחלקה Document
1. קבל תגובה באמצעות getChild 
1. השתמש ב-[removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) להסרת תשובה שצוינה להערה זו 
1. השתמש ב-[addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) להוספת כל תשובה להערה זו 
1. התקשר לשיטת השמירה כדי לשמור את הקובץ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="הוסף הערות באמצעות אפליקציית אנדרואיד" %}}

1. הוסף הפניה לספרייה לפרויקט אנדרואיד 
1. צור אובייקט בכיתה Document
1. השתמש ב-[Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) כדי ליצור את ההערה 
1. השתמש ב-getParagraphs().add ו-getFirstParagraph().getRuns().add  
1. התקשר לשיטת השמירה כדי לשמור את הקובץ with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד: הסר והוסף תגובה תגובה מקובץ DOT" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="קוד: הוספת הערות" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>פתח את אפליקציית Android הערת מסמכים DOT</h2>

צריך לפתח אפליקציה או כלי עזר ניידים להערות DOT כדי לספק משוב, להציע הצעות או לשתף פעולה עם אחרים במסמך? עם [Aspose.Words for Android via Java](https://products.aspose.com/words/iw/android-java/), ילד API של [Aspose.Total for Android via Java](https://products.aspose.com/total/iw/android-java/), כל מפתח אנדרואיד יכול לשלב את קוד ה-API שלעיל בתוך אפליקציית הערת המסמכים שלו. ספריית אנדרואיד רבת עוצמה מאפשרת לתכנת כל פתרון להערות מסמכים. יתר על כן, זה יכול לתמוך בפורמטים פופולריים רבים כולל פורמט DOT.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ספריית אנדרואיד להוספת הערות לקבצי DOT" %}}

- אנו מארחים את חבילות ה-Java שלנו ב-[מאגרי מייבן](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java הוא קובץ JAR נפוץ המכיל קוד בתים. 
- עקוב אחר ה-[הוראות שלב אחר שלב](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) כיצד להתקין Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

- Java SE 7 וגרסאות Java עדכניות יותר נתמכות.
- חבילה נפרדת עבור Java SE 6 למקרה שחייבים להשתמש ב-JRE מיושן.
- חבילת Java היא חוצת פלטפורמות ופועלת על כל מערכות ההפעלה עם הטמעת JVM.
- מערכות ההפעלה כוללות Microsoft Windows, Linux, macOS, Android ו- iOS.

<br />
לפרטים נוספים על תלות אופציונלית בחבילות, כגון JogAmp JOGL, מנוע הגופנים Harfbuzz, Java Advanced Imaging JAI, עיין ב-[תיעוד המוצר](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}