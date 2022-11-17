---
title: Экспорт PCL в OTP в Android
description: Android API для преобразования PCL в OTP без использования Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: OTP
otherformats: PPT POTX POTM POT ODP PPS XAML POWERPOINT SWF PPSM PPSX PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование PCL в OTP на Android через Java" h2="Преобразуйте PCL в OTP в своих приложениях для Android, не используя Microsoft<sup>&reg;</sup> PowerPoint или Adobe<sup>&reg;</sup> Acrobat Reader." >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете интегрировать функцию преобразования PCL в OTP в свои приложения для Android, выполнив два простых шага. На первом этапе вы можете экспортировать PCL в PPTX, используя [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). После этого, используя [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), вы можете конвертировать PPTX в OTP. Оба API входят в состав пакета [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для экспорта PCL в OTP" %}}
1. Откройте файл PCL, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте PCL в PPTX, используя метод [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-).
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Сохраните документ в формате OTP с помощью метода [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) и установите ` OTP` как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) и [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Откройте защищенный паролем файл PCL в Android через Java" %}}
При загрузке формата файла PCL ваш документ может быть защищен паролем. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) также позволяет открывать зашифрованные документы. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PCL document
Document doc = new Document("input.pcl", "Your@Password");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создайте миниатюру файла OTP в приложениях для Android" %}}
После преобразования PCL в OTP вы также можете создавать эскизы выходного документа. Используя богатую функцию [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), вы можете создавать эскизы слайдов, создавая экземпляр [Презентации](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). После этого вы можете получить ссылку на любой желаемый слайд, используя его идентификатор или индекс, и получить миниатюру изображения слайда, на который указывает ссылка, в указанном масштабе.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a OTP file
Presentation presentation = new Presentation("output.otp");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-ppt/" name="PCL К PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-potx/" name="PCL К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-potm/" name="PCL К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-pot/" name="PCL К POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-otp/" name="PCL К OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-pps/" name="PCL К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-xaml/" name="PCL К XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-powerpoint/" name="PCL К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-swf/" name="PCL К SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-ppsm/" name="PCL К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-ppsx/" name="PCL К PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pcl-to-pptm/" name="PCL К PPTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}