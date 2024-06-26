---
title: .NET을 통해 JSON 형식을 DXF로 변환
description: 타사 종속성을 사용하지 않고 C#에서 JSON을 DXF로 구문 분석
url_ignore: /ko/net/conversion/json-to-dxf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DXF
otherformats: JPEG2000 WMZ DICOM SVGZ PSD WMF DXF EMZ IMAGE TGA
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을 통해 JSON 형식을 DXF로 변환" h2="타사 종속성을 사용하지 않고 JSON을 DXF로 구문 분석하는 C# API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 .NET, C#, ASP.NET 및 VB.NET 애플리케이션 내에서 JSON을 DXF로 구문 분석할 수 있습니다. 단계. 먼저 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/)을 사용하여 JSON을 JPEG로 내보낼 수 있습니다. 그 후 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/)을 사용하여 JPEG를 DXF로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#을 통해 JSON 형식을 DXF로 변환" %}}
1. 새 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 개체를 만들고 파일에서 JSON 데이터 읽기
2. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 방법을 사용하여 JSON을 JPEG로 변환
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스를 사용하여 JPEG 문서를 로드합니다.
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 방법을 사용하여 문서를 DXF 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="레이아웃 설정 및 C#을 통해 JSON 형식을 DXF로 변환" %}}
JSON을 DXF로 구문 분석하는 동안 [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions)를 사용하여 JSON에 대한 레이아웃 옵션을 설정할 수도 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="워터마크를 사용하여 JSON 형식을 DXF로 구문 분석" %}}
API를 사용하여 DXF 문서에 워터마크가 있는 JSON을 DXF로 변환할 수도 있습니다. 워터마크를 추가하려면 먼저 JSON 문서를 JPEG로 렌더링하고 그 안에 워터마크를 추가할 수 있습니다. 작업을 시연하기 위해 변환된 JPEG 이미지를 로드하고 Matrix 클래스의 개체를 사용하여 변형을 추가하고 [Graphics](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) 클래스' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) 메서드입니다. 워터마크를 추가한 후 JPEG를 DXF 형식으로 저장할 수 있습니다. 다음은 문서에 대각선 워터마크를 추가하는 방법을 보여주는 코드 예제입니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}