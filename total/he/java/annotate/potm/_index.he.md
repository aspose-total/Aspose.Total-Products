---
title: הסר הערות POTM באינטרנט או נהל הערות באמצעות Java
description: מחק הערות מקובץ POTM דרך האפליקציה המקוונת בחינם. קוד Java API לניהול הערות של קבצי POTM.

family: total
platformtag: Java
feature: Annotate
informat: POTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="נקה הערות ממצגת POTM באינטרנט או נהל באמצעות Java" h2="פתח יישום כלי עזר להערות מצגת POTM מבוסס Java רב עוצמה. קוד רשום לניהול הערות של קובץ POTM דרך Java." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="הסר הערות POTM באופן מקוון" %}}

1. ייבא קובץ POTM כדי למחוק הערות על ידי העלאתו
1. עשה זאת על ידי לחיצה בתוך אזור השחרור באמצעות גרירה ושחרור של אפליקציית ההערות
1. בהתאם לגודל קובץ POTM ולמהירות האינטרנט המתן מספר שניות
1. לחץ על הלחצן 'הסר' כדי לנקות הערות
1. הורד את הקובץ באופן מיידי

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="הסר הערות למצגת POTM דרך Java" %}}

1. הוסף הפניה לספרייה לפרויקט Java 
1. טען POTM באמצעות אובייקט מחלקת מצגת
1. חזור על כל מחבר באמצעות אוסף [Presentation.getCommentAuthors()](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#getCommentAuthors--) 
1. הפעל את שיטת [clear()](https://reference.aspose.com/slides/java/com.aspose.slides/icommentcollection/#clear--) כדי למחוק את ההערה שלה
1. לבסוף התקשר ל-[getCommentAuthors().clear()](https://reference.aspose.com/slides/java/com.aspose.slides/commentauthorcollection/#clear--) כדי להסיר את כל המחברים
1. התקשר לשיטת השמירה כדי לשמור את הקובץ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="דוגמה לקוד ב-Java למחיקת הערות ומחברים ממצגת POTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="הוסף הערות למצגת POTM באמצעות Java" %}}

1. הוסף הפניה לספרייה לפרויקט Java 
1. טען POTM באמצעות אובייקט מחלקת מצגת
1. הפעל את [Presentation.getCommentAuthors().addAuthor(String, String)](https://reference.aspose.com/slides/java/com.aspose.slides/ICommentAuthorCollection#addAuthor-java.lang.String-java.lang.String-) כדי להוסיף את המחברים
1. השתמש ב-[ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date)](https://reference.aspose.com/slides/java/com.aspose.slides/ICommentCollection#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) להוספת הערות 
1. התקשר לשיטת השמירה כדי לשמור את הקובץ with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד Java: הוספת הערות" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>פתח יישום הערת מסמכים POTM באמצעות Java</h2>

צריך לפתח אפליקציית הערות POTM או כלי עזר כדי לספק משוב, להציע הצעות או לשתף פעולה עם אחרים במסמך? עם [Aspose.Slides for Java](https://products.aspose.com/slides/he/java/), ילד API של [Aspose.Total for Java](https://products.aspose.com/total/he/java/), כל מפתח ג'אווה יכול לשלב את קוד ה-API הנ"ל בתוך יישום הערות המסמכים שלו. ספריית Java רבת עוצמה מאפשרת לתכנת כל פתרון הערות למסמך. יתר על כן, זה יכול לתמוך בפורמטים פופולריים רבים כולל פורמט POTM.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ספריית Java להוספת הערות לקבצי POTM" %}}
ישנן אפשרויות חלופיות להתקנת "[Aspose.Slides for Java](https://products.aspose.com/slides/he/java/)" או "[Aspose.Total for Java](https://products.aspose.com/total/he/java/)" במערכת שלך. חבילת ה-Java שלנו נועדה להיות חוצת פלטפורמות, תואמת להטמעות JVM במערכות הפעלה שונות כגון Microsoft Windows, Linux, macOS, Android ו- iOS. אנא בחר אחד שדומה לצרכים שלך ופעל לפי ההוראות המפורטות:<br />

- התקן [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/)
- או מ-[Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/)
- שלב אחר שלב [הוראות](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

- J2SE 6.0 (Java 1.6) ומעלה

<br />
לפרטים נא עיין ב-[תיעוד המוצר](https://docs.aspose.com/slides/java/system-requirements/#optional-dependencies).

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
                          <span itemprop="name"><b>האם זה בטוח להשתמש באפליקציה המקוונת כדי להוסיף הערות למסמך POTM?</b></span>
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
                          <span itemprop="text">אתה יכול להשתמש בכל דפדפן אינטרנט מודרני כמו גוגל כרום, פיירפוקס, אופרה או ספארי להערות מקוונות במסמך POTM. עם זאת, אם אתה מפתח יישום שולחן עבודה, אנו ממליצים להשתמש ב-API לעיבוד מסמכים Aspose.Total לניהול יעיל.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}