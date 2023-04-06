---
title: .NET을 사용하여 XLSB를 DOCX로 변환 또는 무료 온라인 변환기 사용
description: .NET Framework, .NET Core, Mono 또는 Xamarin 플랫폼에서 XLSB를 DOCX로 변환 또는 온라인. 코드를 통합하기 전에 무료 CSV to DOC 온라인 변환기를 빠르게 테스트하십시오.

family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCX
otherformats: POWERPOINT WORD DOC PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="C#을 통해 XLSB를 DOCX로 변환 또는 온라인 앱" h2="엑셀 내보내기&reg; .NET Framework, .NET Core, Mono 또는 Xamarin 플랫폼에서 XLSB를 DOCX로">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET에서 XLSB에서 DOCX로 변환" %}}
1. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 XLSB 파일 열기
2. XLSB를 PDF로 변환하고 SaveFormat을 자동으로 설정
3. 변환된 PDF 파일을 [문서](https://apireference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 이용하여 불러옵니다.
4. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 문서를 DOCX 형식으로 저장하고 Docx을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="XLSB에서 DOCX로의 변환을 위한 .NET C# 코드" gistPath="" %}}
```cs
// load the XLSB file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsb");
// save XLSB as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>XLSB를 DOCX로 변환하는 무료 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsb" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}