---
title: Java API для рендеринга CGM в TXT
description: Экспорт CGM в TXT через Java API без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт CGM в TXT через Java" h2="Преобразование файла CGM в TXT с помощью локального Java API в любых приложениях Java J2SE, J2EE, J2ME." >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете интегрировать функцию преобразования CGM в TXT в свои Java-приложения в два этапа. Во-первых, с помощью [Aspose.PDF для Java](https://products.aspose.com/pdf/java/) вы можете преобразовать CGM в XLSX. На втором этапе вы можете конвертировать XLSX в TXT с помощью API программирования электронных таблиц [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать файл CGM в TXT через Java" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте CGM в XLSX, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
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
Если ваш документ CGM защищен паролем, вы не сможете преобразовать его в TXT без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного CGM в TXT через Java" %}}
При преобразовании файла CGM в TXT вы также можете добавить водяной знак в выходной формат файла TXT. Чтобы добавить водяной знак, создайте новую рабочую книгу, чтобы открыть преобразованный файл XLSX. Выберите рабочий лист через его индекс, создайте форму и используйте ее функцию addTextEffect, установите цвета, прозрачность и многое другое. После этого вы можете сохранить документ XLSX в формате TXT с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
Преобразование файлов **Computer Graphics Metafile (CGM)** в формат **TXT (Plain Text)** ценно для извлечения, документирования и обработки информации о векторной графике в легкочитаемой форме. В **Java-приводимых конвейерах обработки данных** это преобразование позволяет преобразовывать диаграммы CGM в текстовые представления для ведения журналов, хранения метаданных или последующего анализа. Захватывая описательные элементы файлов CGM в формате TXT, организации могут упростить интеграцию с другими системами, обеспечить быстрый поиск и индексацию, а также обеспечить долгосрочную совместимость.



{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}

- **Журналирование диаграмм в текстовом формате**  
  Сохраняйте информацию о диаграммах CGM в виде обычного текста для проверки, отладки или архивирования.

- **Извлечение описаний векторной графики**  
  Преобразуйте структуры CGM в формат TXT для разбора, индексации поиска или интеграции с инструментами аналитики.

- **Документирование метаданных инженерных данных**  
  Документируйте инженерные данные, связанные с CGM, в файлах TXT для быстрого доступа и легкого хранения.


{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}

- **Библиотеки ввода-вывода Java для преобразования**  
  Используйте стандартные API обработки файлов Java вместе с парсерами CGM для извлечения и записи содержимого в файлы TXT.

- **Службы наблюдения за файлами**  
  Автоматизируйте преобразование CGM в TXT, отслеживая каталоги с помощью службы `WatchService` Java для событий создания новых файлов.

- **Пакетные задания преобразования**  
  Обрабатывайте большие объемы файлов CGM в запланированных заданиях Java, экспортируя текстовые представления для архивирования или анализа.

- **Экспортеры обычного текста в конвейерах ETL**  
  Интегрируйте разбор CGM и экспорт в TXT в рабочие процессы извлечения-трансформации-загрузки на основе Java для обработки структурированных данных.
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}