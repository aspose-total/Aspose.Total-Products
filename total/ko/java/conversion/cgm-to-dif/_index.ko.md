---
title: CGM을 DIF로 렌더링하는 Java API
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 Java API를 통해 CGM을 DIF로 내보내기
url_ignore: /ko/java/conversion/cgm-to-dif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DIF
otherformats: XLT XLSB XLAM DIF XLTX XLTM SXC TXT EXCEL ODS MD XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 DIF로 내보내기" h2="Java J2SE, J2EE, J2ME 애플리케이션 내에서 사내 Java API를 사용하여 CGM 파일을 DIF로 변환" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 2단계 프로세스로 Java 애플리케이션에서 CGM을 DIF로 변환 기능을 통합할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM을 XLSX로 렌더링할 수 있습니다. 두 번째 단계에서는 Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 XLSX를 DIF로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 CGM 파일을 DIF로 변환" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 XLSX 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 DIF 형식으로 저장합니다. SaveOptions 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Java용 Aspose.Cells](https://docs.aspose.com/cells/java/installation/) pom.xml에 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
CGM 문서가 비밀번호로 보호되어 있는 경우 비밀번호 없이 DIF로 변환할 수 없습니다. API를 사용하면 먼저 유효한 암호를 사용하여 보호된 문서를 열고 그 후에 변환할 수 있습니다. 암호화된 파일을 열기 위해 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 클래스를 생성하고 파일 이름과 비밀번호를 인수로 전달합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 보호된 CGM을 DIF로 변환" %}}
CGM 파일을 DIF로 변환하는 동안 출력 DIF 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서를 만들어 변환된 XLSX 파일을 엽니다. 인덱스를 통해 워크시트를 선택하고 모양을 만들고 addTextEffect 기능을 사용하여 색상, 투명도 등을 설정합니다. 그런 다음 워터마크를 사용하여 XLSX 문서를 DIF로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM(Computer Graphics Metafile) 파일을 DIF(Data Interchange Format)로 변환하는 것은 시각적 또는 구조화된 콘텐츠를 레거시 스프레드시트 시스템 및 과학 계산 워크플로에 통합해야 하는 기관들에게 가치가 있습니다. Java 기반의 기업 및 연구 환경에서 이러한 변환은 이전 형식에서의 원활한 이주를 가능하게 하며 통계 도구와의 호환성을 지원하며 엔지니어링 응용 프로그램을 위한 구조화된 데이터 모델링을 용이하게 합니다. CGM 다이어그램을 DIF 테이블로 변환함으로써 팀은 시각적 데이터를 숫자 데이터 집합과 통합하여 플랫폼 간 접근성과 분석을 개선할 수 있습니다.

## ✅ 주요 사용 사례

- **레거시 스프레드시트 시스템 이주**  
  CGM 데이터를 DIF로 변환하여 기업 환경에서 아직 사용 중인 이전 스프레드시트 프로그램으로의 원활한 가져오기를 지원합니다.

- **과학 계산 플랫폼**  
  물리학, 화학 및 환경 모델링에서의 수치 분석 도구와의 호환성을 위해 그래픽 CGM 데이터를 DIF로 변환합니다.

- **엔지니어링 앱에서의 구조화된 데이터 모델링**  
  엔지니어링 시뮬레이션 및 CAD 데이터 통합을 위해 구조화된 테이블 형식으로 CGM 기반 도면을 나타내기 위해 DIF를 사용합니다.

## ⚙️ 자동화 시나리오

- **스프레드시트 변환을 위한 Java 라이브러리**  
  스프레드시트 호환 형식을 처리하는 Java API를 사용하여 CGM에서 DIF로 자동 변환을 구현합니다.

- **ETL 도구에서의 일괄 처리**  
  대량의 엔지니어링 또는 연구 데이터 처리를 위해 Java 기반의 추출-변환-로드 파이프라인에 변환 단계를 통합합니다.

- **통계 계산 파이프라인과의 통합**  
  Java 기반의 워크플로 오케스트레이션을 통해 변환된 DIF 파일을 R, MATLAB 또는 Python 통계 분석 모듈에 자동으로 공급합니다.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}