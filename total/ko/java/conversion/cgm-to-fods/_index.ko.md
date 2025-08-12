---
title: CGM을 FODS로 렌더링하는 Java API
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 Java API를 통해 CGM을 FODS로 내보내기
url_ignore: /ko/java/conversion/cgm-to-fods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: FODS
otherformats: ODS TSV XLTX EXCEL XLSB TXT SXC XLSM XLTM MD XLT DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 FODS로 내보내기" h2="Java J2SE, J2EE, J2ME 애플리케이션 내에서 사내 Java API를 사용하여 CGM 파일을 FODS로 변환" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 2단계 프로세스로 Java 애플리케이션에서 CGM을 FODS로 변환 기능을 통합할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM을 XLSX로 렌더링할 수 있습니다. 두 번째 단계에서는 Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 XLSX를 FODS로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 CGM 파일을 FODS로 변환" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 XLSX 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 FODS 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Java용 Aspose.Cells](https://docs.aspose.com/cells/java/installation/) pom.xml에 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
CGM 문서가 비밀번호로 보호되어 있는 경우 비밀번호 없이 FODS로 변환할 수 없습니다. API를 사용하면 먼저 유효한 암호를 사용하여 보호된 문서를 열고 그 후에 변환할 수 있습니다. 암호화된 파일을 열기 위해 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 클래스를 생성하고 파일 이름과 비밀번호를 인수로 전달합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 보호된 CGM을 FODS로 변환" %}}
CGM 파일을 FODS로 변환하는 동안 출력 FODS 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서를 만들어 변환된 XLSX 파일을 엽니다. 인덱스를 통해 워크시트를 선택하고 모양을 만들고 addTextEffect 기능을 사용하여 색상, 투명도 등을 설정합니다. 그런 다음 워터마크를 사용하여 XLSX 문서를 FODS로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
**컴퓨터 그래픽 메타파일 (CGM)** 파일을 **FODS (Flat OpenDocument Spreadsheet)** 형식으로 변환하는 것은 그래픽 기술 데이터를 구조화된 오픈 표준 스프레드시트로 변환하는 효과적인 방법입니다. **자바 기반 오픈 소스 애플리케이션**에서 이 변환은 엔지니어, 연구원 및 데이터 분석가가 CGM 다이어그램에서 측정값, 사양 및 벡터 기반 세부 정보를 편집 가능한 FODS 스프레드시트로 추출할 수 있게 합니다. ODF 호환 XML 형식인 FODS는 OpenOffice와 같은 도구와 호환되어 소유권 제약 없이 쉽게 공유하고 협업할 수 있습니다.


## ✅ 주요 사용 사례

- **그래픽 기술 데이터를 스프레드시트로 변환**  
  CGM 파일에서 벡터 그래픽 데이터를 추출하여 분석을 위해 구조화된 행과 열로 변환합니다.

- **측정값 문서화**  
  엔지니어링 측정값이나 실험 결과를 휴대용 스프레드시트 형식으로 저장하고 관리합니다.

- **ODF 도구를 통한 공유**  
  ODF 호환 애플리케이션을 통해 유래된 CGM 스프레드시트 데이터를 배포합니다.


## ⚙️ 자동화 시나리오

- **JOpenDocument과 같은 자바 라이브러리**  
  오픈 소스 스프레드시트 처리 라이브러리를 사용하여 자바 워크플로우에서 CGM을 FODS로 자동 변환합니다.

- **헤드리스 LibreOffice 통합**  
  자바 애플리케이션에서 LibreOffice를 헤드리스 모드로 실행하여 CGM 그래픽을 일괄적으로 FODS 스프레드시트로 변환합니다.

- **대규모 FODS 생성**  
  대규모 데이터 추출을 위해 CGM 파싱 및 FODS 생성을 자바 기반 ETL 파이프라인에 통합합니다.

- **오픈 소스 데이터 처리 시스템**  
  투명하고 표준 기반 데이터 관리를 위해 FODS를 자바 기반 과학 또는 엔지니어링 플랫폼의 일부로 사용합니다.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}