---
title: C# API를 통해 EPUB을 POWERPOINT로 내보내기
description: Microsoft Word를 사용하지 않고 EPUB을 POWERPOINT로 변환하는 .NET API
url_ignore: /ko/net/conversion/epub-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: POWERPOINT
otherformats: POTX PPSM OTP POT PPSX SWF POTM XAML POWERPOINT PPTM PPT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 EPUB을 POWERPOINT로 렌더링" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 Windows, macOS 및 Linux에서 EPUB을 POWERPOINT로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
강력한 파일 형식 자동화 API [Aspose.Total for .NET](https://products.aspose.com/total/net/) 패키지를 사용하면 간단한 두 단계로 EPUB을 POWERPOINT로 쉽게 렌더링할 수 있습니다. PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 EPUB 파일 형식을 PPTX로 변환할 수 있습니다. 그 후 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)를 사용하여 PPTX를 POWERPOINT로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB을 POWERPOINT로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 EPUB 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 EPUB을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 이용하여 PPTX 파일 불러오기
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 메서드를 사용하여 문서를 POWERPOINT 형식으로 저장하고 'Powerpoint'를 SaveFormat으로 설정합니다.
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
EPUB을 POWERPOINT로 변환하는 동안 일괄 변환 프로세스의 우선 순위를 지정하기 위해 추가 XMP 메타데이터 정보가 필요할 수 있습니다. 예를 들어 생성 날짜를 기준으로 변환 문서를 가져와 정렬하고 그에 따라 문서를 처리할 수 있습니다. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)에서는 EPUB 파일의 XMP 메타데이터에 액세스할 수 있습니다. EPUB 파일의 메타데이터를 얻으려면 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 개체를 생성하고 입력된 EPUB 파일을 열 수 있습니다. 이후 [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 속성을 통해 파일의 메타데이터를 얻을 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 POWERPOINT 파일 생성" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API를 사용하면 변환 애플리케이션의 기능을 더욱 향상시킬 수 있습니다. 기능 중 하나는 보안을 강화하기 위해 출력 파일을 읽기 전용으로 만드는 것입니다. API를 사용하면 POWERPOINT 파일을 읽기 전용으로 설정할 수 있습니다. 즉, 프레젠테이션을 연 후 사용자에게 읽기 전용 권장 사항이 표시됩니다. 
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EPUB 파일을 POWERPOINT로 변환: 사용 사례" %}}
전자서적출판물(Epub 파일)은 다양한 기기에서 디지털 콘텐츠를 저장하고 읽을 수 있는 데 적합합니다. 그러나 프레젠테이션 작업에서는 마스터가 되는 PowerPoint를 사용하여 매력적인 슬라이드와 애니메이션을 창의할 때가 많습니다.

Epub 파일을 PowerPoint 형식으로 변환하는 것은 프리젠테이션 능력을 최대한 활용할 수 있도록 해줍니다. 이 변환은 다음을 달성할 수 있습니다:

**사용 사례:**

* **기업 프레젠테이션**: 인터렉티브 콘텐츠, 멀티미디어 요소, 그리고 맞춤형 레이아웃을 포함한 프로페셔널한 기업 발표를 만들기 위해 Epub 파일을 변환합니다.
* **훈련 자료**: 튜토리얼, 매뉴얼, 가이드 등 훈련 자료를 시각적으로 표현하여 이해하고 관심을 끌기 위해 PowerPoint를 사용합니다.
* **학术 프레젠테이션**: 복잡한 정보를 효과적으로 전달하기 위해 인프라그래픽, 비디오, 이미지 등을 포함한 학术 발표를 통해 매력적인 학术 콘텐츠를 만듭니다.
* **마케팅 캠페ーン**: 제품 데모, 튜토리얼, 케이스 스타디를 통해 고객을 끌고销售율을 높이는 인터렉티브한 마케팅 캠페ーン을 만들기 위해 PowerPoint를 사용합니다.
* **디지털 퍼블리싱**: 맞춤형 레이아웃, 애니메이션, 그리고 멀티미디어 콘텐츠를 포함한 인터랙티브한 디지털 퍼블리싱을 만들기 위해 Epub 파일을 변환합니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}