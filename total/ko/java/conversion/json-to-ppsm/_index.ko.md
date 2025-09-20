---
title: Java를 통해 JSON 형식을 PPSM로 변환
description: Microsoft PowerPoint를 사용하지 않고 Java에서 JSON을 PPSM로 구문 분석
url_ignore: /ko/java/conversion/json-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSM
otherformats: PPS POT POWERPOINT PPSM PPTM POTM PPSX OTP POTX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 JSON 형식을 PPSM로 변환" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 JSON 형식을 PPSM로 구문 분석하는 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 두 가지 간단한 단계를 통해 모든 Java 애플리케이션 내에서 JSON 형식을 PPSM로 변환할 수 있습니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 JSON을 PPTX로 파싱할 수 있습니다. 이후 [Aspose.Slides for Java](https://products.aspose.com/slides/java/)를 이용하여 PPTX를 PPSM로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 JSON 형식을 PPSM로 변환" %}}
1. 새 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 객체를 생성하고 JSON 파일을 엽니다.
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)을 사용하여 JSON을 PPTX로 저장합니다. ) 방법
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPTX 문서를 로드합니다.
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 메소드를 사용하여 문서를 PPSM 형식으로 저장합니다.
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
또한 API를 사용하면 지정된 레이아웃 옵션을 사용하여 JSON을 PPSM로 구문 분석할 수 있습니다. 레이아웃 옵션을 지정하기 위해 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 클래스를 사용할 수 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 레이아웃 설정 및 JSON 형식을 PPSM로 변환" %}}
API를 사용하여 워터마크가 있는 JSON을 PPSM로 변환할 수도 있습니다. PPSM 문서에 워터마크를 추가하려면 먼저 JSON을 PPTX로 구문 분석하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 새로 생성된 PPTX 파일을 로드하고, 모든 슬라이드를 반복하고, 텍스트를 추가합니다. addTextFrame을 사용하여 color, fillType 등과 같은 모든 관련 옵션을 설정하고 문서를 PPSM에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**JSON을 PPSM으로 변환**하는 것은 **구조화된 데이터로부터 매크로가 활성화된 PowerPoint 슬라이드쇼 파일을 생성하는 데 필수적**입니다. PPSM 파일은 포함된 매크로를 지원하여 자동 상호 작용, 동적 콘텐츠 및 고급 프레젠테이션 기능을 가능하게 합니다. JSON을 PPSM으로 변환함으로써 조직은 기업 데모, 교육 세션 및 데이터 기반 보고서를 향상시키는 표준화된 대화식 슬라이드쇼를 제작할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

- **대화식 기업 데모** - 고객 또는 내부 프레젠테이션을 위한 포함된 자동화가 있는 매력적인 슬라이드쇼 구축.
- **자동화된 교육 워크플로우** - 매크로 기반 상호 작용으로 온보딩 및 교육 세션을 표준화.
- **데이터 기반 비즈니스 슬라이드쇼** - 구조화된 데이터셋으로부터 동적 보고서 및 대시보드 생성.
- **마케팅 스토리텔링** - 홍보 캠페인 및 제품 출시를 위한 매크로가 활성화된 슬라이드 생성.
- **기업 수준의 동적 보고** - 임원 및 부서 보고를 위한 반복적인 슬라이드쇼 자동화.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

- **JSON-to-PPSM 파이프라인** - 구조화된 데이터를 매크로가 활성화된 슬라이드쇼 파일로 자동 변환.
- **자동화된 매크로가 활성화된 슬라이드쇼 생성** - 반복적인 수동 슬라이드 제작 제거.
- **JSON 기반 대화식 덱** - 구조화된 데이터와 동적 매크로로 슬라이드쇼 채우기.
- **기업 전반에 걸친 동적 프레젠테이션 자동화** - 팀 및 부서 전반에 걸쳐 대화식 프레젠테이션 확장.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}