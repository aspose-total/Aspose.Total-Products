---
title: Удаление аннотаций ODS онлайн или управление аннотациями с помощью мобильных приложений Android
description: удалять комментарии из файла ODS через онлайн-приложение бесплатно.Код Android API для управления комментариями к файлам ODS.

family: total
platformtag: Android
feature: Annotate
informat: ODS
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Удаление комментариев из документа ODS онлайн или управление ими через приложения для Android" h2="Разработайте мощное приложение для аннотирования документов ODS на базе Android.Перечислен код для управления комментариями к файлу ODS." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Удаление аннотаций ODS онлайн" %}}

1. Импортируйте файл ODS, чтобы удалить комментарии, загрузив его.
1. Сделайте это, щелкнув внутри области перетаскивания с помощью перетаскивания приложения аннотаций.
1. В зависимости от размера файла ODS и скорости интернета подождите несколько секунд.
1. Нажмите кнопку «Удалить», чтобы удалить комментарии.
1. Загрузите файл мгновенно

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Удаление комментариев к документу ODS через API приложения Android" %}}

1. Добавить ссылку на библиотеку в проект Android
1. Загрузить документ через объект класса Workbook
1. Выберите конкретный рабочий лист
1. Получить все комментарии от использования [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. Получить все вложенные комментарии через getThreadedComments
1. Используйте команду RemoveAt, чтобы удалить комментарии и авторов соответственно.
1. Вызовите метод save, чтобы сохранить файл.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Код: удалить комментарии из документа ODS." offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Обновление связанных комментариев ODS" %}}

1. Загрузить документ через объект класса Workbook
1. Получите конкретный рабочий лист
1. Получите вложенный комментарий, используя getComments().getThreadedComments(Index).get(Index).
1. Используйте метод setNotes для обновления комментария
1. Вызовите метод save, чтобы сохранить файл.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Добавляйте комментарии через API приложений Android" %}}

1. Создать документ через объект класса Workbook
1. Получите конкретный рабочий лист
1. Добавить индекс комментариев через getComments().add
1. Используйте метод setNotes для добавления комментария
1. Вызовите метод save, чтобы сохранить файл. with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Код: обновление резьбового комментария к файлу ODS." offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Код: Добавление комментариев" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Разработка Android-приложения для аннотаций документов ODS</h2>

Вам нужно разработать приложение или утилиту для аннотаций ODS на базе Android, чтобы оставлять отзывы, вносить предложения или сотрудничать с другими над документом?Благодаря [Aspose.Cells for Android via Java](https://products.aspose.com/cells/ru/android-java/), дочернему API [Aspose.Total for Android via Java](https://products.aspose.com/total/ru/android-java/), любой разработчик Android может интегрировать приведенный выше код API в свое приложение для аннотаций документов.Мощная библиотека Android позволяет программировать любое решение для аннотаций документов.Более того, он может поддерживать многие популярные форматы, включая формат ODS.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для аннотирования файлов ODS" %}}

- Мы размещаем наши Java-пакеты в формате [Репозитории Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/). 
- Aspose.Cells for Java — это обычный файл JAR, содержащий байт-код.
- Следуйте [пошаговые инструкции](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) о том, как установить Aspose.Cells for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

- ОС Android 2.0 или выше.
- Пакет Java является кроссплатформенным и работает во всех операционных системах с реализацией JVM.

<br />
Для получения более подробной информации обратитесь к [Документация продукта](https://docs.aspose.com/cells/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}