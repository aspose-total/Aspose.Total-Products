---
title: Java를 통해 JSON 형식을 RTF으로 변환
description: Microsoft Word를 사용하지 않고 Java에서 JSON을 RTF으로 구문 분석
url_ignore: /ko/java/conversion/json-to-rtf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: RTF
otherformats: EPUB FLATOPC PCL WORDML DOTX PS DOCM RTF DOC WORD MOBI ODT DOT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 JSON 형식을 RTF으로 변환" h2="Microsoft<sup>&reg;</sup> Word를 사용하지 않고 JSON을 RTF으로 구문 분석하는 온프레미스 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 2단계 프로세스로 Java 애플리케이션에서 JSON을 RTF으로 변환할 수 있습니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 JSON을 PDF로 파싱할 수 있습니다. 두 번째 단계에서는 Word Processing API[Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 PDF를 RTF으로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 JSON 형식을 RTF으로 변환" %}}
1. 새 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 개체를 만들고 파일에서 유효한 JSON 데이터를 읽습니다.
2. [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) 클래스와 [Save](https://reference.aspose.com/)를 사용하여 JSON 파일을 워크시트로 가져옵니다. cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) PDF로
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 PDF 문서 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 문서를 RTF 형식으로 저장합니다.)) 방법
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
또한 API를 사용하면 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions)를 사용하여 JSON을 RTF으로 구문 분석하는 동안 JSON에 대한 레이아웃 옵션을 설정할 수 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="레이아웃 설정 및 Java를 통해 JSON 형식을 RTF으로 변환" %}}
API를 사용하여 워터마크를 사용하여 JSON을 RTF으로 구문 분석할 수도 있습니다. RTF 문서에 워터마크를 추가하려면 먼저 JSON 파일을 PDF로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 새로 생성된 PDF 파일을 로드하고 TextWatermarkOptions의 인스턴스를 생성하고 설정합니다. 해당 속성, Watermark.setText 메서드를 호출하고 TextWatermarkOptions의 워터마크 텍스트 및 개체를 전달합니다. 워터마크를 추가한 후 문서를 RTF에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}