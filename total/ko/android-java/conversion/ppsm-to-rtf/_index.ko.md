---
title: Java를 통해 Andorid의 RTF로 PPSM 내보내기
description: 소프트웨어를 설치하지 않고 모바일 앱에서 PPSM을 RTF로 변환
url: /ko/android-java/conversion/ppsm-to-rtf/
family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: RTF
otherformats: DOCX DOCM WORDML DOTM OTT ODT DOTX DOC DOT TEXT FLATOPC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Andorid에서 PPSM을 RTF로 렌더링" h2="Microsoft PowerPoint 또는 Word에 의존하지 않고 Android 앱 내에서 PPSM를 RTF로 변환하는 파일 형식 API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)을 사용하면 Android 애플리케이션 내에서 파일 형식을 조작할 수 있습니다. 패키지에 제공된 API를 사용하여 앱에서 PowerPoint PPSM에서 Word RTF로의 변환 프로세스를 자동화할 수 있습니다.
주어진 문서를 두 단계로 변환할 수 있습니다. Android 애플리케이션용 PowerPoint API인 [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/)를 사용하여 PPSM을 HTML로 렌더링할 수 있습니다. 그 후 문서 처리 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)를 사용하여 HTML을 RTF로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android에서 PPSM에서 RTF로 렌더링" %}}
1. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPSM 파일을 엽니다.
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)을 사용하여 PPSM을 HTML로 변환합니다.ISaveOptions-) 메서드 및 Html을 SaveFormat으로 설정
3. [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument) 클래스를 이용하여 변환된 HTML 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) 메소드를 사용하여 문서를 RTF 형식으로 저장하고 Rtf 설정 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Aspose.Slides for Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) 및 [Java를 통한 Andorid용 Aspose.Words] 설치 (https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 응용 프로그램.

또는 [다운로드](https://downloads.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-rtfx/" name="PPSM 에게 RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-rtfm/" name="PPSM 에게 RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-wordml/" name="PPSM 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-dotm/" name="PPSM 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-ott/" name="PPSM 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-odt/" name="PPSM 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-dotx/" name="PPSM 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-rtf/" name="PPSM 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-dot/" name="PPSM 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-text/" name="PPSM 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-flatopc/" name="PPSM 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsm-to-word/" name="PPSM 에게 WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}