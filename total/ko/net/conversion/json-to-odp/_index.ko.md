---
title: .NET을 통해 JSON 형식을 ODP로 변환
description: Microsoft PowerPoint를 사용하지 않고 C#에서 JSON을 ODP로 구문 분석
url_ignore: /ko/net/conversion/json-to-odp/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODP
otherformats: PPT OTP PPSX POWERPOINT POTM POT PPSM POTX PPTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을 통해 JSON 형식을 ODP로 변환" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 JSON을 ODP로 구문 분석하는 C# API" >}}

{{% blocks/products/pf/feature-page-summary %}}
간단한 두 단계를 거쳐 .NET, C#, ASP.NET 및 VB.NET 애플리케이션 내에서 JSON을 ODP로 변환할 수 있습니다. 먼저 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/)을 사용하여 JSON을 PPTX로 파싱할 수 있습니다. 이후 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)을 이용하여 PPTX를 ODP로 변환할 수 있습니다. 두 API 모두 [.NET용 Aspose.Total](https://products.aspose.com/total/net/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#을 통해 JSON 형식을 ODP로 변환" %}}
1. 새 [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 개체를 만들고 파일에서 유효한 JSON 데이터를 읽습니다.
2. [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) 클래스와 [저장](https://apireference.aspose.com/)을 사용하여 JSON 파일을 워크시트로 가져옵니다. cells/net/aspose.cells.workbook/save/methods/4) PPTX로
3. [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 사용하여 PPTX 문서 로드
4. [저장](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 방법을 사용하여 문서를 ODP 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="레이아웃 설정 및 C#을 통해 JSON 형식을 ODP로 변환" %}}
JSON을 ODP로 구문 분석하는 동안 [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions)를 사용하여 JSON 형식에 대한 레이아웃 옵션을 설정할 수도 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="워터마크를 사용하여 JSON 형식을 ODP로 변환" %}}
API를 사용하여 워터마크가 있는 JSON을 ODP로 변환할 수도 있습니다. ODP 문서에 워터마크를 추가하려면 먼저 JSON을 PPTX로 구문 분석하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하려면 [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 사용하여 새로 생성된 PPTX 파일을 로드하고, 마스터 프레젠테이션을 선택하고, 다음을 사용하여 모양 유형을 추가합니다. AutoShape를 추가하고 AddTextFrame을 사용하여 워터마크 텍스트를 추가합니다. 워터마크를 추가한 후 문서를 ODP에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-ppt/" name="JSON 에게 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-otp/" name="JSON 에게 OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-ppsx/" name="JSON 에게 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-powerpoint/" name="JSON 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-potm/" name="JSON 에게 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-pot/" name="JSON 에게 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-ppsm/" name="JSON 에게 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-potx/" name="JSON 에게 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-pptm/" name="JSON 에게 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/json-to-pps/" name="JSON 에게 PPS" description="" >}}


{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}