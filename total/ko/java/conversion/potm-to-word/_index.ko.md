---
title: Java를 통해 POTM을 WORD로 변환
description: Microsoft Word 또는 PowerPoint를 사용하지 않고 POTM을 WORD로 내보내는 Java API
url_ignore: /ko/java/conversion/potm-to-word/
family: total
platformtag: net
feature: conversion
informat: POTMM
outformat: WORDX
otherformats: WORDX ODT DOTX DOT WORDM RTF DOTM TEXT WORD FLATOPC OTT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 POTM을 WORD로 변환" h2="모든 Java J2SE, J2EE, J2ME 애플리케이션 내에서 PowerPoint POTM에서 WORD로의 변환을 위한 온프레미스 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) 파일 형식 자동화 라이브러리를 통해 Java 개발자는 PowerPoint POTM을 Word WORD로 일괄 변환 프로세스를 자동화할 수 있습니다. 문서 변환은 2단계 프로세스이며 두 가지 API를 사용합니다. POTM을 HTML로 변환하는 프레젠테이션 조작 및 관리용 PowerPoint API인 [Aspose.Slides for Java](https://products.aspose.com/slides/java/)를 사용하겠습니다. 그 후 기능이 풍부한 Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 HTML을 WORD로 변환합니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 POTM을 WORD로 변환하는 방법" %}}
1. [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 POTM 파일을 엽니다.
2. [저장](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)을 사용하여 POTM을 HTML로 변환합니다. ISaveOptions-) 메서드 및 Html을 SaveFormat으로 설정
3. [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 변환된 HTML 파일을 로드합니다.
4. [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 메서드를 사용하여 문서를 WORD 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
POTM에서 WORD 파일 변환을 위해 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. /aspose-total) 기반 프로젝트를 만들고 pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://downloads.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
API를 사용하여 워터마크를 사용하여 POTM 파일을 WORD로 변환할 수도 있습니다. WORD 문서에 워터마크를 추가하려면 먼저 POTM 파일을 HTML로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 새로 생성된 HTML 파일을 로드하고 TextWatermarkOptions의 인스턴스를 생성하고 설정합니다. 해당 속성, Watermark.setText 메서드를 호출하고 TextWatermarkOptions의 워터마크 텍스트 및 개체를 전달합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-word/" name="POTM 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-dotx/" name="POTM 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-odt/" name="POTM 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-ott/" name="POTM 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-rtf/" name="POTM 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-flatopc/" name="POTM 에게 FLA에게PC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-wordml/" name="POTM 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-wordm/" name="POTM 에게 WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-text/" name="POTM 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-wordx/" name="POTM 에게 WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-dotm/" name="POTM 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/potm-to-dot/" name="POTM 에게 DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}