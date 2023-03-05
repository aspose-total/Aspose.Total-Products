---
title: Java를 통해 Andorid의 RTF로 PPSX 내보내기 또는 무료 온라인 변환기 사용
description: 소프트웨어를 설치하지 않고 모바일 앱에서 PPSX을 RTF로 변환 또는 온라인. 코드를 통합하기 전에 무료 CSV to DOC 온라인 변환기를 빠르게 테스트하십시오.

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: RTF
otherformats: DOT DOTM DOTX DOCX TEXT FLATOPC ODT WORD WORDML DOCM DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Andorid에서 PPSX을 RTF로 렌더링 또는 온라인 앱" h2="Microsoft PowerPoint 또는 Word에 의존하지 않고 Android 앱 내에서 PPSX를 RTF로 변환하는 파일 형식 API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)을 사용하면 Android 애플리케이션 내에서 파일 형식을 조작할 수 있습니다. 패키지에 제공된 API를 사용하여 앱에서 PowerPoint PPSX에서 Word RTF로의 변환 프로세스를 자동화할 수 있습니다.
주어진 문서를 두 단계로 변환할 수 있습니다. Android 애플리케이션용 PowerPoint API인 [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/)를 사용하여 PPSX을 HTML로 렌더링할 수 있습니다. 그 후 문서 처리 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)를 사용하여 HTML을 RTF로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android에서 PPSX에서 RTF로 렌더링" %}}
1. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPSX 파일을 엽니다.
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)을 사용하여 PPSX을 HTML로 변환합니다.ISaveOptions-) 메서드 및 Html을 SaveFormat으로 설정
3. [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument) 클래스를 이용하여 변환된 HTML 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) 메소드를 사용하여 문서를 RTF 형식으로 저장하고 Rtf 설정 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Aspose.Slides for Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) 및 [Java를 통한 Andorid용 Aspose.Words] 설치 (https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 응용 프로그램.

또는 [다운로드](https://releases.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>PPSX를 RTF로 변환하는 무료 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=rtf&from=ppsx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-dot/" name="PPSX 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-dotm/" name="PPSX 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-dotx/" name="PPSX 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-rtfx/" name="PPSX 에게 RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-text/" name="PPSX 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-flatopc/" name="PPSX 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-odt/" name="PPSX 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-word/" name="PPSX 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-wordml/" name="PPSX 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-rtfm/" name="PPSX 에게 RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-rtf/" name="PPSX 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppsx-to-ott/" name="PPSX 에게 OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}