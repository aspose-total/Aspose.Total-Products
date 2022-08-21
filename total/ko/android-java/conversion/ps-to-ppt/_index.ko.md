---
title: Android에서 PS을 PPT로 내보내기
description: Microsoft Word를 사용하지 않고 PS을 PPT로 변환하는 Android API
url: /ko/android-java/conversion/ps-to-ppt/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: PPT
otherformats: PPTM POT PPS PPSM POTX SWF PPSX OTP ODP XAML POTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Android에서 PS을 PPT로 변환" h2="Microsoft<sup>&reg;</sup> PowerPoint 또는 Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 Android 애플리케이션 내에서 PS을 PPT로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 사용하여 Android 애플리케이션 내에서 PS에서 PPT로의 변환 기능을 통합할 수 있습니다. 첫 번째 단계에서는 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)를 사용하여 PS을 PPTX로 내보낼 수 있습니다. 이후 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)를 사용하여 PPTX를 PPT로 변환할 수 있습니다. 두 API 모두 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 패키지에 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS을 PPT로 내보내기 위한 Android API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 PS 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 메소드를 사용하여 PS을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPTX 문서를 로드합니다.
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 메소드를 사용하여 문서를 PPT 형식으로 저장하고 ` Ppt`를 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) 및 [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/)를 애플리케이션에 추가합니다.

또는 [다운로드](https://downloads.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
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

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android에서 암호로 보호된 PS 파일 열기" %}}
PS 파일 형식을 로드하는 동안 문서가 암호로 보호될 수 있습니다. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)를 사용하면 암호화된 문서도 열 수 있습니다. 암호화된 파일을 열기 위해 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java)의 새 인스턴스를 초기화할 수 있습니다. .lang.String-) 클래스를 생성하고 파일 이름과 비밀번호를 인수로 전달합니다.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Android 애플리케이션에서 PPT 파일의 썸네일 이미지 생성" %}}
PS을 PPT로 변환한 후 출력 문서의 축소판 이미지를 만들 수도 있습니다. 풍부한 기능의 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)를 사용하여 [프레젠테이션]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스. 그런 다음 ID 또는 인덱스를 사용하여 원하는 슬라이드의 참조를 얻을 수 있으며 참조된 슬라이드의 축소판 이미지를 지정된 축척으로 가져올 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("output.ppt");
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
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-pptm/" name="PS 에게 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-pot/" name="PS 에게 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-pps/" name="PS 에게 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-ppsm/" name="PS 에게 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-potx/" name="PS 에게 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-swf/" name="PS 에게 SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-ppsx/" name="PS 에게 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-otp/" name="PS 에게 OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-ppt/" name="PS 에게 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-xaml/" name="PS 에게 XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-potm/" name="PS 에게 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ps-to-powerpoint/" name="PS 에게 POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}