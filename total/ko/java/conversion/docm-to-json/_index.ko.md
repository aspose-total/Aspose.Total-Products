---
title: Java를 통해 DOCM를 JSON 형식으로 변환
description: Microsoft Word 또는 Microsoft Excel을 사용하지 않고 Java를 통해 DOCM를 JSON 형식으로 변환
url_ignore: /ko/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 DOCM를 JSON 형식으로 변환" h2="Microsoft<sup>&reg;</sup> Word 또는 Microsoft<sup>&reg;</sup> Excel을 사용하지 않고 DOCM를 JSON으로 변환하는 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 DOCM를 JSON 형식으로 변환하는 것은 간단한 2단계 프로세스입니다. 기능이 풍부한 문서 조작 및 변환 API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 DOCM를 HTML로 내보낼 수 있습니다. 그 후 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 HTML을 JSON으로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 DOCM를 JSON 형식으로 변환" %}}
1. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOCM 파일을 엽니다.
2. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 DOCM를 HTML로 변환합니다. ) 방법
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
API를 사용하여 암호로 보호된 문서를 열 수도 있습니다. 입력 DOCM 문서가 비밀번호로 보호되어 있는 경우 비밀번호를 사용하지 않고는 JSON 형식으로 변환할 수 없습니다. API를 사용하면 LoadOptions 개체에 올바른 암호를 전달하여 암호화된 문서를 열 수 있습니다. 다음 코드 예제에서는 암호로 암호화된 문서를 여는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 보호된 DOCM를 JSON 형식으로 변환" %}}
DOCM를 JSON으로 변환하는 동안 범위를 출력 JSON 형식으로 설정할 수도 있습니다. 범위를 설정하려면 변환된 HTML을 Workbook 클래스를 사용하여 열고, Cells.createRange 메서드를 사용하여 내보낼 데이터 범위를 만들고, Range & ExportRangeToJsonOptions를 참조하여 JsonUtility.exportRangeToJson 메서드를 호출하고, 문자열 JSON 데이터를 파일에 씁니다. BufferedWriter.write 메서드. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
변환 **DOCM (Word Macro-Enabled Documents)**을 **JSON (JavaScript Object Notation)**으로 변환하는 것은 정적 문서 콘텐츠, 테이블 및 양식 필드를 **구조화된, 기계 판독 가능한 데이터**로 변환하는 데 중요합니다. JSON은 가벼우며 사람이 읽기 쉽고 **API, 분석, 웹 앱 및 자동화 워크플로우**에서 널리 사용됩니다. DOCM에서 데이터를 추출하여 JSON으로 변환함으로써 조직은 현대 플랫폼 간의 상호 운용성을 활성화하고 더 빠른 통합을 가능하게 하며 데이터가 **실시간 처리, 유효성 검사 및 확장 가능한 배포**에 준비되도록 할 수 있습니다.

## ✅ 주요 사용 사례

- **REST/GraphQL API에 문서 데이터 게시**
  웹 및 모바일 앱에서 직접 API 사용을 위해 추출된 DOCM 콘텐츠를 JSON으로 제공합니다.

- **NoSQL 데이터베이스 및 데이터 레이크에 데이터 공급**
  MongoDB, Elasticsearch 또는 클라우드 기반 데이터 레이크에 유래된 DOCM 구조화된 데이터를 로드합니다.

- **실시간 JSON 피드로 대시보드 제공**
  문서 기반 KPI 및 메트릭을 BI 대시보드 및 모니터링 도구로 스트리밍합니다.

- **JSON 스키마에 대한 입력 유효성 검사**
  DOCM 필드 데이터를 JSON 스키마 규칙과 일치시켜 일관성과 무결성을 보장합니다.

- **헤드리스 CMS 또는 마이크로서비스 아키텍처 활성화**
  JSON이 공용어인 분산형 API 우선 시스템에 DOCM 콘텐츠를 통합합니다.

## ⚙️ 자동화 시나리오

- **필드 매핑을 사용한 DOCM-to-JSON 추출**
  테이블, 헤더 및 필드를 구조화된 JSON 객체로 변환하기 위한 매핑 정의

- **JSON 이벤트를 변환하고 발생시키는 서버리스 함수**
  파일 업로드 시 변환을 트리거하여 JSON 페이로드를 이벤트 기반 시스템에 전송

- **유형 및 키를 표준화하는 ETL 작업**
  하류 분석을 위해 DOCM 내보내기를 일관된 JSON 구조로 표준화

- **JSON을 하류 시스템으로 푸시하는 웹훅**
  CRM, ERP 도구 또는 타사 앱에 공급되는 DOCM-to-JSON 내보내기를 자동화

- **JSON 내보내기 전에 매크로 및 PII를 제거하는 규정 규칙**
  매크로가 활성화된 파일에서 안전하고 살균된 JSON 출력을 보장하기 위해 규정 검사 적용
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}