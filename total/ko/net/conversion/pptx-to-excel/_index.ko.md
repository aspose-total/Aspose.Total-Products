---
title: C#을 통해 PPTX을 EXCEL로 변환
description: Microsoft Excel 또는 Powerpoint를 사용하지 않고 C#에서 PPTX을 EXCEL로 변환
url_ignore: /ko/net/conversion/pptx-to-excel/
family: total
platformtag: net
feature: conversion
informat: PPTX
outformat: EXCEL
otherformats: MARKDOWN FODS XLTX XLSB XLT XLSM XLS XLTM XLAM XLSX TSV SXC EXCEL MHTML DIF ODS DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을 통해 PPTX을 EXCEL로 변환" h2="Microsoft<sup>&reg;</sup> Excel 또는 PowerPoint를 사용하지 않고 PPTX에서 EXCEL로 변환하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 모든 .NET, C#, ASP.NET 및 VB.NET 응용 프로그램 내에서 PPTX 파일을 EXCEL로 변환할 수 있습니다. 간단한 단계. 먼저 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)을 사용하여 PPTX을 HTML로 내보낼 수 있습니다. 그런 다음 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API를 사용하여 HTML을 EXCEL로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#을 통해 PPTX을 EXCEL로 변환하는 방법" %}}
1. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 사용하여 PPTX 파일을 엽니다.
2. [저장](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 메서드를 사용하여 PPTX을 HTML로 내보냅니다.
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 HTML 문서 로드
4. [저장](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 방법을 사용하여 문서를 EXCEL로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>PPTX를 EXCEL로 변환하는 무료 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=xlsx&from=pptx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 보호된 PPTX을 EXCEL로 변환" %}}
PPTX 파일을 EXCEL로 변환하는 동안 입력 PPTX 문서가 비밀번호로 보호되어 있으면 문서를 해독하지 않고는 EXCEL로 변환할 수 없습니다. 문서가 암호로 보호되어 있다는 것은 프레젠테이션에 특정 제한을 적용한다는 의미입니다. 제한을 제거하려면 암호를 입력해야 합니다. 암호로 보호된 프레젠테이션은 잠긴 프레젠테이션으로 간주됩니다. API를 사용하면 LoadOptions 개체에 올바른 암호를 전달하여 암호화된 문서를 열 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 워터마크를 사용하여 PPTX을 EXCEL로 변환" %}}
PPTX 파일을 EXCEL로 변환하는 동안 출력 EXCEL 파일 형식에 워터마크를 추가할 수도 있습니다. 워터마크를 추가하려면 새 통합 문서 개체를 만들고 변환된 HTML 문서를 열고 해당 인덱스를 통해 워크시트를 선택하고 모양을 만들고 해당 AddTextEffect 기능을 사용할 수 있습니다. 그런 다음 Watermark를 사용하여 HTML 문서를 EXCEL로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-fods/" name="PPTX 에게 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-xltm/" name="PPTX 에게 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-xlt/" name="PPTX 에게 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-xlam/" name="PPTX 에게 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-markdown/" name="PPTX 에게 MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-excel/" name="PPTX 에게 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-mhtml/" name="PPTX 에게 MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-xlsb/" name="PPTX 에게 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-ods/" name="PPTX 에게 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-sxc/" name="PPTX 에게 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-xls/" name="PPTX 에게 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-xltx/" name="PPTX 에게 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-xlsx/" name="PPTX 에게 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-tsv/" name="PPTX 에게 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-dif/" name="PPTX 에게 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-xlsm/" name="PPTX 에게 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-doc/" name="PPTX 에게 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-docx/" name="PPTX 에게 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-docm/" name="PPTX 에게 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-dot/" name="PPTX 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-dotm/" name="PPTX 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-dotx/" name="PPTX 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-odt/" name="PPTX 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-ott/" name="PPTX 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-rtf/" name="PPTX 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-word/" name="PPTX 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-wordml/" name="PPTX 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-text/" name="PPTX 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/pptx-to-flatopx/" name="PPTX 에게 FLA에게PX" description="" >}}


{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}