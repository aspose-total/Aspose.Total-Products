---
title: .NET을 사용하여 SXC를 DOCX로 변환 
description: .NET Framework, .NET Core, Mono 또는 Xamarin 플랫폼에서 SXC를 DOCX로 변환
url: /ko/net/conversion/sxc-to-docx/
family: total
platformtag: net
feature: conversion
informat: SXC
outformat: DOCX
otherformats: WORD PPTX POWERPOINT DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C#을 통해 SXC를 DOCX로 변환" h2="엑셀 내보내기&reg; .NET Framework, .NET Core, Mono 또는 Xamarin 플랫폼에서 SXC를 DOCX로">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET에서 SXC에서 DOCX로 변환" %}}
1. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 SXC 파일 열기
2. SXC를 PDF로 변환하고 SaveFormat을 자동으로 설정
3. 변환된 PDF 파일을 [문서](https://apireference.aspose.com/pdf/net/aspose.pdf/docxument) 클래스를 이용하여 불러옵니다.
4. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.docxument/save/methods/5) 방법을 사용하여 문서를 DOCX 형식으로 저장하고 Docx을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="SXC에서 DOCX로의 변환을 위한 .NET C# 코드" gistPath="" %}}
```cs
// load the SXC file using Workbook class
var book = new Aspose.Cells.Workbook("input.sxc");
// save SXC as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Docxument class
var docxument = new Aspose.Pdf.Docxument("pdfOutput.pdf");
// save docxument in DOCXX format
docxument.Save("output.docxx", SaveFormat.DocxX); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/csv-to-word/" name="CSV 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/csv-to-powerpoint/" name="CSV 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/csv-to-pptx/" name="CSV 에게 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/csv-to-docx/" name="CSV 에게 DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}