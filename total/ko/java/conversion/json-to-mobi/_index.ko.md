---
title: Java를 통해 JSON 형식을 MOBI으로 변환
description: Microsoft Word를 사용하지 않고 Java에서 JSON을 MOBI으로 구문 분석
url_ignore: /ko/java/conversion/json-to-mobi/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: MOBI
otherformats: DOT PS ODT OTT WORDML EPUB MOBI DOC FLATOPC DOTX DOCM RTF WORD PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 JSON 형식을 MOBI으로 변환" h2="Microsoft<sup>&reg;</sup> Word를 사용하지 않고 JSON을 MOBI으로 구문 분석하는 온프레미스 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 2단계 프로세스로 Java 애플리케이션에서 JSON을 MOBI으로 변환할 수 있습니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 JSON을 PDF로 파싱할 수 있습니다. 두 번째 단계에서는 Word Processing API[Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 PDF를 MOBI으로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 JSON 형식을 MOBI으로 변환" %}}
1. 새 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 개체를 만들고 파일에서 유효한 JSON 데이터를 읽습니다.
2. [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) 클래스와 [Save](https://reference.aspose.com/)를 사용하여 JSON 파일을 워크시트로 가져옵니다. cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) PDF로
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 PDF 문서 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 문서를 MOBI 형식으로 저장합니다.)) 방법
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
또한 API를 사용하면 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions)를 사용하여 JSON을 MOBI으로 구문 분석하는 동안 JSON에 대한 레이아웃 옵션을 설정할 수 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="레이아웃 설정 및 Java를 통해 JSON 형식을 MOBI으로 변환" %}}
API를 사용하여 워터마크를 사용하여 JSON을 MOBI으로 구문 분석할 수도 있습니다. MOBI 문서에 워터마크를 추가하려면 먼저 JSON 파일을 PDF로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 새로 생성된 PDF 파일을 로드하고 TextWatermarkOptions의 인스턴스를 생성하고 설정합니다. 해당 속성, Watermark.setText 메서드를 호출하고 TextWatermarkOptions의 워터마크 텍스트 및 개체를 전달합니다. 워터마크를 추가한 후 문서를 MOBI에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
JSON을 MOBI로 변환하는 것은 구조화된 데이터에서 Kindle 호환 eBook을 생성하는 데 중요합니다. MOBI는 Amazon Kindle 장치에서 널리 사용되며, 이는 출판사, 교육기관 및 기업들에게 선호되는 형식입니다. JSON 데이터 세트를 MOBI로 변환함으로써 조직은 이동 가능하고 구조화되며 쉽게 배포 가능한 디지털 도서를 생산할 수 있으며, eReader 간 일관성을 유지합니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

- **디지털 출판** – 구조화된 콘텐츠를 Kindle용 eBook으로 변환합니다.
- **e러닝 콘텐츠** – 접근 가능한 MOBI 형식으로 강의 자료 제공합니다.
- **연구 결과 공유** – 학술 또는 기술적인 연구 결과를 Kindle 장치를 통해 공유합니다.
- **모바일 친화적 도서** – eReader 및 스마트폰 간 호환성을 보장합니다.
- **기업용 eBook 워크플로우** – Kindle 출판을 위해 비즈니스 보고서 및 문서를 표준화합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

- **JSON-to-MOBI 파이프라인** – 구조화된 데이터 세트로부터 eBook 생성을 자동화합니다.
- **자동화된 Kindle용 출판** – Amazon Kindle을 위한 eBook 배포를 간소화합니다.
- **동적 e러닝 콘텐츠 생성** – 실시간으로 대화식 강의 자료를 생성합니다.
- **JSON 기반 eBook 표준화** – 여러 제목 간 일관된 형식을 유지합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}