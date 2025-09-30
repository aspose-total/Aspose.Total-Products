---
title: Онлайн-конвертация PDF в MHTML или разработка приложения на основе Java для конвертации файлов PDF
description: Бесплатное онлайн-приложение для конвертации файлов PDF в MHTML. Код библиотеки конвертации Java для документов PDF. 

family: total
platformtag: Java
feature: conversion
informat: PDF
outformat: MHTML
otherformats: XAMLFLOW DOTX OTT RTF WORDML MARKDOWN PCL PS FLATOPC DOTM DOT MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Онлайн-приложение для преобразования PDF в MHTML и код Java для преобразования файлов PDF" h2="Разработать мощное приложение для преобразования и экспорта PDF на основе Java. Конвертируйте один или несколько файлов PDF в MHTML и другие форматы с помощью API автоматизации Java. Бесплатно конвертируйте файлы PDF онлайн через приложение с мгновенной загрузкой." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Бесплатное онлайн-приложение для конвертации PDF в MHTML" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=mhtml&from=pdf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертируйте файлы PDF в MHTML онлайн с помощью приложения" %}}

1. Загрузите файлы PDF для конвертации
1. Подождите несколько секунд или больше в зависимости от размера PDF
1. Следите за строкой состояния загрузки.
1. Нажмите кнопку «Конвертировать».
1. PDF будет преобразован в документ MHTML
1. Загрузите преобразованный файл MHTML

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование PDF в MHTML с помощью Java Automation API" %}}


1. Откройте файл PDF, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте PDF в DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите файл DOC с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате MHTML, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите MHTML как СохранитьФормат



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "48b55393e52dd85032905dea500a496b" "convert-pdf-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Еще несколько случаев сохранения PDF в MHTML с другими функциями, такими как Требования к конвертации, Открыть защищенный паролем документ PDF через Java.

{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Разработать приложение для преобразования файлов PDF с использованием Java</h2>

Необходимо разработать программное приложение на базе Java для простого сохранения и экспорта файлов PDF в документ MHTML? С помощью [Aspose.Total for Java](https://products.aspose.com/total/ru/java/) любой разработчик Java может интегрировать вышеуказанный код API для программирования приложения для преобразования в различные форматы, включая Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, файлы электронной почты, изображения (JPG, PNG, BMP, GIF) и другие форматы. Мощная библиотека Java для преобразования документов, поддерживает множество популярных форматов, включая формат PDF. Экспортируя и преобразуя документы в другие форматы, программисты могут использовать дочерние API Aspose.Total for Java, включая [Aspose.Words for Java](https://products.aspose.com/words/ru/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/ru/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/ru/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/ru/java/) и другие.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF Библиотека преобразования для Java" %}}

Существуют альтернативные варианты интеграции Aspose.Total for Java в вашу систему. Пожалуйста, выберите тот вариант, который соответствует вашим потребностям, и следуйте пошаговым инструкциям:<br /><br />

- Используйте Aspose.Total for Java непосредственно из проекта на базе Maven и включите соответствующий дочерний API в pom.xml.
- Кроме того, можно получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Сохранение PDF в MHTML Требования к приложению" %}}

Любая операционная система, поддерживающая Java Runtime Environment (JRE), может запустить Aspose.Total for Java. Ниже перечислены большинство (но не все) поддерживаемых операционных систем. <br /><br />
- Майкрософт Виндоус
- Linux: Ubuntu, OpenSUSE, CentOS и другие
- macOS: 10.9 (Mavericks) и более поздние версии
- Мобильные устройства: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}
Преобразование **PDF в MHTML** (формат веб-архива) необходимо для преобразования документов в **HTML-страницы в одном файле с встроенными ресурсами**. Это обеспечивает простое распространение PDF-файлов в виде файлов, готовых для веба, для **архивирования, цифровой публикации и просмотра в браузере**.
{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}
- PDF в MHTML для веб-архивирования в одном файле
- Преобразование отчетов в **веб-архивы** для просмотра в браузере
- Потоки работ предприятия для **распространения документов на основе HTML**
- Хранение юридических и документов о соответствии в формате MHTML
- Цифровые рабочие процессы, преобразующие PDF в **готовые для веба форматы**
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}
- Автоматизированные **конвейеры PDF в MHTML**
- Пакетная обработка PDF в веб-архивы
- Интеграция корпоративной системы управления контентом для вывода в MHTML
- Автоматизированные рабочие процессы публикации с преобразованием PDF в MHTML
- Преобразование PDF в браузере в **самодостаточные HTML-архивы**
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}