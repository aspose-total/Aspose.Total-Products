---
title: C++에서 WORDML를 XLSB로 변환
description: Microsoft Word 또는 Microsoft Excel을 사용하지 않고 WORDML를 XLSB로 변환하는 C++ API
url: /ko/cpp/conversion/wordml-to-xlsb/
family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: XLSB
otherformats: XLSM TSV CSV ODS FODS SXC XLTX EXCEL XLSX XLAM XLS XLT DIF XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="WORDML를 XLSB로 변환하는 C++ API" h2="Microsoft<sup>&reg;</sup> Word 또는 Microsoft<sup>&reg;</sup> Excel을 사용하지 않고 C++를 통해 WORDML를 XLSB로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ 애플리케이션에 WORDML에서 XLSB로의 변환 기능을 쉽게 포함할 수 있습니다. 기능이 풍부하고 강력하며 사용하기 쉬운 문서 조작 및 변환 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)를 사용하여 WORDML를 HTML로 내보낼 수 있습니다. 그 후 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)를 사용하여 HTML을 XLSB로 변환할 수 있습니다. 두 API 모두 [C++용 Aspose.Total](https://products.aspose.com/total/cpp/) 패키지에 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORDML를 XLSB로 변환하는 C++ API" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) 클래스 참조를 사용하여 WORDML 파일을 엽니다.
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string_saveformat) 멤버 함수를 사용하여 WORDML를 HTML로 변환
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 클래스 참조를 사용하여 HTML 문서 로드
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) 멤버 함수를 사용하여 문서를 XLSB 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 WORDML 문서 속성에 액세스" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/)도 WORDML 파일의 문서 속성에 액세스할 수 있으며 변환 프로세스 전에 정보에 입각한 결정을 내릴 수 있습니다. 문서 속성에 액세스하려면 [BuiltInWordmlumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_wordmlument_properties)를 사용하여 기본 제공 속성을 얻고 [CustomWordmlumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_wordmlument_properties) 사용자 지정 속성을 가져옵니다. 다음 코드 예제에서는 문서의 모든 기본 제공 및 사용자 지정 속성을 열거하는 방법을 보여줍니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-wordmlument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 스트림에 XLSB 파일 저장" %}}
WORDML를 XLSB로 변환한 후 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)를 사용하여 문서를 스트림에 저장할 수 있습니다. 스트림에 파일을 저장하려면 MemoryStream 또는 FileStream 객체를 만들고 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)을 호출하여 해당 스트림 객체에 파일을 저장합니다. 개체의 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) 메서드입니다. [Save](https://reference.aspose.com) 호출 시 [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) 열거를 사용하여 원하는 파일 형식을 지정합니다 메서드.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-xlsm/" name="WORDML 에게 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-tsv/" name="WORDML 에게 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-xlsb/" name="WORDML 에게 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-ods/" name="WORDML 에게 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-fods/" name="WORDML 에게 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-sxc/" name="WORDML 에게 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-xltx/" name="WORDML 에게 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-excel/" name="WORDML 에게 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-xlsx/" name="WORDML 에게 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-xlam/" name="WORDML 에게 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-xls/" name="WORDML 에게 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-xlt/" name="WORDML 에게 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-dif/" name="WORDML 에게 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/wordml-to-xltm/" name="WORDML 에게 XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}