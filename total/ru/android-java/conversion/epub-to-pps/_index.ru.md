---
title: Экспорт EPUB в PPS в Android
description: Android API для преобразования EPUB в PPS без использования Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PPS
otherformats: PPSM POTM ODP OTP XAML SWF POTX POT POWERPOINT PPTM PPT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование EPUB в PPS на Android через Java" h2="Преобразуйте EPUB в PPS в своих приложениях для Android, не используя Microsoft<sup>&reg;</sup> PowerPoint или Adobe<sup>&reg;</sup> Acrobat Reader." >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете интегрировать функцию преобразования EPUB в PPS в свои приложения для Android, выполнив два простых шага. На первом этапе вы можете экспортировать EPUB в PPTX, используя [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). После этого, используя [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), вы можете конвертировать PPTX в PPS. Оба API входят в состав пакета [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для экспорта EPUB в PPS" %}}
1. Откройте файл EPUB, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте EPUB в PPTX, используя метод [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-).
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Сохраните документ в формате PPS с помощью метода [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) и установите ` PPS` как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) и [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Откройте защищенный паролем файл EPUB в Android через Java" %}}
При загрузке формата файла EPUB ваш документ может быть защищен паролем. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) также позволяет открывать зашифрованные документы. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создайте миниатюру файла PPS в приложениях для Android" %}}
После преобразования EPUB в PPS вы также можете создавать эскизы выходного документа. Используя богатую функцию [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), вы можете создавать эскизы слайдов, создавая экземпляр [Презентации](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). После этого вы можете получить ссылку на любой желаемый слайд, используя его идентификатор или индекс, и получить миниатюру изображения слайда, на который указывает ссылка, в указанном масштабе.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("output.pps");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-ppsm/" name="EPUB К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-potm/" name="EPUB К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-pps/" name="EPUB К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-otp/" name="EPUB К OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-xaml/" name="EPUB К XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-swf/" name="EPUB К SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-potx/" name="EPUB К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-pot/" name="EPUB К POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-powerpoint/" name="EPUB К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-pptm/" name="EPUB К PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-ppt/" name="EPUB К PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/epub-to-ppsx/" name="EPUB К PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}