---
title: C#을 사용하여 웹 페이지 HTML을 이미지로 변환
description: 웹 사이트 웹 페이지를 스크랩하고 HTML을 이미지로 내보냅니다. 웹 사이트 데이터를 JPEG, PNG, GIF, BMP 등으로 스크랩하는 .NET 애플리케이션을 개발합니다. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C#을 통해 웹 페이지를 이미지로 변환" h2="HTML 웹 페이지에서 웹 사이트 데이터를 추출합니다. .NET 애플리케이션 내에서 HTML을 JPG, GIF, PNG, BMP 이미지로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">웹 페이지를 이미지로 변환하는 이유는 무엇입니까?</h2>
<p>웹 페이지를 이미지로 변환하면 다양한 상황에서 유용할 수 있습니다. 이는 많은 응용 프로그램의 공통 요구 사항입니다. 일부 시나리오에서는 화면에 보이지 않는 부분을 포함하여 전체 웹 페이지를 이미지로 캡처해야 합니다. 이는 웹사이트 미리보기 생성, 영수증 및 송장 캡처 또는 법적 목적을 위한 웹페이지 보관에 유용할 수 있습니다. 문서화 또는 테스트 목적으로 웹 페이지의 스크린샷을 만드는 데 사용할 수 있습니다. 검색 결과 또는 이미지 갤러리에서 사용할 웹 페이지의 축소판 또는 미리 보기를 만드는 데 사용할 수도 있습니다. 데스크톱 애플리케이션을 구축하든 웹 애플리케이션을 구축하든 C#을 사용하여 웹 페이지를 이미지로 변환하는 데 사용할 수 있는 많은 옵션이 있습니다.</p><br />

<p>C#을 사용하여 웹 페이지를 이미지로 변환하면 다음과 같은 여러 이점을 얻을 수 있습니다.</p><br />
<ul>
<li>향상된 접근성: 시각 장애 또는 기타 장애가 있는 사용자가 이미지를 더 쉽게 읽고 이해할 수 있습니다.</li>
<li>향상된 휴대성: 이미지는 쉽게 공유하거나 다른 문서나 응용 프로그램에 포함할 수 있습니다.</li>
</ul>
<p>C#을 사용하여 웹 페이지를 이미지로 변환하면 다음과 같은 몇 가지 문제가 발생할 수 있습니다.</p><br />
<ul>
<li>제한된 형식 지원: 일부 API 또는 도구는 모든 이미지 형식을 지원하지 않거나 출력 이미지의 크기 또는 해상도에 제한이 있을 수 있습니다.</li>
<li>호환성 문제: 일부 웹 페이지는 모든 브라우저에서 올바르게 렌더링되지 않거나 제대로 표시하려면 특정 설정 또는 플러그인이 필요할 수 있습니다.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#을 사용하여 웹 페이지를 이미지로 변환하는 방법은 무엇입니까?" %}}
C#을 사용하여 웹 페이지를 이미지로 변환하려면 이 기능을 제공하는 Aspose.HTML for .NET API를 사용하여 HTML 페이지를 JPEG, PNG 및 TIFF를 비롯한 이미지 형식으로 변환할 수 있습니다.</p>

1. 에서 사용할 수 있는 생성자 중 하나를 사용하여 HTML 문서를 로드합니다. [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). 파일, HTML 코드, 스트림 또는 URL에서 HTML을 로드할 수 있습니다.
2. 새 인스턴스 만들기 [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) ImageFormat 속성을 JPEG로 설정합니다. 기본적으로 형식 속성은 PNG로 설정됩니다.
3. 활용 [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) Converter 클래스의 메서드를 사용하여 HTML 문서를 JPEG 파일로 저장합니다. HTMLDocument, ImageSaveOptions 및 출력 파일 경로를 ConvertHTML() 메서드에 대한 매개 변수로 제공해야 합니다.
4. 결과 JPEG 파일은 지정된 파일 경로에 저장됩니다.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="웹 스크래핑 및 이미지 변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔에서 직접 설치합니다.

둘 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 자식 API, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) 통합됩니다.

또는 다음에서 오프라인 MSI 설치 프로그램 또는 ZIP 파일의 DLL을 가져옵니다. [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}