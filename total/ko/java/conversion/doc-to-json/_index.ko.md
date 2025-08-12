---
title: Java를 통해 DOC를 JSON 형식으로 변환
description: Microsoft Word 또는 Microsoft Excel을 사용하지 않고 Java를 통해 DOC를 JSON 형식으로 변환
url_ignore: /ko/java/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 DOC를 JSON 형식으로 변환" h2="Microsoft<sup>&reg;</sup> Word 또는 Microsoft<sup>&reg;</sup> Excel을 사용하지 않고 DOC를 JSON으로 변환하는 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 DOC를 JSON 형식으로 변환하는 것은 간단한 2단계 프로세스입니다. 기능이 풍부한 문서 조작 및 변환 API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 DOC를 HTML로 내보낼 수 있습니다. 그 후 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 HTML을 JSON으로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 DOC를 JSON 형식으로 변환" %}}
1. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOC 파일을 엽니다.
2. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 DOC를 HTML로 변환합니다. ) 방법
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 HTML 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 JSON 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
API를 사용하여 암호로 보호된 문서를 열 수도 있습니다. 입력 DOC 문서가 비밀번호로 보호되어 있는 경우 비밀번호를 사용하지 않고는 JSON 형식으로 변환할 수 없습니다. API를 사용하면 LoadOptions 개체에 올바른 암호를 전달하여 암호화된 문서를 열 수 있습니다. 다음 코드 예제에서는 암호로 암호화된 문서를 여는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 보호된 DOC를 JSON 형식으로 변환" %}}
DOC를 JSON으로 변환하는 동안 범위를 출력 JSON 형식으로 설정할 수도 있습니다. 범위를 설정하려면 변환된 HTML을 Workbook 클래스를 사용하여 열고, Cells.createRange 메서드를 사용하여 내보낼 데이터 범위를 만들고, Range & ExportRangeToJsonOptions를 참조하여 JsonUtility.exportRangeToJson 메서드를 호출하고, 문자열 JSON 데이터를 파일에 씁니다. BufferedWriter.write 메서드. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Converting **DOC** to **JSON (JavaScript Object Notation)**은 워드 문서 데이터를 웹 서비스 및 애플리케이션에서 쉽게 사용할 수 있도록 하는 데 중요합니다. JSON은 현대적인 API, 웹 앱 및 NoSQL 데이터베이스를 지원하는 가벼운 구조화된 형식을 제공합니다.

## ✅ 주요 사용 사례
- 응용 프로그램 사용을 위한 워드에서 구조화된 데이터 추출
- 문서 내용을 웹 API에 통합
- 문서에서 파생된 데이터에 대한 검색 및 필터링 가능하게 함
- 구조화된 워드 데이터를 NoSQL 데이터베이스에 저장

## ⚙️ 자동화 시나리오
- 직접 데이터 변환을 위한 DOC-to-JSON 추출기
- 개발자를 위한 Java 기반 JSON 생성 스크립트
- 자동화된 워드에서 API로의 통합 워크플로우
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}