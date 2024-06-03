---
title: Видаліть анотацію TSV онлайн або керуйте анотаціями за допомогою мобільних програм Android
description: видалити коментарі з файлу TSV через онлайн-програму безкоштовно. Код Android API для керування коментарями файлів TSV.

family: total
platformtag: Android
feature: Annotate
informat: TSV
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Очистіть коментарі з документа TSV в Інтернеті або керуйте через програми Android" h2="Розробіть потужну службову програму анотації документів TSV на базі Android. Наведено код для керування коментарями файлу TSV." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Видаліть анотації TSV онлайн" %}}

1. Імпортуйте файл TSV, щоб видалити коментарі, завантаживши його
1. Зробіть це, клацнувши всередині області перетягування за допомогою програми для анотацій
1. Залежно від розміру файлу TSV і швидкості Інтернету зачекайте кілька секунд
1. Натисніть кнопку «Видалити», щоб видалити коментарі
1. Миттєво завантажте файл

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Видаліть коментарі до документів TSV через Android App API" %}}

1. Додайте посилання на бібліотеку до проекту Android 
1. Завантажити документ через об’єкт класу Workbook
1. Виберіть конкретний аркуш
1. Отримати всі коментарі з використанням [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. Отримайте всі ланцюгові коментарі через getThreadedComments
1. Використовуйте removeAt, щоб видалити коментарі та авторів відповідно
1. Викличте метод збереження, щоб зберегти файл
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Код: видалити коментарі з документа TSV" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Оновити ланцюгові коментарі TSV" %}}

1. Завантажити документ через об’єкт класу Workbook
1. Отримайте окремий робочий аркуш 
1. Отримайте ланцюговий коментар за допомогою getComments().getThreadedComments(Index).get(Index)
1. Використовуйте метод setNotes, щоб оновити коментар 
1. Викличте метод збереження, щоб зберегти файл

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Додайте коментарі через Android App API" %}}

1. Створити документ через об’єкт класу Workbook
1. Отримайте окремий робочий аркуш
1. Додайте індекс коментарів через getComments().add
1. Використовуйте метод setNotes, щоб додати коментар  
1. Викличте метод збереження, щоб зберегти файл with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Код: оновити коментар до файлу TSV" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Код: додавання коментарів" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Розробити додаток TSV для анотації документів для Android</h2>

Потрібно розробити програму або утиліту анотації TSV на основі Android, щоб надавати відгуки, вносити пропозиції чи співпрацювати з іншими над документом? Завдяки [Aspose.Cells for Android via Java](https://products.aspose.com/cells/uk/android-java/), дочірньому API [Aspose.Total for Android via Java](https://products.aspose.com/total/uk/android-java/), будь-який розробник Android може інтегрувати наведений вище код API у свою програму анотації документів. Потужна бібліотека Android дозволяє програмувати будь-яке рішення для анотації документів. Крім того, він може підтримувати багато популярних форматів, включаючи формат TSV.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для анотування файлів TSV" %}}

- Ми розміщуємо наші пакети Java у [Репозиторії Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/). 
- Aspose.Cells for Java — це звичайний файл JAR, що містить байт-код. 
- Дотримуйтесь [покрокова інструкція](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository), щоб інсталювати Aspose.Cells for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Системні вимоги" %}}

- ОС Android 2.0 або вище.
- Пакет Java є кросплатформним і працює на всіх операційних системах із реалізацією JVM.

<br />
Для отримання додаткової інформації зверніться до [Документація продукту](https://docs.aspose.com/cells/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}