---
title: Преобразование XML в POTM через Java API
description: Java API для преобразования XML в POTM без использования Microsoft Word
url: /ru/java/conversion/xml-to-potm/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: POTM
otherformats: POTM XAML POWERPOINT POTX OTP PPSX PPTM PPT PPSM PPS SWF POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для экспорта XML в POTM" h2="Экспорт XML в POTM через локальный Java API без использования Microsoft<sup>&reg;</sup> PowerPoint или Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете легко преобразовать XML в POTM в любом приложении Java J2SE, J2EE, J2ME. Во-первых, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/), вы можете экспортировать XML в PPTX. После этого, используя [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API обработки PowerPoint, вы можете конвертировать PPTX в POTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования XML в POTM" %}}
1. Откройте файл XML, используя класс [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте XML в PPTX, используя метод [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-).
3. Загрузите документ PPTX с помощью класса [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Сохраните документ в формате POTM с помощью метода [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) и установите ` POTM` как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Slides для Java](https://docs.aspose.com/slides/java/ установка/) в вашем pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}](
При загрузке формата файла XML ваш документ может быть защищен паролем. [Aspose.PDF для Java](https://products.aspose.com/pdf/java/) также позволяет открывать зашифрованные документы. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Открыть зашифрованный файл XML через Java" %}}
После преобразования XML в POTM вы также можете добавить предопределенный тип представления для своей презентации. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) предоставляет возможность установить тип представления для сгенерированной презентации, когда она открывается в PowerPoint через [ViewProperties](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Свойство [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) используется для установки типа представления с помощью [ViewType](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-pps/" name="XML К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-swf/" name="XML К SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-potx/" name="XML К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-ppsx/" name="XML К PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-potm/" name="XML К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-ppt/" name="XML К PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-ppsm/" name="XML К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-xaml/" name="XML К XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-otp/" name="XML К OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-pptm/" name="XML К PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-pot/" name="XML К POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xml-to-powerpoint/" name="XML К POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}