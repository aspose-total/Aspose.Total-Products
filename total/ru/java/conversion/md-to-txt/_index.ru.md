---
title: Java API для рендеринга MD в TXT
description: Экспорт MD в TXT через Java API без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/java/conversion/md-to-txt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: TXT
otherformats: ODS XLT XLTM XLSM TXT FODS XLTX XLSB DIF XLAM TSV EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт MD в TXT через Java" h2="Преобразование файла MD в TXT с помощью локального Java API в любых приложениях Java J2SE, J2EE, J2ME." >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете интегрировать функцию преобразования MD в TXT в свои Java-приложения в два этапа. Во-первых, с помощью [Aspose.PDF для Java](https://products.aspose.com/pdf/java/) вы можете преобразовать MD в XLSX. На втором этапе вы можете конвертировать XLSX в TXT с помощью API программирования электронных таблиц [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать файл MD в TXT через Java" %}}
1. Откройте файл MD, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте MD в XLSX, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате TXT, используя [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Cells для Java](https://docs.aspose.com/cells/java/installation/) в вашем pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Если ваш документ MD защищен паролем, вы не сможете преобразовать его в TXT без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного MD в TXT через Java" %}}
При преобразовании файла MD в TXT вы также можете добавить водяной знак в выходной формат файла TXT. Чтобы добавить водяной знак, создайте новую рабочую книгу, чтобы открыть преобразованный файл XLSX. Выберите рабочий лист через его индекс, создайте форму и используйте ее функцию addTextEffect, установите цвета, прозрачность и многое другое. После этого вы можете сохранить документ XLSX в формате TXT с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Преобразование файлов Markdown (MD) в TXT (обычный текст) создает чистую, легкую версию вашего контента без форматирования и разметки. Файлы TXT обладают высокой совместимостью, идеальны для обработки текста, написания сценариев и интеграции с приложениями, которые не поддерживают форматирование Markdown.



{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}



* Экспорт документации Markdown для распространения по электронной почте в виде обычного текста.

* Генерация необработанного контента для текстовой аналитики или рабочих процессов машинного обучения.

* Создание легких, портативных копий заметок и документации.

* Обмен контентом Markdown в средах, где не поддерживается богатое форматирование.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}



* Плановое пакетное преобразование репозиториев Markdown в TXT для резервного копирования и архивирования.

* ETL-пайплайны, преобразующие документацию Markdown в TXT для обработки сценариями или инструментами автоматизации.

* Автоматическое создание текстовых журналов из заметок проекта на основе Markdown.

* Интеграция с конвейерами контента для экспорта Markdown в TXT для последующих систем.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}