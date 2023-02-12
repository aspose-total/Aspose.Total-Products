---
title: C++를 사용하여 EXCEL를 PPTX로 변환 또는 무료 온라인 변환기 사용
description: C++ 애플리케이션 내에서 EXCEL를 PPTX로 변환 또는 온라인. 코드를 통합하기 전에 무료 CSV to DOC 온라인 변환기를 빠르게 테스트하십시오.

family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: PPTX
otherformats: DOC WORD DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++를 통해 EXCEL를 PPTX로 변환 또는 온라인" h2="엑셀 내보내기&reg; 완전한 기능을 갖춘 C++ 애플리케이션 내에서 EXCEL에서 PPTX로" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++에서 EXCEL에서 PPTX로 변환" %}}
1. [Factory](https://reference.aspose.com/cells)의 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 멤버 함수를 사용하여 EXCEL 파일 열기 /cpp/class/aspose.cells.factory) 클래스 참조
2. EXCEL를 PDF로 변환하고 SaveFormat을 PDF로 설정
3. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument) 클래스 참조를 사용하여 변환된 PDF 파일을 로드합니다.
4. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) 멤버 함수를 사용하여 문서를 PPTX 형식으로 저장하고 Pptx을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EXCEL file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.excel");
// save EXCEL as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>EXCEL에서 PPTX로 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsx-to-pptx/">EXCEL를 PPTX로 변환하는 무료 앱을 사용해 보세요.</a></p>
</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/excel-to-pptx/" name="EXCEL 에게 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/excel-to-word/" name="EXCEL 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/excel-to-pptxx/" name="EXCEL 에게 PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/excel-to-powerpoint/" name="EXCEL 에게 POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}