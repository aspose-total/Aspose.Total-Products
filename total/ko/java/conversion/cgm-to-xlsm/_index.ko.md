---
title: CGM을 XLSM로 렌더링하는 Java API
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 Java API를 통해 CGM을 XLSM로 내보내기
url_ignore: /ko/java/conversion/cgm-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLSM
otherformats: FODS XLAM DIF SXC XLTM MD XLSM TSV EXCEL XLTX XLT ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 XLSM로 내보내기" h2="Java J2SE, J2EE, J2ME 애플리케이션 내에서 사내 Java API를 사용하여 CGM 파일을 XLSM로 변환" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 2단계 프로세스로 Java 애플리케이션에서 CGM을 XLSM로 변환 기능을 통합할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM을 XLSX로 렌더링할 수 있습니다. 두 번째 단계에서는 Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 XLSX를 XLSM로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 CGM 파일을 XLSM로 변환" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 XLSX 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 XLSM 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Java용 Aspose.Cells](https://docs.aspose.com/cells/java/installation/) pom.xml에 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
CGM 문서가 비밀번호로 보호되어 있는 경우 비밀번호 없이 XLSM로 변환할 수 없습니다. API를 사용하면 먼저 유효한 암호를 사용하여 보호된 문서를 열고 그 후에 변환할 수 있습니다. 암호화된 파일을 열기 위해 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 클래스를 생성하고 파일 이름과 비밀번호를 인수로 전달합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 보호된 CGM을 XLSM로 변환" %}}
CGM 파일을 XLSM로 변환하는 동안 출력 XLSM 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서를 만들어 변환된 XLSX 파일을 엽니다. 인덱스를 통해 워크시트를 선택하고 모양을 만들고 addTextEffect 기능을 사용하여 색상, 투명도 등을 설정합니다. 그런 다음 워터마크를 사용하여 XLSX 문서를 XLSM로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM 파일을 **XLSM (매크로 활성화 Excel 워크북)** 형식으로 변환하는 것은 자바 기반 시스템에서 조직이 공학 계산, 보고 및 시각화 워크플로우를 자동화할 수 있게 합니다. XLSM을 사용하면 매크로가 동적으로 CGM에서 파생된 데이터를 처리하고 복잡한 계산을 수행하며 수동 개입 없이 차트나 다이어그램을 업데이트할 수 있습니다. 이를 통해 기술 및 운영용으로 더 스마트하고 자체 업데이트되는 보고서를 만들 수 있습니다.

## ✅ 주요 사용 사례
- 포함된 매크로로 자동화된 공학 보고서 생성.
- 제조 또는 설계 데이터에 대한 동적 계산 워크플로우.
- 매크로 논리가 포함된 CGM 다이어그램을 Excel 모델에 통합.
- 매크로 활성화 분석을 통한 간소화된 품질 관리 프로세스.

## ⚙️ 자동화 시나리오
- 매크로 실행 지원을 통한 자바 Excel 자동화 엔진.
- Java API를 통한 매크로 활성화 스프레드시트 생성.
- 기업 시스템에서 CGM 데이터 세트로부터 예약된 XLSM 생성.
- 실시간 공학 대시보드를 위한 자동화된 매크로 트리거.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}