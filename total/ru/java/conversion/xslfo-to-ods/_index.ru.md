---
title: Java API для рендеринга XSLFO в ODS
description: Экспорт XSLFO в ODS через Java API без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/java/conversion/xslfo-to-ods/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: ODS
otherformats: TXT XLSB EXCEL XLT DIF XLTM FODS XLAM XLTX SXC XLSM MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт XSLFO в ODS через Java" h2="Преобразование файла XSLFO в ODS с помощью локального Java API в любых приложениях Java J2SE, J2EE, J2ME." >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете интегрировать функцию преобразования XSLFO в ODS в свои Java-приложения в два этапа. Во-первых, с помощью [Aspose.PDF для Java](https://products.aspose.com/pdf/java/) вы можете преобразовать XSLFO в XLSX. На втором этапе вы можете конвертировать XLSX в ODS с помощью API программирования электронных таблиц [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать файл XSLFO в ODS через Java" %}}
1. Откройте файл XSLFO, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте XSLFO в XLSX, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате ODS, используя [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Cells для Java](https://docs.aspose.com/cells/java/installation/) в вашем pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Если ваш документ XSLFO защищен паролем, вы не сможете преобразовать его в ODS без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного XSLFO в ODS через Java" %}}
При преобразовании файла XSLFO в ODS вы также можете добавить водяной знак в выходной формат файла ODS. Чтобы добавить водяной знак, создайте новую рабочую книгу, чтобы открыть преобразованный файл XLSX. Выберите рабочий лист через его индекс, создайте форму и используйте ее функцию addTextEffect, установите цвета, прозрачность и многое другое. После этого вы можете сохранить документ XLSX в формате ODS с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Преобразование XSLFO в **ODS (OpenDocument Spreadsheet)** обеспечивает совместимость с современными приложениями для электронных таблиц с открытым исходным кодом. ODS сохраняет стили, формулы и таблицы, что делает его идеальным для совместного создания отчетов и обмена данными.



{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}



* Преобразование XSLFO-отчетов по кадровому делу для пользователей LibreOffice.

* Обмен квартальной аналитикой с внешними партнерами в формате ODS.

* Подготовка оперативных панелей управления для межотделенческого обзора.

* Архивирование финансовых таблиц на основе XSLFO в перспективном открытом формате.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}



* Преобразование XSLFO в ODS в реальном времени для совместных офисных сред.

* Плановый пакетный экспорт операционных показателей из XSLFO.

* Интеграция в автоматизированные конвейеры отчетности для удаленных команд.

* Автоматическое создание электронных таблиц ODS из шаблонов XSLFO для повторяющихся отчетов.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}