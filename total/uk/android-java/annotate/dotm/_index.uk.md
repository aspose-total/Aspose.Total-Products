---
title: Видаліть анотацію DOTM онлайн або керуйте анотаціями за допомогою мобільних програм Android
description: видалити коментарі з файлу DOTM через онлайн-програму безкоштовно. Код Android API для керування коментарями файлів DOTM.

family: total
platformtag: Android
feature: Annotate
informat: DOTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Очистіть коментарі з документа DOTM в Інтернеті або керуйте через програми Android" h2="Розробіть потужну службову програму анотації документів DOTM на базі Android. Наведено код для керування коментарями файлу DOTM." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Видаліть анотації DOTM онлайн" %}}

1. Імпортуйте файл DOTM, щоб видалити коментарі, завантаживши його
1. Зробіть це, клацнувши всередині області перетягування за допомогою програми для анотацій
1. Залежно від розміру файлу DOTM і швидкості Інтернету зачекайте кілька секунд
1. Натисніть кнопку «Видалити», щоб видалити коментарі
1. Миттєво завантажте файл

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Видаліть коментарі до документів DOTM за допомогою програми Android" %}}

1. Додайте посилання на бібліотеку до проекту Android 
1. Завантажити документ через об’єкт класу документа
1. Отримайте всі коментарі з усіх вузлів за допомогою [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) і NodeType.COMMENT 
1. Викличте метод [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear), щоб видалити всі коментарі
1. Викличте метод збереження, щоб зберегти файл.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Код: видалити коментарі з файлу DOTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Видалити та додати коментар DOTM Відповідь" %}}

1. Додайте посилання на бібліотеку до проекту Android 
1. Завантажити документ через об’єкт класу документа
1. Отримайте коментар за допомогою getChild 
1. Використовуйте [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) для видалення зазначеної відповіді на цей коментар 
1. Використовуйте [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String), щоб додати будь-яку відповідь на цей коментар 
1. Викличте метод збереження, щоб зберегти файл

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Додайте коментарі через додаток для Android" %}}

1. Додайте посилання на бібліотеку до проекту Android 
1. Створити об’єкт класу документа
1. Використовуйте [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/), щоб створити коментар 
1. Використовуйте getParagraphs().add і getFirstParagraph().getRuns().add  
1. Викличте метод збереження, щоб зберегти файл with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Код: видалити та додати відповідь коментаря з файлу DOTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Код: додавання коментарів" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Розробити додаток DOTM для анотації документів для Android</h2>

Потрібно розробити мобільну програму або утиліту анотації DOTM, щоб надавати відгуки, вносити пропозиції чи співпрацювати з іншими над документом? Завдяки [Aspose.Words for Android via Java](https://products.aspose.com/words/uk/android-java/), дочірньому API [Aspose.Total for Android via Java](https://products.aspose.com/total/uk/android-java/), будь-який розробник Android може інтегрувати наведений вище код API у свою програму анотації документів. Потужна бібліотека Android дозволяє програмувати будь-яке рішення для анотації документів. Крім того, він може підтримувати багато популярних форматів, включаючи формат DOTM.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Бібліотека Android для анотування файлів DOTM" %}}

- Ми розміщуємо наші пакети Java у [Репозиторії Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java — це звичайний файл JAR, що містить байт-код. 
- Дотримуйтесь [покрокова інструкція](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/), щоб інсталювати Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Системні вимоги" %}}

- Підтримуються Java SE 7 і новіші версії Java.
- Окремий пакет для Java SE 6 на випадок, якщо потрібно використовувати застарілу JRE.
- Пакет Java є кросплатформним і працює на всіх операційних системах із реалізацією JVM.
- Операційні системи включають Microsoft Windows, Linux, macOS, Android та iOS.

<br />
Для отримання додаткової інформації про додаткові залежності пакетів, як-от JogAmp JOGL, механізм шрифтів Harfbuzz, Java Advanced Imaging JAI, зверніться до [Документація продукту](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}