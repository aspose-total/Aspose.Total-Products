---
title: C# API를 통해 PS을 PPT로 내보내기
description: Microsoft Word를 사용하지 않고 PS을 PPT로 변환하는 .NET API
url_ignore: /ko/net/conversion/ps-to-ppt/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPT
otherformats: PPT POTX XAML PPS SWF POTM POWERPOINT PPSX PPTM PPSM POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 PS을 PPT로 렌더링" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 Windows, macOS 및 Linux에서 PS을 PPT로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
강력한 파일 형식 자동화 API [Aspose.Total for .NET](https://products.aspose.com/total/net/) 패키지를 사용하면 간단한 두 단계로 PS을 PPT로 쉽게 렌더링할 수 있습니다. PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 PS 파일 형식을 PPTX로 변환할 수 있습니다. 그 후 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)를 사용하여 PPTX를 PPT로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS을 PPT로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 PS 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 PS을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 이용하여 PPTX 파일 불러오기
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 메서드를 사용하여 문서를 PPT 형식으로 저장하고 'Ppt'를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 PS 파일에서 XMP 메타데이터 가져오기" %}}
PS을 PPT로 변환하는 동안 일괄 변환 프로세스의 우선 순위를 지정하기 위해 추가 XMP 메타데이터 정보가 필요할 수 있습니다. 예를 들어 생성 날짜를 기준으로 변환 문서를 가져와 정렬하고 그에 따라 문서를 처리할 수 있습니다. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)에서는 PS 파일의 XMP 메타데이터에 액세스할 수 있습니다. PS 파일의 메타데이터를 얻으려면 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 개체를 생성하고 입력된 PS 파일을 열 수 있습니다. 이후 [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 속성을 통해 파일의 메타데이터를 얻을 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 PPT 파일 생성" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API를 사용하면 변환 애플리케이션의 기능을 더욱 향상시킬 수 있습니다. 기능 중 하나는 보안을 강화하기 위해 출력 파일을 읽기 전용으로 만드는 것입니다. API를 사용하면 PPT 파일을 읽기 전용으로 설정할 수 있습니다. 즉, 프레젠테이션을 연 후 사용자에게 읽기 전용 권장 사항이 표시됩니다. 
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 PS 파일을 PPT로 변환: 사용 사례" %}}
PS (포트ABLE 닌텍 포맷) 파일은 레이아웃 정보를 저장하기 위해 사용되고, 정적 문서such as presentations, reports, and brochures를 만들기 위해 적합합니다. 그러나 다이내므리 미디어 콘텐츠를 처리하는 작업에서, 파워포인트 프레젠테이션을 통해 시각화와 상호작용을 이끌어 내는 것이 중요합니다.

PS 파일을 파워포인트 포맷으로 변환하는 것은 프리젠테이션 만들기 능력을 최대한 활용할 수 있도록 합니다. 이 변환은 다음을 할 수 있도록 합니다:

**사용 사례:**

* **프레젠테이션 디자인 및 개발**: 이미지, 비디오, 애니메이션 등 다양한 콘텐츠를 포함한 인터랙티브한 프리젠테이션을 만들기 위해 PS 파일을 파워포인트로 변환합니다.
* **슬라이드 데크 최적화**: 레이아웃과 시각적 요소들을 수정하고 최적화를 통해 깨끗한 프리젠테이션 경험을 제공할 수 있습니다.
* **콘텐츠 관리 및 업데이트**: 다수의 기기와 플랫�에서 콘텐츠를 쉽게 관리하고 업데이트할 수 있도록 PS 파일을 파워포인트로 변환합니다.
* **인터랙티브 스토리텔링**: 복잡한 정보를 ENGAGING하게 전달하기 위해 텍스트, 이미지, 오디오, 비디오를 결합한 프리젠테이션을 만들 수 있습니다.
* **콜라보레이션 및 리뷰**: 팀 멤버나 스태업과 실시간으로 공유하고 코멘트를 할 수 있도록 PS 파일을 파워포인트로 변환합니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}