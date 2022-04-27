---
title: WORDML를 XLSX로 변환하는 .NET API
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 WORDML를 XLSX로 변환하는 C# API
url: /ko/net/conversion/wordml-to-xlsx/
family: total
platformtag: net
feature: conversion
informat: WORDML
outformat: XLSX
otherformats: FODS EXCEL XLSB XLT XLS XLTX SXC ODS DIF XLTM XLSX XLSM XLAM TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="WORDML를 XLSX로 변환하는 C# API" h2="Microsoft<sup>&reg;</sup> Word 또는 Microsoft<sup>&reg;</sup> Excel을 사용하지 않고 C#을 통해 WORDML를 XLSX로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 모든 .NET, C#, ASP.NET 및 VB.NET 응용 프로그램 내에 WORDML에서 XLSX로 변환 기능을 포함할 수 있습니다. 두 가지 간단한 단계. 먼저 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 WORDML를 HTML로 내보낼 수 있습니다. 그런 다음 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API를 사용하여 HTML을 XLSX로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORDML를 XLSX로 변환하는 .NET API" %}}
1. [Wordmlument](https://apireference.aspose.com/words/net/aspose.words/wordmlument) 클래스를 사용하여 WORDML 파일을 엽니다.
2. [저장](https://apireference.aspose.com/words/net/aspose.words.wordmlument/save/methods/4) 메서드를 사용하여 WORDML를 HTML로 변환
3. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 HTML 문서 로드
4. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 메서드를 사용하여 문서를 XLSX 형식으로 저장하고 'XLSX'를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 스트림에서 WORDML 문서 로드" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/)에서도 스트림을 통해 WORDML 문서를 로드할 수 있습니다. 스트림에서 문서를 열려면 문서가 포함된 스트림 개체를 [Wordmlument](https://apireference.aspose.com/words/net/aspose.words/wordmlument) 생성자에 전달하기만 하면 됩니다. 다음 코드 예제는 스트림에서 문서를 여는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 XLSX 파일에 사용자 지정 속성 추가" %}}
WORDML를 XLSX로 변환하는 동안 [.NET용 Aspose.Cells](https://products.aspose.com/cells/net/)를 사용하여 XLSX 문서에 사용자 정의 속성을 추가할 수 있습니다. 사용자 지정 속성을 추가하려면 [CustomWordmlumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customwordmlumentpropertycollection) 클래스. Add 메서드는 속성을 Excel 파일에 추가하고 새 문서 속성에 대한 참조를 [Aspose.Cells.Properties.WordmlumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties)로 반환합니다. /wordmlumentproperty) 개체입니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-dif/" name="WORDML 에게 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-xlsb/" name="WORDML 에게 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-tsv/" name="WORDML 에게 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-fods/" name="WORDML 에게 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-xlt/" name="WORDML 에게 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-excel/" name="WORDML 에게 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-xlsx/" name="WORDML 에게 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-ods/" name="WORDML 에게 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-sxc/" name="WORDML 에게 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-xlam/" name="WORDML 에게 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-xltm/" name="WORDML 에게 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-xlsm/" name="WORDML 에게 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-xls/" name="WORDML 에게 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/wordml-to-xltx/" name="WORDML 에게 XLTX" description="" >}}


{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}