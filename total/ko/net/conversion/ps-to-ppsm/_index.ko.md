---
title: C# API를 통해 PS을 PPSM로 내보내기
description: Microsoft Word를 사용하지 않고 PS을 PPSM로 변환하는 .NET API
url_ignore: /ko/net/conversion/ps-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPSM
otherformats: PPSX POTX PPTM POWERPOINT SWF POTM PPSM PPS OTP PPT POT XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 PS을 PPSM로 렌더링" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 Windows, macOS 및 Linux에서 PS을 PPSM로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
강력한 파일 형식 자동화 API [Aspose.Total for .NET](https://products.aspose.com/total/net/) 패키지를 사용하면 간단한 두 단계로 PS을 PPSM로 쉽게 렌더링할 수 있습니다. PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 PS 파일 형식을 PPTX로 변환할 수 있습니다. 그 후 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)를 사용하여 PPTX를 PPSM로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS을 PPSM로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 PS 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 PS을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 이용하여 PPTX 파일 불러오기
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 메서드를 사용하여 문서를 PPSM 형식으로 저장하고 'Ppsm'를 SaveFormat으로 설정합니다.
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
PS을 PPSM로 변환하는 동안 일괄 변환 프로세스의 우선 순위를 지정하기 위해 추가 XMP 메타데이터 정보가 필요할 수 있습니다. 예를 들어 생성 날짜를 기준으로 변환 문서를 가져와 정렬하고 그에 따라 문서를 처리할 수 있습니다. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)에서는 PS 파일의 XMP 메타데이터에 액세스할 수 있습니다. PS 파일의 메타데이터를 얻으려면 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 개체를 생성하고 입력된 PS 파일을 열 수 있습니다. 이후 [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 속성을 통해 파일의 메타데이터를 얻을 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 PPSM 파일 생성" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API를 사용하면 변환 애플리케이션의 기능을 더욱 향상시킬 수 있습니다. 기능 중 하나는 보안을 강화하기 위해 출력 파일을 읽기 전용으로 만드는 것입니다. API를 사용하면 PPSM 파일을 읽기 전용으로 설정할 수 있습니다. 즉, 프레젠테이션을 연 후 사용자에게 읽기 전용 권장 사항이 표시됩니다. 
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsm", SaveFormat.Ppsm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 PS 파일을 PPSM로 변환: 사용 사례" %}}
**파일 전환 안내서**

PDF (포터블 문서 형식) 파일은 문서를 저장하고 печать나 공유에 적합한 파일로 사용됩니다. 그러나 편집 가능한 내용을 작업할 때, Microsoft Office 포맷은 편집과 협업에 필수적이 됩니다.

PDF 파일을 PPSM (파워포인트 슬라이드 마스터) 포맷으로 전환하는 것은你的 프레젠테이션 디자인과 레이아웃 능력을 최대한 활용할 수 있도록 합니다. 이 전환은 다음 기능을 사용할 수 있도록 합니다:

**사용 사례:**

*   **기업 프리젠테이션 디자인**: PDF 파일을 전환하여 기업 브랜드로고, 타이포그래피 등 일관적인 기업 이미지를 모든 프레젠테이션에 적용할 수 있습니다.
*   **마케팅 자료 제작**: PPSM을 사용하여 마케팅 자료 such as 브로셔, 플라이어, 포스터를 디자인하고 편집할 수 있습니다.
*   **훈련 자료 개발**: PDF 파일을 전환하여 인터랙티브한 훈련 자료, 시�션, 튜토리얼을 만들 수 있습니다.
*   **퍼블리케이션 디자인 및 레이아웃**: PPSM을 사용하여 잡지, 신문, 학술지를 위한 레이아웃을 디자인하고 편집할 수 있습니다.
*   **커스텀 파워포인트 템플릿**: PDF 파일을 전환하여 커스텀 파워포인트 템플릿을 만들 수 있습니다. 이 방법은 디자이너와 프레젠테이션 담당자에게 시간과 노력을 절약합니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}