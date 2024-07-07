---
title: הסר הערות DOTM באינטרנט או נהל הערות באמצעות .NET
description: מחק הערות מקובץ DOTM דרך אפליקציה מקוונת בחינם. קוד NET API לניהול הערות של קבצי DOTM.

family: total
platformtag: net
feature: Annotate
informat: DOTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="נקה הערות מ-DOTM Document Online או נהל באמצעות NET" h2="פתח יישום רב עוצמה המבוסס על DOTM מסמכים DOTM. קוד רשום לניהול הערות של קובץ DOTM דרך NET." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="הסר הערות DOTM באופן מקוון" %}}

1. ייבא קובץ DOTM כדי למחוק הערות על ידי העלאתו
1. עשה זאת על ידי לחיצה בתוך אזור השחרור באמצעות גרירה ושחרור של אפליקציית ההערות
1. בהתאם לגודל קובץ DOTM ומהירות האינטרנט המתן מספר שניות
1. לחץ על הלחצן 'הסר' כדי לנקות הערות
1. הורד את הקובץ באופן מיידי

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="מחק הערות מסמך DOTM של מחבר ספציפי באמצעות NET" %}}

1. הוסף הפניה לספרייה לפרויקט NET 
1. טען מסמך באמצעות אובייקט מחלקה Document
1. קבל את כל ההערות לצמתים באמצעות GetChildNodes עם NodeType.Comment
1. חזור על כל ההערות והתאם את שם המחבר
1. התקשר לשיטת הסר כדי למחוק את הערת המחבר הספציפית

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד C#: מחק הערות מחבר ספציפיות מקובץ DOTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="הוסף הערות באמצעות NET" %}}

1. צור אובייקט בכיתה Document
1. השתמש בכיתה הערה
1. הוסף את הפסקה החדשה באמצעות Paragraphs.Add
1. השתמש ב-FirstParagraph.Runs. הוסף את הוספה של ההערה
1. או דרך אחרת היא להשתמש במחלקות CommentRangeStart ו-CommentRangeEnd 
1. התקשר לשיטת השמירה כדי לשמור את הקובץ עם הערות נוספות

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="חלץ את כל ההערות" %}}

1. טען מסמך באמצעות אובייקט מחלקה Document
1. צור אובייקט ArrayList
1. קבל את כל GetChildNodes ב-NodeCollection
1. חזור על כל אוסף והוסף הערות ב-ArrayList

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="קוד NET : הוסף תגובה מקובץ DOTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: חלץ את כל ההערות" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>פתח יישום הערת מסמכים DOTM באמצעות NET</h2>

צריך לפתח אפליקציית הערות DOTM או כלי עזר כדי לספק משוב, להציע הצעות או לשתף פעולה עם אחרים במסמך? עם [Aspose.Words for .NET](https://products.aspose.com/words/net/) צאצא API של [Aspose.Total for .NET](https://products.aspose.com/total/he/net/), כל מפתח NET יכול לשלב את קוד ה-API שלמעלה בתוך יישום הערת המסמכים שלו. ספריית .NET רבת עוצמה מאפשרת לתכנת כל פתרון להערות מסמכים. יתר על כן, זה יכול לתמוך בפורמטים פופולריים רבים כולל פורמט DOTM.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ספריית NET לביאור קבצי DOTM" %}}

ישנן שלוש אפשרויות חלופיות להתקנת "Aspose.Words for .NET" או "Aspose.Total for .NET" על המערכת שלך. אנא בחר אחד שדומה לצרכים שלך ופעל לפי ההוראות המפורטות:<br />

- התקן [חבילת NuGet](https://www.nuget.org/packages/Aspose.Words/). ראה [תיעוד](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- התקן את הספרייה באמצעות [קונסולת מנהל החבילות](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) בתוך Visual Studio IDE
- התקן את הספרייה ביד באמצעות [מתקין וינדוס](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

המוצר שלנו הוא חוצה פלטפורמות לחלוטין ותומך בכל ההטמעות העיקריות של .NET בהתאם למפרט '.NET Standard 2.0':<br />

- Microsoft .NET Framework, החל מגירסת 2.0 המוקדמת ביותר, וכלה בגרסה העדכנית ביותר של '.NET Framework 4.8'
- .NET Core, החל מגרסה 2.0 המוקדמת ביותר, וכלה בגרסה האחרונה של '.NET 6'
- מונו >= 2.6.7
<br /><br />
מכיוון שקוד .NET אינו מסתמך על החומרה או מערכת ההפעלה הבסיסית, אלא רק על מכונה וירטואלית, כך שאתה חופשי לפתח כל סוג של תוכנה עבור Windows, macOS, Android, iOS ו-Linux. רק ודא שהתקנת את הגרסה המתאימה של .NET Framework, .NET Core, Windows Azure, Mono או Xamarin.<br /><br />
אנו ממליצים להשתמש ב-Microsoft Visual Studio, Xamarin ו-MonoDevelop IDE כדי ליצור יישומי C#, F#, VB.NET.
<br /><br />
לפרטים נוספים, עיין ב-[תיעוד המוצר](https://docs.aspose.com/words/net/system-requirements/).

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
                          <span itemprop="name"><b>האם אוכל להשתמש בקוד NET לעיל ביישום שלי?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">כן, אתה מוזמן להוריד את הקוד הזה ולהשתמש בו לצורך פיתוח יישום הערות מסמכים מבוסס NET. קוד זה יכול לשמש משאב רב ערך לשיפור הפונקציונליות והיכולות של הפרויקטים שלך בתחום עיבוד המסמכים האחוריים והמניפולציה.</span>
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
                          <span itemprop="name"><b>האם זה בטוח להשתמש באפליקציה המקוונת כדי להוסיף הערות למסמך DOTM?</b></span>
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
                          <span itemprop="text">אתה יכול להשתמש בכל דפדפן אינטרנט מודרני כמו גוגל כרום, פיירפוקס, אופרה או ספארי להערות מקוונות במסמך DOTM. עם זאת, אם אתה מפתח יישום שולחן עבודה, אנו ממליצים להשתמש ב-API לעיבוד מסמכים Aspose.Total לניהול יעיל.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}