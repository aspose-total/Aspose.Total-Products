---
title: C++를 통해 JSON 형식을 DOTX으로 변환
description: C++ API t0 Microsoft Word를 사용하지 않고 JSON을 DOTX으로 구문 분석

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOTX
otherformats: DOC MOBI DOT ODT WORD WORDML FLATOPC PS CHM PCL OTT EPUB DOCM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++를 통해 JSON 형식을 DOTX으로 변환" h2="Microsoft<sup>&reg;</sup> Word를 사용하지 않고 C++ 애플리케이션 내에서 JSON을 DOTX으로 구문 분석" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)를 사용하면 간단한 두 단계로 C++ 애플리케이션 내에서 JSON을 DOTX으로 구문 분석할 수 있습니다. 먼저 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)를 사용하여 JSON을 PDF로 내보낼 수 있습니다. 그 후 [Aspose.Words for C++](https://products.aspose.com/words/cppp/)를 사용하여 PDF를 DOTX으로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++에서 JSON 형식을 DOTX으로 변환" %}}
1. 새 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 개체를 만들고 파일에서 유효한 JSON 데이터를 읽습니다.
2. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 메서드를 사용하여 JSON을 PDF로 저장합니다.
3. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 클래스를 사용하여 PDF 문서 로드
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 메서드를 사용하여 문서를 DOTX 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
```Install-Package Aspose.Total.Cpp```를 사용하여 Visual Studio의 패키지 관리자 콘솔을 통해 설치합니다.

또는 [downloads](https://releases.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++에서 레이아웃 설정 및 JSON 형식을 DOTX으로 변환" %}}
JSON을 DOTX으로 파싱하는 동안 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 클래스로 JSON을 로드하여 행과 열의 크기를 설정할 수도 있습니다. 워크시트의 모든 행에 대해 동일한 행 높이를 설정해야 하는 경우 [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f)를 사용하여 설정할 수 있습니다. ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) 컬렉션의 메서드입니다. 마찬가지로 워크시트의 모든 열에 동일한 열 너비를 설정하려면 ICells 컬렉션의 [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) 메서드를 사용합니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++에서 워터마크를 사용하여 JSON 형식을 DOTX으로 변환" %}}
API를 사용하여 워터마크를 사용하여 JSON을 DOTX으로 구문 분석할 수도 있습니다. DOTX 문서에 워터마크를 추가하려면 먼저 JSON을 PDF로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 클래스를 사용하여 새로 생성된 PDF 파일을 로드하고, 텍스트 워터마크에 대해 다른 속성을 설정하고,
SetText 메서드를 호출하고 TextWatermarkOptions의 워터마크 텍스트 및 개체를 전달합니다. 워터마크를 추가한 후 문서를 DOTX에 저장할 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-doc/" name="JSON 에게 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-mobi/" name="JSON 에게 MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-dot/" name="JSON 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-odt/" name="JSON 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-word/" name="JSON 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-wordml/" name="JSON 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-flatopc/" name="JSON 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-ps/" name="JSON 에게 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-dotx/" name="JSON 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-pcl/" name="JSON 에게 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-ott/" name="JSON 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-epub/" name="JSON 에게 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-docm/" name="JSON 에게 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-rtf/" name="JSON 에게 RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}