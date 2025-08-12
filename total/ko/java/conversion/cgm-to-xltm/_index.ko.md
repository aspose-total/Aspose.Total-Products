---
title: CGM을 XLTM로 렌더링하는 Java API
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 Java API를 통해 CGM을 XLTM로 내보내기
url_ignore: /ko/java/conversion/cgm-to-xltm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLTM
otherformats: XLTM TSV TXT XLT ODS EXCEL XLTX MD SXC XLSB DIF XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 XLTM로 내보내기" h2="Java J2SE, J2EE, J2ME 애플리케이션 내에서 사내 Java API를 사용하여 CGM 파일을 XLTM로 변환" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 2단계 프로세스로 Java 애플리케이션에서 CGM을 XLTM로 변환 기능을 통합할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM을 XLSX로 렌더링할 수 있습니다. 두 번째 단계에서는 Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 XLSX를 XLTM로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 CGM 파일을 XLTM로 변환" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 XLSX 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 XLTM 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Java용 Aspose.Cells](https://docs.aspose.com/cells/java/installation/) pom.xml에 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
CGM 문서가 비밀번호로 보호되어 있는 경우 비밀번호 없이 XLTM로 변환할 수 없습니다. API를 사용하면 먼저 유효한 암호를 사용하여 보호된 문서를 열고 그 후에 변환할 수 있습니다. 암호화된 파일을 열기 위해 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 클래스를 생성하고 파일 이름과 비밀번호를 인수로 전달합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 보호된 CGM을 XLTM로 변환" %}}
CGM 파일을 XLTM로 변환하는 동안 출력 XLTM 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서를 만들어 변환된 XLSX 파일을 엽니다. 인덱스를 통해 워크시트를 선택하고 모양을 만들고 addTextEffect 기능을 사용하여 색상, 투명도 등을 설정합니다. 그런 다음 워터마크를 사용하여 XLSX 문서를 XLTM로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM 파일을 **XLTM (매크로 활성화 엑셀 템플릿)** 형식으로 변환하면 자바 플랫폼에서 자동화 주도 워크플로우를 지원하여 사전 구성된 템플릿에 기존 매크로를 포함시킬 수 있습니다. 이를 통해 엔지니어들은 스프레드시트 논리를 다시 구축하지 않고도 매크로가 활성화된 보고서를 빠르게 생성하고 자동 계산을 실행하며 CGM 입력에서 시각화를 업데이트할 수 있습니다.

## ✅ 주요 사용 사례
- 엔지니어링 프로세스 자동화를 위한 매크로 활성화된 템플릿.
- CGM 통합 계산을 통한 자동 보고.
- 제조 및 연구 및 개발 팀을 위한 스마트 문서 워크플로우.
- 내장 검증 매크로가 포함된 품질 관리 템플릿.

## ⚙️ 자동화 시나리오
- 자바 엔터프라이즈 애플리케이션에서 매크로 템플릿 렌더링.
- 다양한 프로젝트를 위한 일괄 CGM-to-XLTM 템플릿 생성.
- ETL 기반 매크로 활성화된 보고 파이프라인.
- 실시간 운영 보고를 위한 자바 트리거 매크로.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}