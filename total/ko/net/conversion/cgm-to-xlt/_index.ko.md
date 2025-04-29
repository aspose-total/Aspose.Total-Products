---
title: C# API를 통해 CGM을 XLT로 변환
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 CGM 파일을 XLT로 변환하는 C# API
url_ignore: /ko/net/conversion/cgm-to-xlt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLT
otherformats: XLAM XLSM MD XLTM ODS DIF EXCEL TXT XLTX TSV SXC FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM을 XLT로 렌더링하는 C# API" h2="Microsoft<sup>&reg;</sup> Excel 또는 Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 C#을 통해 CGM 파일을 XLT로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 모든 .NET, C#, ASP.NET 및 VB.NET 응용 프로그램 내에서 CGM 파일을 XLT로 쉽게 변환할 수 있습니다. 먼저 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)을 사용하여 CGM을 XLSX로 내보낼 수 있습니다. 그런 다음 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API를 사용하여 XLSX를 XLT로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 XLT로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 CGM을 XLSX로 변환
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 XLSX 문서 로드
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 메서드를 사용하여 문서를 XLT 형식으로 저장하고 'Xlt'를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 보호된 CGM을 XLT로 변환" %}}
CGM 문서가 비밀번호로 보호되어 있는 경우 비밀번호 없이 XLT로 변환할 수 없습니다. API를 사용하면 먼저 유효한 암호를 사용하여 보호된 문서를 열고 그 후에 변환할 수 있습니다. 암호화된 파일을 열기 위해 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스의 새 인스턴스를 초기화하고 파일 이름과 비밀번호를 인수로 전달할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 워터마크를 사용하여 CGM 파일을 XLT로 변환" %}}
CGM 파일을 XLT로 변환하는 동안 출력 XLT 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서 개체를 만들고 변환된 XLSX 문서를 열고 해당 인덱스를 통해 워크시트를 선택하고 모양을 만들고 해당 AddTextEffect 기능을 사용할 수 있습니다. 그런 다음 워터마크를 사용하여 XLSX 문서를 XLT로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 XLT로 변환: 사용 사례" %}}
CGM 파일을 XLT 포맷으로 전환하는 것은 데이터 시각화와 분석 기능을 fullest로 활용할 수 있도록 합니다. 이 전환은以下用途를 지원합니다:

**사용 사례:**

* **프로젝트 관리 분석**: XLM 파일을 통해 프로젝트 일정, 진행 상태, 의존 관계 등을 분석하고, 대응 조치 계획을 세울 수 있습니다.
* **시장 조사 데이터 분석**: XLT를 활용하여 고객 인구통계와 구매 패턴 같은 시장 조사 데이터를 시각적으로 표현하고, 분석할 수 있습니다.
* **금융 계획 및 예산 관리**: XLT 파일을 통해 인터랙티브한 금융 모델을 생성하고, 예산 시나리오를 시�션하며, 영업 예상치를 포기할 수 있습니다.
* **공학 설계 및 개발**: XLT를 통해 공학 설계를 시각적으로 표현하고, 시스템 성능을 시�션하며, 설계 개념을 검증할 수 있습니다.
* **영업 성과 추적**: XLT 파일을 통해 영업 성과를 분석하고, 판매 트렌드를 분석하여 개선점을 찾을 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}