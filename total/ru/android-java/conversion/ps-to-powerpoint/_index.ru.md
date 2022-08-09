---
title: Экспорт PS в POWERPOINT в Android
description: Android API для преобразования PS в POWERPOINT без использования Microsoft Word
url: /ru/android-java/conversion/ps-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: PPT
otherformats: POTX PPS PPTM POTM SWF ODP PPSM XAML OTP POT PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование PS в POWERPOINT на Android через Java" h2="Преобразуйте PS в POWERPOINT в своих приложениях для Android, не используя Microsoft<sup>&reg;</sup> PowerPoint или Adobe<sup>&reg;</sup> Acrobat Reader." >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете интегрировать функцию преобразования PS в POWERPOINT в свои приложения для Android, выполнив два простых шага. На первом этапе вы можете экспортировать PS в PPTX, используя [Aspose.PDF для Android через Java](https://products.aspose.com/pdf/android-java/). После этого, используя [Aspose.Slides для Android через Java](https://products.aspose.com/slides/android-java/), вы можете конвертировать PPTX в POWERPOINT. Оба API входят в состав пакета [Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для экспорта PS в POWERPOINT" %}}
1. Откройте файл PS, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте PS в PPTX, используя метод [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-).
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Сохраните документ в формате POWERPOINT с помощью метода [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) и установите ` POWERPOINT` как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF для Android через Java](https://docs.aspose.com/pdf/androidjava/installation/) и [Aspose.Slides для Android через Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Откройте защищенный паролем файл PS в Android через Java" %}}
При загрузке формата файла PS ваш документ может быть защищен паролем. [Aspose.PDF для Android через Java](https://products.aspose.com/pdf/android-java/) также позволяет открывать зашифрованные документы. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создайте миниатюру файла POWERPOINT в приложениях для Android" %}}
После преобразования PS в POWERPOINT вы также можете создавать эскизы выходного документа. Используя богатую функцию [Aspose.Slides для Android через Java](https://products.aspose.com/slides/android-java/), вы можете создавать эскизы слайдов, создавая экземпляр [Презентации]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). После этого вы можете получить ссылку на любой желаемый слайд, используя его идентификатор или индекс, и получить миниатюру изображения слайда, на который указывает ссылка, в указанном масштабе.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("output.powerpoint");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-potx/" name="PS К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-pps/" name="PS К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-pptm/" name="PS К PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-potm/" name="PS К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-swf/" name="PS К SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-powerpoint/" name="PS К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-ppsm/" name="PS К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-xaml/" name="PS К XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-otp/" name="PS К OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-pot/" name="PS К POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-ppsx/" name="PS К PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-ppt/" name="PS К PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}