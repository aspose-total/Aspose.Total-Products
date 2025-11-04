---
title: Java API для рендеринга XSLFO в FODS
description: Экспорт XSLFO в FODS через Java API без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/java/conversion/xslfo-to-fods/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: FODS
otherformats: XLAM ODS FODS XLTM XLT TSV SXC MD EXCEL XLTX XLSM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт XSLFO в FODS через Java" h2="Преобразование файла XSLFO в FODS с помощью локального Java API в любых приложениях Java J2SE, J2EE, J2ME." >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете интегрировать функцию преобразования XSLFO в FODS в свои Java-приложения в два этапа. Во-первых, с помощью [Aspose.PDF для Java](https://products.aspose.com/pdf/java/) вы можете преобразовать XSLFO в XLSX. На втором этапе вы можете конвертировать XLSX в FODS с помощью API программирования электронных таблиц [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать файл XSLFO в FODS через Java" %}}
1. Откройте файл XSLFO, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте XSLFO в XLSX, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате FODS, используя [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Cells для Java](https://docs.aspose.com/cells/java/installation/) в вашем pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Если ваш документ XSLFO защищен паролем, вы не сможете преобразовать его в FODS без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного XSLFO в FODS через Java" %}}
При преобразовании файла XSLFO в FODS вы также можете добавить водяной знак в выходной формат файла FODS. Чтобы добавить водяной знак, создайте новую рабочую книгу, чтобы открыть преобразованный файл XLSX. Выберите рабочий лист через его индекс, создайте форму и используйте ее функцию addTextEffect, установите цвета, прозрачность и многое другое. После этого вы можете сохранить документ XLSX в формате FODS с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Преобразование файлов XSLFO в формат **FODS (Flat OpenDocument Spreadsheet)** поддерживает офисные пакеты с открытым исходным кодом, такие как LibreOffice и OpenOffice. FODS позволяет создавать легкие, редактируемые электронные таблицы на основе XML, подходящие для совместной работы.



{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}



* Обмен бюджетными таблицами, созданными в формате XSLFO, с пользователями офисных пакетов с открытым исходным кодом.

* Архивирование отчетов в открытом стандартизированном формате электронных таблиц.

* Подготовка таблиц отслеживания проектов для совместной работы на различных платформах.

* Преобразование технических таблиц XSLFO в редактируемые электронные таблицы FODS.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}



* Пакетное преобразование XSLFO в FODS для открытых отчетных конвейеров.

* Интеграция в системы управления документами, поддерживающие формат FODS.

* Запланированный экспорт для совместных дашбордов проектов.

* Автоматическое преобразование отчетов по аналитике XSLFO в формат FODS.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}