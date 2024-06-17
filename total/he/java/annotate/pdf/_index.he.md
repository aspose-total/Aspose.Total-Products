---
title: הסר הערות PDF באינטרנט או נהל הערות באמצעות Java
description: מחק הערות מקובץ PDF דרך האפליקציה המקוונת בחינם. קוד Java API לניהול הערות של קבצי PDF.

family: total
platformtag: Java
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="נקה הערות מ-PDF Document Online או נהל באמצעות Java" h2="פתח יישום רב עוצמה מבוסס Java PDF להערות מסמכים. קוד רשום לניהול הערות של קובץ PDF דרך Java." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="הסר הערות PDF באופן מקוון" %}}

1. ייבא קובץ PDF כדי למחוק הערות על ידי העלאתו
1. עשה זאת על ידי לחיצה בתוך אזור השחרור באמצעות גרירה ושחרור של אפליקציית ההערות
1. בהתאם לגודל קובץ PDF ולמהירות האינטרנט המתן מספר שניות
1. לחץ על הלחצן 'הסר' כדי לנקות הערות
1. הורד את הקובץ באופן מיידי

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="הסר הערות למסמך PDF דרך Java" %}}

1. הוסף הפניה לספרייה לפרויקט Java 
1. טען מסמך באמצעות אובייקט מחלקה Document
1. בחר את הדף הספציפי באמצעות getPages().get_Item(Index) 
1. השתמש ב-AnnotationSelector וקבל את כל הערות הטקסט באמצעות annotationSelector.getSelected()
1. חזור על כל הערה וקרא לשיטת המחיקה כדי להסיר אותה.
1. התקשר לשיטת השמירה כדי לשמור את הקובץ.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד Java למחיקת הערות מקובץ PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="הוסף הערה באמצעות Java" %}}

1. הוסף הפניה לספרייה לפרויקט Java 
1. צור אובייקט בכיתה Document
1. הוסף את הדף והתוכן החדשים באמצעות getPages().add() 
1. השתמש ב-getPages().get_Item(Index) של המחלקה TextAnnotation
1. הגדר את ההערות הרלוונטיות כגון כותרת, נושא, תוכן וכו'
1. השתמש ב-getAnnotations().add כדי להוסיף את ההערות
1. התקשר לשיטת השמירה כדי לשמור את הקובץ עם הערות נוספות
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד Java להוספת ביאור PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>פתח יישום הערת מסמכים PDF באמצעות Java</h2>

צריך לפתח אפליקציית הערות PDF או כלי עזר כדי לספק משוב, להציע הצעות או לשתף פעולה עם אחרים במסמך? עם [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), ילד API של [Aspose.Total for Java](https://products.aspose.com/total/java/), כל מפתח ג'אווה יכול לשלב את קוד ה-API הנ"ל בתוך יישום הערות המסמכים שלו. ספריית Java רבת עוצמה מאפשרת לתכנת כל פתרון הערות למסמך. יתר על כן, זה יכול לתמוך בפורמטים פופולריים רבים כולל פורמט PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ספריית Java לביאור קבצי PDF" %}}
ישנן אפשרויות חלופיות להתקנת "[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)" או "[Aspose.Total for Java](https://products.aspose.com/total/java/)" במערכת שלך. חבילת ה-Java שלנו נועדה להיות חוצת פלטפורמות, תואמת להטמעות JVM במערכות הפעלה שונות כגון Microsoft Windows, Linux, macOS, Android ו- iOS. אנא בחר אחד שדומה לצרכים שלך ופעל לפי ההוראות המפורטות:<br />

- התקן [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)
- או מ-[Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/)
- שלב אחר שלב [הוראות](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

- J2SE 8.0 (1.8) ומעלה
- תמיכה ב-Aspose.PDF עבור Java ב-IBM i (Iseries או As/400)

<br />
לפרטים נא עיין ב-[תיעוד המוצר](https://docs.aspose.com/pdf/java/system-requirements/#optional-dependencies).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="שאלות נפוצות" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>שאלות נפוצות</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>האם אוכל להשתמש בקוד Java לעיל באפליקציה שלי?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">כן, אתה מוזמן להוריד את הקוד הזה ולהשתמש בו לצורך פיתוח יישום הערות מסמכים מבוסס Java. קוד זה יכול לשמש משאב רב ערך לשיפור הפונקציונליות והיכולות של הפרויקטים שלך בתחום עיבוד המסמכים האחוריים והמניפולציה.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>האם אפליקציית הערות מסמכים מקוונת זו פועלת רק ב-Windows?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">יש לך את הגמישות ליזום הערת מסמכים להסרת הערות בכל מכשיר, ללא קשר למערכת ההפעלה עליה הוא פועל, בין אם זה Windows, Linux, Mac OS או Android. כל מה שנדרש הוא דפדפן אינטרנט עכשווי וחיבור אינטרנט פעיל.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>האם זה בטוח להשתמש באפליקציה המקוונת כדי להוסיף הערות למסמך PDF?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">כמובן! קבצי הפלט שנוצרו באמצעות השירות שלנו יוסרו בצורה מאובטחת ואוטומטית מהשרתים שלנו בתוך מסגרת זמן של 24 שעות. כתוצאה מכך, קישורי התצוגה המשויכים לקבצים אלה יפסיקו לפעול לאחר תקופה זו.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>באיזה דפדפן צריך להשתמש באפליקציה?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">אתה יכול להשתמש בכל דפדפן אינטרנט מודרני כמו גוגל כרום, פיירפוקס, אופרה או ספארי להערות מקוונות במסמך PDF. עם זאת, אם אתה מפתח יישום שולחן עבודה, אנו ממליצים להשתמש ב-API לעיבוד מסמכים Aspose.Total לניהול יעיל.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}