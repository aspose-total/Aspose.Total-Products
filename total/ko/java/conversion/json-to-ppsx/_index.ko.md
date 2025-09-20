---
title: Java를 통해 JSON 형식을 PPSX로 변환
description: Microsoft PowerPoint를 사용하지 않고 Java에서 JSON을 PPSX로 구문 분석
url_ignore: /ko/java/conversion/json-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSX
otherformats: PPT POTM PPTM PPS PPSX POT POWERPOINT OTP POTX PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 JSON 형식을 PPSX로 변환" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 JSON 형식을 PPSX로 구문 분석하는 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 두 가지 간단한 단계를 통해 모든 Java 애플리케이션 내에서 JSON 형식을 PPSX로 변환할 수 있습니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 JSON을 PPTX로 파싱할 수 있습니다. 이후 [Aspose.Slides for Java](https://products.aspose.com/slides/java/)를 이용하여 PPTX를 PPSX로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 JSON 형식을 PPSX로 변환" %}}
1. 새 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 객체를 생성하고 JSON 파일을 엽니다.
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)을 사용하여 JSON을 PPTX로 저장합니다. ) 방법
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPTX 문서를 로드합니다.
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 메소드를 사용하여 문서를 PPSX 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
또한 API를 사용하면 지정된 레이아웃 옵션을 사용하여 JSON을 PPSX로 구문 분석할 수 있습니다. 레이아웃 옵션을 지정하기 위해 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 클래스를 사용할 수 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 레이아웃 설정 및 JSON 형식을 PPSX로 변환" %}}
API를 사용하여 워터마크가 있는 JSON을 PPSX로 변환할 수도 있습니다. PPSX 문서에 워터마크를 추가하려면 먼저 JSON을 PPTX로 구문 분석하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 새로 생성된 PPTX 파일을 로드하고, 모든 슬라이드를 반복하고, 텍스트를 추가합니다. addTextFrame을 사용하여 color, fillType 등과 같은 모든 관련 옵션을 설정하고 문서를 PPSX에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**JSON을 PPSX로 변환**하는 것은 **구조화된 데이터에서 현대적인 PowerPoint 슬라이드 파일을 생성하는 데 필수적입니다**. PPSX 파일은 현대적인 PowerPoint 버전과 호환되는 전체 화면, 재생 준비가 된 슬라이드쇼를 제공하여 조직이 프레젠테이션 작성을 자동화하고 브랜딩 일관성을 유지하며 데이터 기반 콘텐츠를 효율적으로 전달할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

- **비즈니스 미팅** – 경영진 및 팀 프레젠테이션을 위한 표준화된 전문 슬라이드 생성.
- **교육 강의** – 구조화된 데이터 세트에서 직접 강의 데크 및 강의 자료 생성.
- **제품 데모** – 제품 및 서비스를 소개하기 위한 동적이고 준비된 프레젠테이션 슬라이드쇼 구축.
- **마케팅 캠페인** – 프로모션을 위한 브랜드화된 슬라이드쇼 프레젠테이션 자동화.
- **연구 데이터 프레젠테이션** – 구조화된 연구 데이터를 시각적으로 매력적인 슬라이드로 변환.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

- **JSON-to-PPSX 파이프라인** – 구조화된 데이터를 현대적인 슬라이드 파일로 변환하는 프로세스 간소화.
- **자동화된 슬라이드쇼 생성** – 수동 슬라이드 디자인 및 서식 작업 감소.
- **기업 수준의 보고서 데크** – 부서 전체에 걸쳐 표준화된 프레젠테이션 데크 생성.
- **JSON 기반 브랜드 슬라이드쇼** – 데이터 삽입 및 자동 슬라이드에서 기업 브랜딩 유지.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}