---
title: .NET을 통해 DOTM를 JSON 형식으로 변환
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 C#에서 DOTM를 JSON으로 변환
url_ignore: /ko/net/conversion/dotm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM SXC XLTM TSV DIF FODS XLSM XLSX ODS XLTX XLS EXCEL XLSB XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을 통해 DOTM를 JSON 형식으로 변환" h2="Microsoft<sup>&reg;</sup> Word 또는 Excel을 사용하지 않고 C#을 통해 DOTM를 JSON으로 구문 분석" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 모든 .NET, C#, ASP.NET 및 VB.NET 응용 프로그램 내에서 DOTM를 JSON 형식으로 변환할 수 있습니다. 간단한 단계. 먼저 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 DOTM를 HTML로 내보낼 수 있습니다. 그 후 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API를 사용하여 HTML을 JSON으로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#을 통해 DOTM를 JSON 형식으로 변환" %}}
1. [Dotmument](https://reference.aspose.com/words/net/aspose.words/dotmument) 클래스를 사용하여 DOTM 파일을 엽니다.
2. [Save](https://reference.aspose.com/words/net/aspose.words.dotmument/save/methods/4) 메서드를 사용하여 DOTM를 HTML로 변환
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 HTML 문서 로드
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 메서드를 사용하여 문서를 JSON 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 보호된 DOTM를 JSON 형식으로 변환" %}}
API를 사용하여 암호로 보호된 문서를 열 수도 있습니다. 입력 DOTM 문서가 비밀번호로 보호되어 있는 경우 비밀번호를 사용하지 않고는 JSON 형식으로 변환할 수 없습니다. API를 사용하면 LoadOptions 개체에 올바른 암호를 전달하여 암호화된 문서를 열 수 있습니다. 다음 코드 예제에서는 암호로 암호화된 문서를 여는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 범위에서 DOTM를 JSON으로 변환" %}}
DOTM를 JSON으로 변환하는 동안 범위를 출력 JSON 형식으로 설정할 수도 있습니다. 범위를 설정하려면 변환된 HTML을 Workbook 클래스를 사용하여 열고, 데이터가 포함된 Worksheet의 CellsCollection을 가져오고, 행 및 열 인덱스를 지정하여 CellsCollection에서 범위를 만들고, Range 및 ExportRangeToJsonOptions 개체에 대한 참조를 사용하여 ExportRangeToJson 메서드를 호출할 수 있습니다. 마지막으로 File.WriteAllText 메서드를 통해 JSON 데이터를 파일에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}