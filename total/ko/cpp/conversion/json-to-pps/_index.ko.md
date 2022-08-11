---
title: C++를 통해 JSON 형식을 PPS로 변환
description: Microsoft PowerPoint를 사용하지 않고 C++에서 JSON을 PPS로 구문 분석
url: /ko/cpp/conversion/json-to-pps/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPS
otherformats: PPSX PPSM PPTM POWERPOINT POTM POTX PPT ODP OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++를 통해 JSON 형식을 PPS로 변환" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 JSON을 PPS로 구문 분석하는 C++ API" >}}

{{% blocks/products/pf/feature-page-summary %}}
간단한 두 단계로 모든 C++ 애플리케이션 내에서 JSON을 PPS로 변환할 수 있습니다. 먼저 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)를 사용하여 JSON을 PPTX로 파싱할 수 있습니다. 이후 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)를 이용하여 PPTX를 PPS로 변환할 수 있습니다. 두 API 모두 [C++용 Aspose.Total](https://products.aspose.com/total/cpp/) 패키지에 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++를 통해 JSON 형식을 PPS로 변환" %}}
1. 새 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 개체를 만들고 파일에서 유효한 JSON 데이터를 읽습니다.
2. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 메서드를 사용하여 JSON을 PPTX로 저장합니다.
3. [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 클래스를 사용하여 PPTX 문서 로드
4. [저장](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 메서드를 사용하여 문서를 PPS 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
```Install-Package Aspose.Total.Cpp```를 사용하여 Visual Studio의 패키지 관리자 콘솔을 통해 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="레이아웃 설정 및 C++를 통해 JSON 형식을 PPS로 변환" %}}
JSON을 PPS로 파싱하는 동안 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 클래스로 JSON을 로드하여 행과 열의 크기를 설정할 수도 있습니다. 워크시트의 모든 행에 대해 동일한 행 높이를 설정해야 하는 경우 [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f)를 사용하여 설정할 수 있습니다. ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) 컬렉션의 메서드입니다. 마찬가지로 워크시트의 모든 열에 동일한 열 너비를 설정하려면 ICells 컬렉션의 [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) 메서드를 사용합니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++에서 워터마크를 사용하여 JSON 형식을 PPS로 변환" %}}
API를 사용하여 워터마크가 있는 JSON을 PPS로 변환할 수도 있습니다. PPS 문서에 워터마크를 추가하려면 먼저 JSON을 PPTX로 구문 분석하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 클래스를 사용하여 새로 생성된 PPTX 파일을 로드하고 첫 번째 슬라이드를 가져오고 추가 Rectangle 형태의 AutoShape는 Rectangle에 TextFrame을 추가하고, 텍스트 프레임을 위한 Paragraph 객체를 생성하고, 단락을 위한 Portion 객체를 생성하고, set_Text()를 이용하여 워터마크를 추가하고, PPS에 문서를 저장할 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-ppsx/" name="JSON 에게 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-ppsm/" name="JSON 에게 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-pptm/" name="JSON 에게 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-powerpoint/" name="JSON 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-potm/" name="JSON 에게 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-potx/" name="JSON 에게 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-ppt/" name="JSON 에게 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-pps/" name="JSON 에게 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-otp/" name="JSON 에게 OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/json-to-pot/" name="JSON 에게 POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}