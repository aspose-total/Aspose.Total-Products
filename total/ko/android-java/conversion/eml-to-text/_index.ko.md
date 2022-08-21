---
title: Andorid 앱에서 EML을 TEXT로 렌더링
description: Andorid 응용 프로그램에서 Microsoft Word 또는 Outlook을 사용하지 않고 EML을 TEXT로 내보내기
url: /ko/android-java/conversion/eml-to-text/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: TEXT
otherformats: RTF EMF PCL EPUB JPEG ODT XPS DOTX DOCX OTT MD DOT GIF FLATOPC SVG DOTM BMP TIFF PDF DOCM PNG WORDML PS DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid 앱에서 EML을 TEXT로 변환" h2="Java API를 통해 Andorid를 사용하여 EML을 TEXT로 내보내기 위한 Andorid 애플리케이션 설계" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid 앱은 일상적인 최종 사용자가 사용하기 쉽습니다. Andorid 휴대폰 사용자의 수는 나날이 증가하고 있습니다. 강력한 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 파일 형식 자동화 라이브러리를 사용하여 이메일 조작 및 변환 애플리케이션을 개발할 수 있습니다. [Android Java용 Aspose.Eml](https://products.aspose.com/eml/android-java/) 및 [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). 첫 번째 API를 사용하여 EML 파일 형식을 HTML로 변환할 수 있고 두 번째 API를 사용하여 HTML을 TEXT로 렌더링할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Andorid에서 EML을 TEXT로 변환" %}}
1. [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) 클래스를 사용하여 EML 파일을 엽니다.
2. [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)을 사용하여 EML을 HTML로 변환합니다. )) 방법
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 HTML 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions))을 사용하여 문서를 TEXT 형식으로 저장합니다. )) 메서드 및 TEXT를 SaveFormat으로 설정
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java를 통한 Android용 Aspose.Eml](https://docs.aspose.com/eml/androidjava/installation/) 및 [Java를 통한 Andorid용 Aspose.Words](https://docs.aspose.com/words) 설치

또는 [다운로드](https://downloads.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TEXT
document.save("output.text", SaveFormat.TEXT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-rtf/" name="EML 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-emf/" name="EML 에게 EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-pcl/" name="EML 에게 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-epub/" name="EML 에게 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-jpeg/" name="EML 에게 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-odt/" name="EML 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-xps/" name="EML 에게 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-dotx/" name="EML 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-docx/" name="EML 에게 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-ott/" name="EML 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-md/" name="EML 에게 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-dot/" name="EML 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-gif/" name="EML 에게 GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-flatopc/" name="EML 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-svg/" name="EML 에게 SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-dotm/" name="EML 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-text/" name="EML 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-tiff/" name="EML 에게 TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-pdf/" name="EML 에게 PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-docm/" name="EML 에게 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-png/" name="EML 에게 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-wordml/" name="EML 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-ps/" name="EML 에게 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/eml-to-doc/" name="EML 에게 DOC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}