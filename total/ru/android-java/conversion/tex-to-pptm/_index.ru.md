---
title: Экспорт TEX в PPTM в Android
description: Android API для преобразования TEX в PPTM без использования Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: PPTM
otherformats: POWERPOINT OTP XAML PPS SWF POTX ODP POT POTM PPT PPSM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование TEX в PPTM на Android через Java" h2="Преобразуйте TEX в PPTM в своих приложениях для Android, не используя Microsoft<sup>&reg;</sup> PowerPoint или Adobe<sup>&reg;</sup> Acrobat Reader." >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете интегрировать функцию преобразования TEX в PPTM в свои приложения для Android, выполнив два простых шага. На первом этапе вы можете экспортировать TEX в PPTX, используя [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). После этого, используя [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), вы можете конвертировать PPTX в PPTM. Оба API входят в состав пакета [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для экспорта TEX в PPTM" %}}
1. Откройте файл TEX, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте TEX в PPTX, используя метод [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-).
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Сохраните документ в формате PPTM с помощью метода [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) и установите ` PPTM` как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) и [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Откройте защищенный паролем файл TEX в Android через Java" %}}
При загрузке формата файла TEX ваш документ может быть защищен паролем. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) также позволяет открывать зашифрованные документы. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.
{{% blocks/products/pf/feature-page-code %}}

```java
// open TEX document
Document doc = new Document("input.tex", "Your@Password");
// save TEX as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создайте миниатюру файла PPTM в приложениях для Android" %}}
После преобразования TEX в PPTM вы также можете создавать эскизы выходного документа. Используя богатую функцию [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), вы можете создавать эскизы слайдов, создавая экземпляр [Презентации](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). После этого вы можете получить ссылку на любой желаемый слайд, используя его идентификатор или индекс, и получить миниатюру изображения слайда, на который указывает ссылка, в указанном масштабе.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("output.pptm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-powerpoint/" name="TEX К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-otp/" name="TEX К OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-xaml/" name="TEX К XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-pps/" name="TEX К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-swf/" name="TEX К SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-potx/" name="TEX К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-pptm/" name="TEX К PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-pot/" name="TEX К POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-potm/" name="TEX К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-ppt/" name="TEX К PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-ppsm/" name="TEX К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/tex-to-ppsx/" name="TEX К PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}