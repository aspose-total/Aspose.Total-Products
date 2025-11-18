---
title: Java를 통해 POTX를 JSON 형식으로 변환
description: Microsoft Excel 또는 PowerPoint를 사용하지 않고 Java를 통해 POTX를 JSON 형식으로 변환
url_ignore: /ko/java/conversion/potx-to-json/
family: total
platformtag: net
feature: conversion
informat: POTX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 POTX를 JSON 형식으로 변환" h2="Microsoft<sup>&reg;</sup> Excel 또는 PowerPoint를 사용하지 않고 POTX를 JSON으로 내보내는 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 POTX를 JSON 형식으로 변환하는 것은 간단한 2단계 프로세스입니다. 첫 번째 단계에서는 [Aspose.Slides for Java](https://products.aspose.com/slides/java/)를 사용하여 POTX를 HTML로 내보낼 수 있습니다. 둘째, [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 HTML을 JSON으로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 POTX를 JSON 형식으로 변환" %}}
1. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 POTX 파일을 엽니다.
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)을 사용하여 POTX를 HTML로 변환합니다. ISaveOptions-) 메서드
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 HTML 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 JSON 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
API를 사용하여 암호로 보호된 문서를 열 수도 있습니다. 입력 POTX 문서가 비밀번호로 보호되어 있는 경우 비밀번호를 사용하지 않고는 JSON 형식으로 변환할 수 없습니다. API를 사용하면 LoadOptions 개체에 올바른 암호를 전달하여 암호화된 문서를 열 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 보호된 POTX를 JSON 형식으로 변환" %}}
POTX를 JSON으로 변환하는 동안 범위를 출력 JSON 형식으로 설정할 수도 있습니다. 범위를 설정하려면 변환된 HTML을 Workbook 클래스를 사용하여 열고, Cells.createRange 메서드를 사용하여 내보낼 데이터 범위를 만들고, Range & ExportRangeToJsonOptions를 참조하여 JsonUtility.exportRangeToJson 메서드를 호출하고, 문자열 JSON 데이터를 파일에 씁니다. BufferedWriter.write 메서드. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```

{{< blocks/products/pf/agp/feature-section >}}



POTX를 JSON으로 변환하면 슬라이드 콘텐츠가 구조화된 JavaScript Object Notation으로 변환되어 웹 애플리케이션, 대시보드 및 API 기반 데이터 처리에 이상적입니다.



{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}



* 웹 대시보드를 위한 프레젠테이션 테이블 및 차트 내보내기.

* AI 또는 기계 학습 데이터 수집을 위해 슬라이드를 JSON으로 변환.

* 프레젠테이션 데이터로 대화식 보고 도구 준비.

* 웹 애플리케이션 및 SaaS 플랫폼과의 슬라이드 기반 콘텐츠 공유.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}



* 분석 및 보고 파이프라인을 위한 일괄 JSON 변환.

* 실시간 슬라이드 데이터 소비를 위한 API 기반 시스템 통합.

* 동적 웹 또는 모바일 대시보드를 위한 트리거 변환.

* 구조화된 JSON으로 슬라이드 콘텐츠 자동 추출.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}