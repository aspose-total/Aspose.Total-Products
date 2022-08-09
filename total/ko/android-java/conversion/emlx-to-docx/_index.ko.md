---
title: Andorid 앱에서 EMLX을 DOCX로 렌더링
description: Andorid 응용 프로그램에서 Microsoft Word 또는 Outlook을 사용하지 않고 EMLX을 DOCX로 내보내기
url: /ko/android-java/conversion/emlx-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOCX
otherformats: EMF JPEG EPUB DOTX PCL PNG DOTM FLATOPC DOCM XPS OTT MD DOT RTF BMP GIF WORDML TIFF PS TEXT SVG PDF DOC ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid 앱에서 EMLX을 DOCX로 변환" h2="Java API를 통해 Andorid를 사용하여 EMLX을 DOCX로 내보내기 위한 Andorid 애플리케이션 설계" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid 앱은 일상적인 최종 사용자가 사용하기 쉽습니다. Andorid 휴대폰 사용자의 수는 나날이 증가하고 있습니다. 강력한 [Java를 통한 Android용 Aspose.Total](https://products.aspose.com/total/android-java/) 파일 형식 자동화 라이브러리를 사용하여 이메일 조작 및 변환 애플리케이션을 개발할 수 있습니다. [Android Java용 Aspose.Emlx](https://products.aspose.com/emlx/android-java/) 및 [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). 첫 번째 API를 사용하여 EMLX 파일 형식을 HTML로 변환할 수 있고 두 번째 API를 사용하여 HTML을 DOCX로 렌더링할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Andorid에서 EMLX을 DOCX로 변환" %}}
1. [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage) 클래스를 사용하여 EMLX 파일을 엽니다.
2. [저장](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)을 사용하여 EMLX을 HTML로 변환합니다. )) 방법
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 HTML 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions))을 사용하여 문서를 DOCX 형식으로 저장합니다. )) 메서드 및 DOCX를 SaveFormat으로 설정
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java를 통한 Android용 Aspose.Emlx](https://docs.aspose.com/emlx/androidjava/installation/) 및 [Java를 통한 Andorid용 Aspose.Words](https://docs.aspose.com/words) 설치 /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository).

또는 [다운로드](https://downloads.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOCX
document.save("output.docx", SaveFormat.DOCX); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-emf/" name="EMLX 에게 EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-jpeg/" name="EMLX 에게 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-epub/" name="EMLX 에게 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-dotx/" name="EMLX 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-pcl/" name="EMLX 에게 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-png/" name="EMLX 에게 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-dotm/" name="EMLX 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-flatopc/" name="EMLX 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-docm/" name="EMLX 에게 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-xps/" name="EMLX 에게 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-ott/" name="EMLX 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-md/" name="EMLX 에게 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-dot/" name="EMLX 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-rtf/" name="EMLX 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-docx/" name="EMLX 에게 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-gif/" name="EMLX 에게 GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-wordml/" name="EMLX 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-tiff/" name="EMLX 에게 TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-ps/" name="EMLX 에게 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-text/" name="EMLX 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-svg/" name="EMLX 에게 SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-pdf/" name="EMLX 에게 PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-doc/" name="EMLX 에게 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/emlx-to-odt/" name="EMLX 에게 ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}