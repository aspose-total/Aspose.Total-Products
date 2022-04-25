---
title: .NET을 통해 JSON 형식을 PCL으로 변환
description: Microsoft Word를 사용하지 않고 C#에서 JSON을 PCL으로 구문 분석
url: /ko/net/conversion/json-to-pcl/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PCL
otherformats: PS DOC DOTX DOCM RTF MOBI EPUB PCL OTT WORD ODT FLATOPC WORDML DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을 통해 JSON 형식을 PCL으로 변환" h2="Microsoft<sup>&reg;</sup> Word를 사용하지 않고 JSON을 PCL으로 구문 분석하는 C# API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 .NET, C#, ASP.NET 및 VB.NET 애플리케이션 내에서 JSON을 PCL으로 구문 분석할 수 있습니다. 단계. 먼저 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/)을 사용하여 JSON을 PDF로 내보낼 수 있습니다. 그 후 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 PDF를 PCL으로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#을 통해 JSON 형식을 PCL으로 변환" %}}
1. 새 [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 개체를 만들고 파일에서 유효한 JSON 데이터를 읽습니다.
2. [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) 클래스와 [저장](https://apireference.aspose.com/)을 사용하여 JSON 파일을 워크시트로 가져옵니다. cells/net/aspose.cells.workbook/save/methods/4) PDF로
3. [Document](https://apireference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 PDF 문서 로드
4. [저장](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3) 방법을 사용하여 문서를 PCL 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="레이아웃 설정 및 C#을 통해 JSON 형식을 PCL으로 변환" %}}
JSON을 PCL으로 구문 분석하는 동안 [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions)를 사용하여 JSON에 대한 레이아웃 옵션을 설정할 수도 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="워터마크를 사용하여 JSON 형식을 PCL으로 구문 분석" %}}
API를 사용하여 워터마크가 있는 JSON을 PCL으로 변환할 수도 있습니다. PCL 문서에 워터마크를 추가하려면 먼저 JSON 파일을 PDF로 구문 분석하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Document](https://apireference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 새로 생성된 PDF 파일을 로드하고 TextWatermarkOptions 인스턴스를 생성하고 속성을 설정합니다. , Watermark.SetText 메서드를 호출하고 TextWatermarkOptions의 워터마크 텍스트 및 개체를 전달합니다. 워터마크를 추가한 후 문서를 PCL에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-ott/" name="JSON 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-flatopc/" name="JSON 에게 FLA에게PC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-ps/" name="JSON 에게 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-dotx/" name="JSON 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-rtf/" name="JSON 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-wordml/" name="JSON 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-odt/" name="JSON 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-word/" name="JSON 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-epub/" name="JSON 에게 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-doc/" name="JSON 에게 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-dot/" name="JSON 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-pcl/" name="JSON 에게 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-mobi/" name="JSON 에게 MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-docm/" name="JSON 에게 DOCM" description="" >}}


{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}