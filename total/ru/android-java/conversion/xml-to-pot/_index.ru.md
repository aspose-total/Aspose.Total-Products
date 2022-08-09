---
title: Экспорт XML в POT в Android
description: Android API для преобразования XML в POT без использования Microsoft Word
url: /ru/android-java/conversion/xml-to-pot/
family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: POT
otherformats: PPTM PPS PPSX POTX PPSM POWERPOINT XAML SWF POTM PPT OTP ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование XML в POT на Android через Java" h2="Преобразуйте XML в POT в своих приложениях для Android, не используя Microsoft<sup>&reg;</sup> PowerPoint или Adobe<sup>&reg;</sup> Acrobat Reader." >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете интегрировать функцию преобразования XML в POT в свои приложения для Android, выполнив два простых шага. На первом этапе вы можете экспортировать XML в PPTX, используя [Aspose.PDF для Android через Java](https://products.aspose.com/pdf/android-java/). После этого, используя [Aspose.Slides для Android через Java](https://products.aspose.com/slides/android-java/), вы можете конвертировать PPTX в POT. Оба API входят в состав пакета [Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для экспорта XML в POT" %}}
1. Откройте файл XML, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте XML в PPTX, используя метод [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-).
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Сохраните документ в формате POT с помощью метода [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) и установите ` POT` как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF для Android через Java](https://docs.aspose.com/pdf/androidjava/installation/) и [Aspose.Slides для Android через Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Откройте защищенный паролем файл XML в Android через Java" %}}
При загрузке формата файла XML ваш документ может быть защищен паролем. [Aspose.PDF для Android через Java](https://products.aspose.com/pdf/android-java/) также позволяет открывать зашифрованные документы. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создайте миниатюру файла POT в приложениях для Android" %}}
После преобразования XML в POT вы также можете создавать эскизы выходного документа. Используя богатую функцию [Aspose.Slides для Android через Java](https://products.aspose.com/slides/android-java/), вы можете создавать эскизы слайдов, создавая экземпляр [Презентации]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). После этого вы можете получить ссылку на любой желаемый слайд, используя его идентификатор или индекс, и получить миниатюру изображения слайда, на который указывает ссылка, в указанном масштабе.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("output.pot");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-pptm/" name="XML К PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-pps/" name="XML К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-ppsx/" name="XML К PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-potx/" name="XML К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-ppsm/" name="XML К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-powerpoint/" name="XML К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-xaml/" name="XML К XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-swf/" name="XML К SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-potm/" name="XML К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-ppt/" name="XML К PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-otp/" name="XML К OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xml-to-pot/" name="XML К POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}