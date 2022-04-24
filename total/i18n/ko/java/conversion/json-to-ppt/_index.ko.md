---
title: Java를 통해 JSON 형식을 PPT로 변환
description: Microsoft PowerPoint를 사용하지 않고 Java에서 JSON을 PPT로 구문 분석
url: /ko/java/conversion/json-to-ppt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPT
otherformats: POTX PPS POWERPOINT PPTM PPT PPSM POT PPSX POTM OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 JSON 형식을 PPT로 변환" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 JSON 형식을 PPT로 구문 분석하는 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 두 가지 간단한 단계를 통해 모든 Java 애플리케이션 내에서 JSON 형식을 PPT로 변환할 수 있습니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 JSON을 PPTX로 파싱할 수 있습니다. 이후 [Aspose.Slides for Java](https://products.aspose.com/slides/java/)를 이용하여 PPTX를 PPT로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 JSON 형식을 PPT로 변환" %}}
1. 새 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 객체를 생성하고 JSON 파일을 엽니다.
2. [저장](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)을 사용하여 JSON을 PPTX로 저장합니다. ) 방법
3. [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPTX 문서를 로드합니다.
4. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 메소드를 사용하여 문서를 PPT 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://downloads.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
또한 API를 사용하면 지정된 레이아웃 옵션을 사용하여 JSON을 PPT로 구문 분석할 수 있습니다. 레이아웃 옵션을 지정하기 위해 [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 클래스를 사용할 수 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 레이아웃 설정 및 JSON 형식을 PPT로 변환" %}}
API를 사용하여 워터마크가 있는 JSON을 PPT로 변환할 수도 있습니다. PPT 문서에 워터마크를 추가하려면 먼저 JSON을 PPTX로 구문 분석하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 새로 생성된 PPTX 파일을 로드하고, 모든 슬라이드를 반복하고, 텍스트를 추가합니다. addTextFrame을 사용하여 color, fillType 등과 같은 모든 관련 옵션을 설정하고 문서를 PPT에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-pps/" name="JSON 에게 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-ppt/" name="JSON 에게 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-pptm/" name="JSON 에게 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-ppsm/" name="JSON 에게 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-powerpoint/" name="JSON 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-pot/" name="JSON 에게 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-potm/" name="JSON 에게 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-otp/" name="JSON 에게 OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-ppsx/" name="JSON 에게 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-potx/" name="JSON 에게 POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}