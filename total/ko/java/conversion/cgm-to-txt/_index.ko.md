---
title: CGM을 TXT로 렌더링하는 Java API
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 Java API를 통해 CGM을 TXT로 내보내기
url_ignore: /ko/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 TXT로 내보내기" h2="Java J2SE, J2EE, J2ME 애플리케이션 내에서 사내 Java API를 사용하여 CGM 파일을 TXT로 변환" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 2단계 프로세스로 Java 애플리케이션에서 CGM을 TXT로 변환 기능을 통합할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM을 XLSX로 렌더링할 수 있습니다. 두 번째 단계에서는 Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 XLSX를 TXT로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 CGM 파일을 TXT로 변환" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 XLSX 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 TXT 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Java용 Aspose.Cells](https://docs.aspose.com/cells/java/installation/) pom.xml에 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
CGM 문서가 비밀번호로 보호되어 있는 경우 비밀번호 없이 TXT로 변환할 수 없습니다. API를 사용하면 먼저 유효한 암호를 사용하여 보호된 문서를 열고 그 후에 변환할 수 있습니다. 암호화된 파일을 열기 위해 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 클래스를 생성하고 파일 이름과 비밀번호를 인수로 전달합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 보호된 CGM을 TXT로 변환" %}}
CGM 파일을 TXT로 변환하는 동안 출력 TXT 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서를 만들어 변환된 XLSX 파일을 엽니다. 인덱스를 통해 워크시트를 선택하고 모양을 만들고 addTextEffect 기능을 사용하여 색상, 투명도 등을 설정합니다. 그런 다음 워터마크를 사용하여 XLSX 문서를 TXT로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
**컴퓨터 그래픽 메타파일 (CGM)** 파일을 **TXT (평문)** 형식으로 변환하는 것은 가벼우면서 사람이 읽기 쉬운 형태로 벡터 그래픽 정보를 추출, 문서화 및 처리하는 데 유용합니다. **자바 기반 데이터 처리 파이프라인**에서 이 변환은 CGM 다이어그램을 텍스트 기반 표현으로 변환하여 로깅, 메타데이터 저장 또는 하류 분석을 위한 변환을 가능하게 합니다. CGM 파일의 설명 요소를 TXT로 캡처함으로써 조직은 다른 시스템과의 통합을 간소화하고 빠른 검색 및 색인화를 가능하게 하며 장기적인 호환성을 유지할 수 있습니다.

## ✅ 주요 사용 사례

- **다이어그램의 텍스트 기반 로깅**  
  CGM 다이어그램 정보를 감사, 디버깅 또는 보관 목적으로 평문으로 저장합니다.

- **벡터 그래픽 설명 추출**  
  CGM 구조를 파싱, 검색 색인 또는 분석 도구 통합을 위해 TXT로 변환합니다.

- **공학 메타데이터 문서화**  
  TXT 파일에 CGM 관련 공학 데이터를 문서화하여 빠른 참조와 가벼운 저장을 가능하게 합니다.

## ⚙️ 자동화 시나리오

- **변환을 위한 Java I/O 라이브러리**  
  표준 Java 파일 처리 API와 CGM 파서를 사용하여 내용을 추출하고 TXT 파일에 작성합니다.

- **파일 감시자 서비스**  
  Java `WatchService`를 사용하여 디렉토리를 모니터링하여 새 파일 이벤트에 대비하여 CGM을 TXT로 자동 변환합니다.

- **일괄 변환 작업**  
  예약된 Java 작업에서 대량의 CGM 파일을 처리하여 보존 또는 분석을 위해 텍스트 표현을 내보냅니다.

- **ETL 파이프라인의 평문 내보내기자**  
  구조화된 데이터 처리를 위해 Java 기반 추출-변환-로드 워크플로에 CGM 파싱 및 TXT 내보내기를 통합합니다.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}