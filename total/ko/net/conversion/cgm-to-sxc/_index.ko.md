---
title: C# API를 통해 CGM을 SXC로 변환
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 CGM 파일을 SXC로 변환하는 C# API
url_ignore: /ko/net/conversion/cgm-to-sxc/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SXC
otherformats: TSV XLTX DIF ODS XLTM SXC TXT XLSM XLT EXCEL MD XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM을 SXC로 렌더링하는 C# API" h2="Microsoft<sup>&reg;</sup> Excel 또는 Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 C#을 통해 CGM 파일을 SXC로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 모든 .NET, C#, ASP.NET 및 VB.NET 응용 프로그램 내에서 CGM 파일을 SXC로 쉽게 변환할 수 있습니다. 먼저 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)을 사용하여 CGM을 XLSX로 내보낼 수 있습니다. 그런 다음 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API를 사용하여 XLSX를 SXC로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 SXC로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 CGM을 XLSX로 변환
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 XLSX 문서 로드
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 메서드를 사용하여 문서를 SXC 형식으로 저장하고 'Sxc'를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 보호된 CGM을 SXC로 변환" %}}
CGM 문서가 비밀번호로 보호되어 있는 경우 비밀번호 없이 SXC로 변환할 수 없습니다. API를 사용하면 먼저 유효한 암호를 사용하여 보호된 문서를 열고 그 후에 변환할 수 있습니다. 암호화된 파일을 열기 위해 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스의 새 인스턴스를 초기화하고 파일 이름과 비밀번호를 인수로 전달할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 워터마크를 사용하여 CGM 파일을 SXC로 변환" %}}
CGM 파일을 SXC로 변환하는 동안 출력 SXC 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서 개체를 만들고 변환된 XLSX 문서를 열고 해당 인덱스를 통해 워크시트를 선택하고 모양을 만들고 해당 AddTextEffect 기능을 사용할 수 있습니다. 그런 다음 워터마크를 사용하여 XLSX 문서를 SXC로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 SXC로 변환: 사용 사례" %}}
CGM 파일을 SXC 포맷으로 전환하는 것은 데이터 시각화와 분석의 완전한 잠재력을 끌어올리기 위해 必요합니다. 이 전환을 통해 다음 사용자 케이스들을 활용할 수 있습니다:

**사용자 케이스:**

* **비즈니스 운영 최적화**: CGM 파일을 분석하여 비즈니스 프로세스를 이해하고,关键 성과 지표(KPIs)를 추踪하며 개선점을 식별할 수 있습니다.
* **금융 분석 및 계획**: SXC를 통해 금융 데이터를 시각화하고 전망을 예측하며 스태허터에게 인터랙티브한 대시보드を作성할 수 있습니다.
* **공급 체인 관리**: CGM 파일을 통해 공급 체ain 시나리오를 시�션하고 로지스틱스를 최적화하며需求을 예측할 수 있습니다.
* **환경 영향평가**: SXC를 통해 환경 데이터를 시각화하고 다양한 시나리오를 모델링하여 정책의 영향을 예상할 수 있습니다.
* **의료 数据 분석**: CGM 파일을 통해 환자 데이터를 분석하여 병상 전환을 추踪하며 의료 결과에 대한 트렌드를 식별할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}