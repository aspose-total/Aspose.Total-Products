---
title: C++를 사용하여 XLTM를 POWERPOINT로 변환
description: C++ 애플리케이션 내에서 XLTM를 POWERPOINT로 변환
url: /ko/cpp/conversion/xltm-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: PPTX DOCX WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++를 통해 XLTM를 POWERPOINT로 변환" h2="엑셀 내보내기&reg; 완전한 기능을 갖춘 C++ 애플리케이션 내에서 XLTM에서 POWERPOINT로" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++에서 XLTM에서 POWERPOINT로 변환" %}}
1. [Factory](https://reference.aspose.com/cells)의 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 멤버 함수를 사용하여 XLTM 파일 열기 /cpp/class/aspose.cells.factory) 클래스 참조
2. XLTM를 PDF로 변환하고 SaveFormat을 PDF로 설정
3. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument) 클래스 참조를 사용하여 변환된 PDF 파일을 로드합니다.
4. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) 멤버 함수를 사용하여 문서를 POWERPOINT 형식으로 저장하고 Powerpoint을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltm");
// save XLTM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xltm-to-pptx/" name="XLTM 에게 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xltm-to-powerpointx/" name="XLTM 에게 POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xltm-to-word/" name="XLTM 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xltm-to-powerpoint/" name="XLTM 에게 POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}