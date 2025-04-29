---
title: C# API를 통해 CGM을 XLSB로 변환
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 CGM 파일을 XLSB로 변환하는 C# API
url_ignore: /ko/net/conversion/cgm-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLSB
otherformats: XLSB TSV XLTX ODS XLSM XLT XLTM EXCEL SXC TXT FODS MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM을 XLSB로 렌더링하는 C# API" h2="Microsoft<sup>&reg;</sup> Excel 또는 Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 C#을 통해 CGM 파일을 XLSB로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 모든 .NET, C#, ASP.NET 및 VB.NET 응용 프로그램 내에서 CGM 파일을 XLSB로 쉽게 변환할 수 있습니다. 먼저 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)을 사용하여 CGM을 XLSX로 내보낼 수 있습니다. 그런 다음 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API를 사용하여 XLSX를 XLSB로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 XLSB로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 CGM을 XLSX로 변환
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 XLSX 문서 로드
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 메서드를 사용하여 문서를 XLSB 형식으로 저장하고 'Xlsb'를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 보호된 CGM을 XLSB로 변환" %}}
CGM 문서가 비밀번호로 보호되어 있는 경우 비밀번호 없이 XLSB로 변환할 수 없습니다. API를 사용하면 먼저 유효한 암호를 사용하여 보호된 문서를 열고 그 후에 변환할 수 있습니다. 암호화된 파일을 열기 위해 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스의 새 인스턴스를 초기화하고 파일 이름과 비밀번호를 인수로 전달할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 워터마크를 사용하여 CGM 파일을 XLSB로 변환" %}}
CGM 파일을 XLSB로 변환하는 동안 출력 XLSB 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서 개체를 만들고 변환된 XLSX 문서를 열고 해당 인덱스를 통해 워크시트를 선택하고 모양을 만들고 해당 AddTextEffect 기능을 사용할 수 있습니다. 그런 다음 워터마크를 사용하여 XLSX 문서를 XLSB로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 XLSB로 변환: 사용 사례" %}}
CGM (컴퓨터 그래픽스 메타파일) 파일은 벡터 그래픽스의 정보를 저장하기 위해 사용됩니다. 이 파일들은 정적인 그래픽과 일러스트레이션을 만들기 위해 이상적이라고 할 수 있습니다. 그러나 동적인 데이터를 처리할 때, 스페레드시트如 염소에서 데이터 시각화와 분석이 필요합니다.

CGM 파일을 염소 포맷으로 변환하는 것은 데이터의 완전한 시각화와 분석 가능성을 풀어주는 것입니다. 이 변환은 다음을 할 수 있습니다:

**사용 사례:**

* **정적 그래픽 리디자인:** CGM 파일을 통해 최적화된 정적 그래픽, 로고, 아이콘 등을 만들 수 있습니다. 색상, 형상, 크기를 정확하게 조절할 수 있어야 합니다.
* **일러스트레이션과 그래픽 편집:** 염소에서 벡터 그래픽을 편집할 수 있습니다. 이미지 합성도 가능하며 텍스트나 효과를 추가하여 일러스트레이션을 개선할 수 있습니다.
* **브로셔 디자인 및 레이아웃:** CGM 파일을 통해 인터랙티브한 브로셔 디자인을 만들 수 있습니다. 콘텐츠를 배열하고 레이아웃을 쉽게 조절할 수 있습니다.
* **인포그래픽 생성:** 염소에서 흥미로운 인포그래픽을设计할 수 있습니다. 데이터를 조직하고 복잡한 정보를清晰하게 시각화할 수 있습니다.
* **정적 보고서生成:** CGM 파일을 통해 인터랙티브한 보고서를 만들 수 있습니다. 주요 성과 지표(KPIs)를 추적하고 비즈니스 이론을 시각적으로 표현할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}