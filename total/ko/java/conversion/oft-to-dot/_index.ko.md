---
title: Java를 통해 OFT을 DOT로 내보내기
description: Microsoft Word 또는 Outlook을 사용하지 않고 OFT을 DOT로 변환하는 Java API
url_ignore: /ko/java/conversion/oft-to-dot/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: DOT
otherformats: DOTM PDF RTF PS FLATOPC DOCX XPS DOTX JPEG EMF OTT SVG TEXT DOT MD PCL WORDML TIFF PNG GIF EPUB ODT DOCM DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFT을 DOT로 렌더링하는 Java API" h2="타사 종속성을 사용하지 않고 사내 Java API를 사용하여 OFT을 DOT로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
이메일 변환은 Java 개발자가 [Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 모든 Java J2SE, J2EE, J2ME 애플리케이션에 통합할 수 있는 강력한 기능입니다. 패키지 내에서 두 개의 API를 사용하여 타사 종속성 없이 이메일 OFT을 DOT로 변환할 수 있습니다. 먼저 이메일 조작 API[Aspose.Oft for Java](https://products.aspose.com/oft/java/)를 사용하여 OFT 파일 형식을 HTML로 변환할 수 있습니다. 둘째, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 HTML을 DOT로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="이메일을 DOT로 변환하는 방법" %}}
1. [MailMessage](https://apireference.aspose.com/oft/java/com.aspose.oft/mailmessage) 클래스를 사용하여 OFT 파일을 엽니다.
2. [저장](https://apireference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions)을 사용하여 OFT을 HTML로 변환합니다.)) 방법
3. [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 HTML 로드
4. [저장](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 문서를 DOT 형식으로 저장합니다.)) 메서드 및 DOT를 SaveFormat으로 설정
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 기반 프로젝트에서 직접 Java용 Aspose.Total을 사용해야 합니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://downloads.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOT
document.save("output.dot", SaveFormat.DOT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-png/" name="MSG 에게 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-doc/" name="MSG 에게 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-ott/" name="MSG 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-odt/" name="MSG 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-wordml/" name="MSG 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-dotx/" name="MSG 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-svg/" name="MSG 에게 SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-docx/" name="MSG 에게 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-epub/" name="MSG 에게 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-text/" name="MSG 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-xps/" name="MSG 에게 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-ps/" name="MSG 에게 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-flatopc/" name="MSG 에게 FLA에게PC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-docm/" name="MSG 에게 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-jpeg/" name="MSG 에게 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-tiff/" name="MSG 에게 TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-dot/" name="MSG 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-emf/" name="MSG 에게 EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-rtf/" name="MSG 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-gif/" name="MSG 에게 GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-pcl/" name="MSG 에게 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-dotm/" name="MSG 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-md/" name="MSG 에게 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/msg-to-pdf/" name="MSG 에게 PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}