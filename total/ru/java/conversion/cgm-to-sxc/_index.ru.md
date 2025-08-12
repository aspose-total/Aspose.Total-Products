---
title: Java API для рендеринга CGM в SXC
description: Экспорт CGM в SXC через Java API без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/java/conversion/cgm-to-sxc/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SXC
otherformats: FODS DIF MD XLSB EXCEL XLTX XLAM TSV XLTM ODS TXT XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт CGM в SXC через Java" h2="Преобразование файла CGM в SXC с помощью локального Java API в любых приложениях Java J2SE, J2EE, J2ME." >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете интегрировать функцию преобразования CGM в SXC в свои Java-приложения в два этапа. Во-первых, с помощью [Aspose.PDF для Java](https://products.aspose.com/pdf/java/) вы можете преобразовать CGM в XLSX. На втором этапе вы можете конвертировать XLSX в SXC с помощью API программирования электронных таблиц [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать файл CGM в SXC через Java" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте CGM в XLSX, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате SXC, используя [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Cells для Java](https://docs.aspose.com/cells/java/installation/) в вашем pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Если ваш документ CGM защищен паролем, вы не сможете преобразовать его в SXC без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного CGM в SXC через Java" %}}
При преобразовании файла CGM в SXC вы также можете добавить водяной знак в выходной формат файла SXC. Чтобы добавить водяной знак, создайте новую рабочую книгу, чтобы открыть преобразованный файл XLSX. Выберите рабочий лист через его индекс, создайте форму и используйте ее функцию addTextEffect, установите цвета, прозрачность и многое другое. После этого вы можете сохранить документ XLSX в формате SXC с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM в SXC (формат OpenOffice Calc) конверсия позволяет интегрировать техническую графику или табличные данные в системы электронных таблиц с открытым исходным кодом. Он поддерживает совместимость с LibreOffice и другими платформами на основе открытых документов.

## ✅ Основные случаи использования
- **Интеграция Таблиц Инженерии** – Совмещение диаграмм с таблицами данных для технических отчетов.
- **Архивирование Технических Иллюстраций на Основе Векторов** – Хранение векторных технических иллюстраций наряду с данными.
- **Совместимость с Инструментами на Основе LibreOffice** – Обеспечение плавного использования файлов в кроссплатформенных средах.

## ⚙️ Сценарии автоматизации
- **Рабочие процессы трансформации данных, управляемые Java** – Преобразование CGM в форматы, готовые к использованию в электронных таблицах.
- **Рутины ETL для Открытых Документов** – Автоматизация импорта векторных диаграмм в электронные таблицы.
- **Системы Отчетности для Кроссплатформенных Сред** – Встраивание визуальных элементов в автоматизированную генерацию отчетов.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}