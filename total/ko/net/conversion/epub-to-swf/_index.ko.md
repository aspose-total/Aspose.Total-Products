---
title: C# API를 통해 EPUB을 SWF로 내보내기
description: Microsoft Word를 사용하지 않고 EPUB을 SWF로 변환하는 .NET API
url_ignore: /ko/net/conversion/epub-to-swf/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: SWF
otherformats: OTP POTX PPTM XAML PPSX PPSM PPT SWF POTM POWERPOINT POT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 EPUB을 SWF로 렌더링" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 Windows, macOS 및 Linux에서 EPUB을 SWF로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
강력한 파일 형식 자동화 API [Aspose.Total for .NET](https://products.aspose.com/total/net/) 패키지를 사용하면 간단한 두 단계로 EPUB을 SWF로 쉽게 렌더링할 수 있습니다. PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 EPUB 파일 형식을 PPTX로 변환할 수 있습니다. 그 후 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)를 사용하여 PPTX를 SWF로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB을 SWF로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 EPUB 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 EPUB을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 이용하여 PPTX 파일 불러오기
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 메서드를 사용하여 문서를 SWF 형식으로 저장하고 'Swf'를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 EPUB 파일에서 XMP 메타데이터 가져오기" %}}
EPUB을 SWF로 변환하는 동안 일괄 변환 프로세스의 우선 순위를 지정하기 위해 추가 XMP 메타데이터 정보가 필요할 수 있습니다. 예를 들어 생성 날짜를 기준으로 변환 문서를 가져와 정렬하고 그에 따라 문서를 처리할 수 있습니다. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)에서는 EPUB 파일의 XMP 메타데이터에 액세스할 수 있습니다. EPUB 파일의 메타데이터를 얻으려면 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 개체를 생성하고 입력된 EPUB 파일을 열 수 있습니다. 이후 [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 속성을 통해 파일의 메타데이터를 얻을 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 SWF 파일 생성" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API를 사용하면 변환 애플리케이션의 기능을 더욱 향상시킬 수 있습니다. 기능 중 하나는 보안을 강화하기 위해 출력 파일을 읽기 전용으로 만드는 것입니다. API를 사용하면 SWF 파일을 읽기 전용으로 설정할 수 있습니다. 즉, 프레젠테이션을 연 후 사용자에게 읽기 전용 권장 사항이 표시됩니다. 
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.swf", SaveFormat.Swf);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EPUB 파일을 SWF로 변환: 사용 사례" %}}
EPUB (Electronic Publication) 파일은 디지털 콘텐츠를 저장하고 있는 데 적합하며, 이에 대한 인터랙티브 미디어 콘텐츠를 만들기 위해 SWF (Shockwave Flash) 파일이 필수적입니다. EPUB 파일을 SWF 형식으로 변환하는 것은 당신의 인터랙티브 미디어 능력의 완전한 잠재력을 깨우는 데 있어 必요합니다.

**사용 사례:**

* **인터렉티브 스토리텔링**: 웹사이트, 소셜 미디어, 또는 모바일 기기에서 공유할 수 있는 immersive한 인터랙티브 스토리를 만들기 위해 EPUB 파일을 SWF로 변환합니다.
* **E-learning 콘텐츠 개발**: 온라인 코스의 유용한 e-learning 모듈, 시�레이션, 그리고 교육 콘텐츠를 만드는 데 SWF를 사용합니다.
* **디지털 퍼블리싱 플랫�상 개발**: 인터랙티브한 기능을 가진 동적 디지털 퍼블리션, 잡지를 만들기 위해 EPUB 파일을 SWF로 변환합니다.
* **미디어 프레젠테이션**: 애니메이션, 비디오, 퀴즈와 같은 인터랙티브 미디어 요소가 있는 프리젠테이션을 제공하기 위해 SWF를 사용합니다.
* **게임과 시�레이션 앱 개발**: PC, 모바일 기기, 또는 웹 브라우저에서 인터랙티브한 게임, 시�레이션, 그리고 경험을 만드는 데 EPUB 파일을 SWF로 변换합니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}