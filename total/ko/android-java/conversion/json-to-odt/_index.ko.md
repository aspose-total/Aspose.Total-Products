---
title: Java를 통해 Android에서 JSON 형식을 ODT으로 변환
description: Microsoft Word를 사용하지 않고 Java에서 JSON을 ODT으로 구문 분석

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: ODT
otherformats: EPUB PCL WORD FLATOPC OTT MOBI RTF PS DOC DOT DOTX CHM DOCM WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android 애플리케이션에서 JSON 형식을 ODT으로 변환" h2="Microsoft<sup>&reg;</sup> Word를 사용하지 않고 Android 애플리케이션 내에서 JSON을 ODT으로 구문 분석" >}}

{{% blocks/products/pf/feature-page-summary %}}
2단계 프로세스로 Android 애플리케이션에서 JSON을 ODT으로 변환할 수 있습니다. 첫째, 강력한 스프레드시트 처리 API[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)를 사용하여 JSON을 PDF로 구문 분석할 수 있습니다. 두 번째 단계에서는 Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)를 사용하여 PDF를 ODT으로 변환할 수 있습니다. 두 API 모두 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 제품군에 속합니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 Android에서 JSON 형식을 ODT으로 변환" %}}
1. 새 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 개체를 만들고 파일에서 유효한 JSON 데이터를 읽습니다.
2. [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) 클래스와 [Save](https://reference.aspose.com/)를 사용하여 JSON 파일을 워크시트로 가져옵니다. PDF로
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 PDF 문서 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions))을 사용하여 문서를 ODT 형식으로 저장합니다. )) 방법
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. 앱에 라이브러리를 설치합니다.

또는 [다운로드](https://releases.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android에서 레이아웃 설정 및 JSON 형식을 ODT으로 변환" %}}
또한 API를 사용하면 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions)를 사용하여 JSON을 ODT으로 구문 분석하는 동안 JSON 형식에 대한 레이아웃 옵션을 설정할 수 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 조각은 레이아웃 옵션을 설정하는 방법을 보여줍니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android에서 워터마크를 사용하여 JSON 형식을 ODT으로 변환" %}}
API를 사용하여 워터마크가 있는 JSON을 ODT으로 변환할 수도 있습니다. ODT 문서에 워터마크를 추가하려면 먼저 JSON 파일을 PDF로 구문 분석하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 새로 생성된 PDF 파일을 로드하고 TextWatermarkOptions의 인스턴스를 생성하고 설정합니다. 해당 속성, Watermark.setText 메서드를 호출하고 TextWatermarkOptions의 워터마크 텍스트 및 개체를 전달합니다. 워터마크를 추가한 후 문서를 ODT에 저장할 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-epub/" name="JSON 에게 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-pcl/" name="JSON 에게 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-word/" name="JSON 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-flatopc/" name="JSON 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-ott/" name="JSON 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-mobi/" name="JSON 에게 MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-rtf/" name="JSON 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-ps/" name="JSON 에게 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-doc/" name="JSON 에게 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-dot/" name="JSON 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-dotx/" name="JSON 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-odt/" name="JSON 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-docm/" name="JSON 에게 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/json-to-wordml/" name="JSON 에게 WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}