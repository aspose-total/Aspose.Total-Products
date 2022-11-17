---
title: XSLFO을 XLTX로 변환하는 C++ API
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 C++ API를 통해 XSLFO을 XLTX로 변환

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: XLTX
otherformats: CSV MD DIF EXCEL XLT TXT TSV XLAM FODS SXC XLSB ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ 응용 프로그램에서 XSLFO을 XLTX로 렌더링" h2="Microsoft<sup>&reg;</sup> Excel 또는 Adobe<sup>&reg;</sup> Acrobat Reader 없이 기본 C++ 응용 프로그램에서 XSLFO을 XLTX로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 파일 형식 자동화 라이브러리를 통해 C++에서 XSLFO을 XLTX로 변환하는 것은 간단한 2단계 프로세스입니다. 첫 번째 단계에서는 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)를 사용하여 XSLFO을 XLSX로 내보낼 수 있으며, 그 후 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) 스프레드시트 프로그래밍 API, XLSX를 XLTX로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XSLFO을 XLTX로 변환하는 C++ API" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 클래스 참조를 사용하여 XSLFO 파일 열기
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) 멤버 함수를 사용하여 XSLFO을 XLSX로 변환
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 클래스 참조를 사용하여 XLSX 문서 로드
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 멤버 함수를 사용하여 문서를 XLTX 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 XSLFO 파일 정보 가져오기 또는 설정" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)를 사용하면 XSLFO 문서에 대한 정보를 얻을 수 있으며 변환 프로세스 전에 정보에 입각한 결정을 내릴 수 있습니다. XSLFO 파일의 파일별 정보를 얻으려면 먼저 [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) 메서드를 호출해야 합니다. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 클래스입니다. DocumentInfo 개체가 검색되면 개별 속성의 값을 가져올 수 있습니다. 또한 DocumentInfo 클래스의 각 메소드를 사용하여 속성을 설정할 수도 있습니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 스트림에 XLTX 파일 형식 저장" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/)를 사용하면 XLTX 파일 형식을 스트리밍에 저장할 수 있습니다. 스트림에 파일을 저장하려면 MemoryStream 또는 FileStream 객체를 만들고 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)을 호출하여 해당 스트림 객체에 파일을 저장합니다. 개체의 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) 메서드입니다. Save 메서드를 호출할 때 [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) 열거를 사용하여 원하는 파일 형식을 지정합니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xltx-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-xltx/" name="XSLFO 에게 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-md/" name="XSLFO 에게 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-dif/" name="XSLFO 에게 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-excel/" name="XSLFO 에게 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-xlt/" name="XSLFO 에게 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-txt/" name="XSLFO 에게 TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-tsv/" name="XSLFO 에게 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-xlam/" name="XSLFO 에게 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-fods/" name="XSLFO 에게 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-sxc/" name="XSLFO 에게 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-xlsb/" name="XSLFO 에게 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/xslfo-to-ods/" name="XSLFO 에게 ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}