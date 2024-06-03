---
title: Видаліть анотацію PDF онлайн або керуйте анотаціями за допомогою мобільних програм Android
description: видалити коментарі з файлу PDF через онлайн-програму безкоштовно. Код Android API для керування коментарями файлів PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Очистіть коментарі з документа PDF в Інтернеті або керуйте через програми Android" h2="Розробіть потужну службову програму анотації документів PDF на базі Android. Наведено код для керування коментарями файлу PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Видаліть анотації PDF онлайн" %}}

1. Імпортуйте файл PDF, щоб видалити коментарі, завантаживши його
1. Зробіть це, клацнувши всередині області перетягування за допомогою програми для анотацій
1. Залежно від розміру файлу PDF і швидкості Інтернету зачекайте кілька секунд
1. Натисніть кнопку «Видалити», щоб видалити коментарі
1. Миттєво завантажте файл

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Видаліть коментарі до документів PDF через Android App API" %}}

1. Додайте посилання на бібліотеку до проекту Android 
1. Завантажити документ через об’єкт класу документа
1. Виберіть певну сторінку через getPages().get_Item(Index) 
1. Використовуйте AnnotationSelector і отримуйте всі текстові анотації через annotationSelector.getSelected()
1. Перебирайте кожну анотацію, викликаючи метод delete, щоб видалити її.
1. Викличте метод збереження, щоб зберегти файл.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Код: видалити коментарі з файлу PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Додати анотацію через Android App API" %}}

1. Додайте посилання на бібліотеку до проекту Android 
1. Створити об’єкт класу документа
1. Додайте нову сторінку та вміст за допомогою getPages().add() 
1. Використовуйте getPages().get_Item(Index) класу TextAnnotation
1. Встановіть відповідні анотації, такі як заголовок, тема, вміст тощо
1. Використовуйте getAnnotations().add, щоб додати анотації
1. Викличте метод збереження, щоб зберегти файл із доданими коментарями
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Код: додайте анотацію PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Розробити додаток PDF для анотації документів для Android</h2>

Потрібно розробити мобільну програму або утиліту анотації PDF, щоб надавати відгуки, вносити пропозиції чи співпрацювати з іншими над документом? Завдяки [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/uk/android-java/), дочірньому API [Aspose.Total for Android via Java](https://products.aspose.com/total/uk/android-java/), будь-який розробник Android може інтегрувати наведений вище код API у свою програму анотації документів. Потужна бібліотека Android дозволяє програмувати будь-яке рішення для анотації документів. Крім того, він може підтримувати багато популярних форматів, включаючи формат PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Бібліотека Android для анотування файлів PDF" %}}

- Ми розміщуємо наші пакети Java у [Репозиторії Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java — це звичайний файл JAR, що містить байт-код. 
- Дотримуйтесь [покрокова інструкція](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository), щоб інсталювати Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системні вимоги" %}}

- Android API 31 і 32
- Android 4.0 і вище
- Інструменти Android Studio та SDK

<br />
Для отримання додаткової інформації про додаткові залежності пакетів, як-от JogAmp JOGL, механізм шрифтів Harfbuzz, Java Advanced Imaging JAI, зверніться до [Документація продукту](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}