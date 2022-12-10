---
title: Java를 통해 Andorid의 WORD로 PPT 내보내기
description: 소프트웨어를 설치하지 않고 모바일 앱에서 PPT을 WORD로 변환

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOCX
otherformats: DOTX DOC DOTM ODT DOCM RTF DOCX OTT WORDML TEXT FLATOPC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Andorid에서 PPT을 WORD로 렌더링" h2="Microsoft PowerPoint 또는 Word에 의존하지 않고 Android 앱 내에서 PPT를 WORD로 변환하는 파일 형식 API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)을 사용하면 Android 애플리케이션 내에서 파일 형식을 조작할 수 있습니다. 패키지에 제공된 API를 사용하여 앱에서 PowerPoint PPT에서 Word WORD로의 변환 프로세스를 자동화할 수 있습니다.
주어진 문서를 두 단계로 변환할 수 있습니다. Android 애플리케이션용 PowerPoint API인 [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/)를 사용하여 PPT을 HTML로 렌더링할 수 있습니다. 그 후 문서 처리 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)를 사용하여 HTML을 WORD로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android에서 PPT에서 WORD로 렌더링" %}}
1. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPT 파일을 엽니다.
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)을 사용하여 PPT을 HTML로 변환합니다.ISaveOptions-) 메서드 및 Html을 SaveFormat으로 설정
3. [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument) 클래스를 이용하여 변환된 HTML 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,int)) 메소드를 사용하여 문서를 WORD 형식으로 저장하고 Word 설정 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Aspose.Slides for Android via Java](https://words.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) 및 [Java를 통한 Andorid용 Aspose.Words] 설치 (https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 응용 프로그램.

또는 [다운로드](https://releases.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordument
Wordument wordument = new Wordument("htmlOutput.html");
// save wordument in WORDX format
wordument.save("output.wordx",SaveFormat.Wordx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-dotx/" name="PPT 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-word/" name="PPT 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-dotm/" name="PPT 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-odt/" name="PPT 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-wordm/" name="PPT 에게 WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-rtf/" name="PPT 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-wordx/" name="PPT 에게 WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-ott/" name="PPT 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-wordml/" name="PPT 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-text/" name="PPT 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-flatopc/" name="PPT 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ppt-to-dot/" name="PPT 에게 DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}