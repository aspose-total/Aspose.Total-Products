---
title: C# API를 통해 CGM을 TXT로 변환
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 CGM 파일을 TXT로 변환하는 C# API
url_ignore: /ko/net/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM을 TXT로 렌더링하는 C# API" h2="Microsoft<sup>&reg;</sup> Excel 또는 Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 C#을 통해 CGM 파일을 TXT로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 모든 .NET, C#, ASP.NET 및 VB.NET 응용 프로그램 내에서 CGM 파일을 TXT로 쉽게 변환할 수 있습니다. 먼저 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)을 사용하여 CGM을 XLSX로 내보낼 수 있습니다. 그런 다음 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API를 사용하여 XLSX를 TXT로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 TXT로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 CGM을 XLSX로 변환
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 XLSX 문서 로드
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 메서드를 사용하여 문서를 TXT 형식으로 저장하고 'Txt'를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 보호된 CGM을 TXT로 변환" %}}
CGM 문서가 비밀번호로 보호되어 있는 경우 비밀번호 없이 TXT로 변환할 수 없습니다. API를 사용하면 먼저 유효한 암호를 사용하여 보호된 문서를 열고 그 후에 변환할 수 있습니다. 암호화된 파일을 열기 위해 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스의 새 인스턴스를 초기화하고 파일 이름과 비밀번호를 인수로 전달할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 워터마크를 사용하여 CGM 파일을 TXT로 변환" %}}
CGM 파일을 TXT로 변환하는 동안 출력 TXT 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서 개체를 만들고 변환된 XLSX 문서를 열고 해당 인덱스를 통해 워크시트를 선택하고 모양을 만들고 해당 AddTextEffect 기능을 사용할 수 있습니다. 그런 다음 워터마크를 사용하여 XLSX 문서를 TXT로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 TXT로 변환: 사용 사례" %}}
CGM (컴퓨터 그래픽스 메타파일) 파일은 벡터 그래픽스 정보를 저장하기 위해 사용됩니다. 이 파일들은 정적 그래픽과 일러스트레이션을 만들기 위해 적합합니다. 그러나 동적 데이터를 처리할 때, 텍스트 편집기를如 Notepad를 사용하여 기본적인 텍스트 조작과 문서화가 필요합니다.

CGM 파일을 평범한 텍스트 포맷으로 변환하는 것은 텍스트 편집 기능을 최대한 활용할 수 있도록 합니다. 이 변환은 다음을 위해 기대됩니다:

**사용목적:**

* **데이터 문서화**: CGM 파일을 인간이 읽을 수 있는 문서로 변환하여, 그래픽 정보를 이해하고 공유할 수 있습니다.
* **텍스트 조작**: Notepad를 사용하여 CGM 파일에서 추출된 텍스트를 편집하고 조작할 수 있습니다.
* **ASCII아트 생성**: CGM 파일을 ASCII 아트로 변환하여, 간단한 텍스트 기반 그래픽으로 표현할 수 있습니다.
* **其他 도구에 데이터 임포트**: 평범한 텍스트 포맷으로 변환하여, 다른 텍스트 편집기나 워드 프로세서에 그래픽 데이터를 імпोर트할 수 있습니다.
* **기본 보고서 및 디버깅**: CGM 파일을 기본적인 보고서와 디버그 로그로 변환하여, 개발 과정에서 발생하는 오류와 문제를 식별할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}