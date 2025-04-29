---
title: C# API를 통해 CGM을 PPS로 내보내기
description: Microsoft Word를 사용하지 않고 CGM을 PPS로 변환하는 .NET API
url_ignore: /ko/net/conversion/cgm-to-pps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPS
otherformats: PPSM PPS PPTM POWERPOINT PPT PPSX XAML POTM POTX SWF OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 CGM을 PPS로 렌더링" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 Windows, macOS 및 Linux에서 CGM을 PPS로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
강력한 파일 형식 자동화 API [Aspose.Total for .NET](https://products.aspose.com/total/net/) 패키지를 사용하면 간단한 두 단계로 CGM을 PPS로 쉽게 렌더링할 수 있습니다. PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 CGM 파일 형식을 PPTX로 변환할 수 있습니다. 그 후 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)를 사용하여 PPTX를 PPS로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 PPS로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 CGM을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 이용하여 PPTX 파일 불러오기
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 메서드를 사용하여 문서를 PPS 형식으로 저장하고 'Pps'를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 CGM 파일에서 XMP 메타데이터 가져오기" %}}
CGM을 PPS로 변환하는 동안 일괄 변환 프로세스의 우선 순위를 지정하기 위해 추가 XMP 메타데이터 정보가 필요할 수 있습니다. 예를 들어 생성 날짜를 기준으로 변환 문서를 가져와 정렬하고 그에 따라 문서를 처리할 수 있습니다. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)에서는 CGM 파일의 XMP 메타데이터에 액세스할 수 있습니다. CGM 파일의 메타데이터를 얻으려면 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 개체를 생성하고 입력된 CGM 파일을 열 수 있습니다. 이후 [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 속성을 통해 파일의 메타데이터를 얻을 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 PPS 파일 생성" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API를 사용하면 변환 애플리케이션의 기능을 더욱 향상시킬 수 있습니다. 기능 중 하나는 보안을 강화하기 위해 출력 파일을 읽기 전용으로 만드는 것입니다. API를 사용하면 PPS 파일을 읽기 전용으로 설정할 수 있습니다. 즉, 프레젠테이션을 연 후 사용자에게 읽기 전용 권장 사항이 표시됩니다. 
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 PPS로 변환: 사용 사례" %}}
CGM (컴퓨터 그래픽스 메타파일) 파일은 벡터 그래픽스 정보를 저장하기 위해 사용되고, 정적 그래픽과 일러스트레이션을 만들기 위해 적합합니다. 그러나 동적 데이터를 처리할 때, 스페레드시트如 엑셀은 데이터 시각화와 분석에 있어 필수적입니다.

CGM 파일을 PPS (포터블 프레젠테이션) 포맷으로 변환하는 것은 귀하의 프리젠테이션과 시각화를 최대한 활용할 수 있도록 해줍니다. 이 변환은 다음을 위해 사용할 수 있습니다:

**사용 사례:**

* **프레젠퉴 디자인**: CGM 파일을 PPS로 변환하여 프로페셔널한 슬라이드, 애니메이션, 그리고 전환 효과를 만들고 관众을 매료시키는 데 적합합니다.
* **훈련과 교육**: PPS를 사용하여 인터랙티브한 훈련 자료, 시�션, 그리고 튜터리얼을 만들어 학습 결과를 개선하는 데 도움이 됩니다.
* **마케팅과 세일즈 마테리얼**: CGM 파일을 PPS로 변환하여 설득력 있는 세일스 콜라테럴, 제품 데모, 그리고 마케팅 자료를 만들 수 있습니다.
* **기업 커뮤니케이션**: PPS를 사용하여 내부 커뮤니케이션, 보고서, 그리고 인포그래픽스를 만들 수 있어 정보 전달을 더 나아지게 됩니다.
* **이벤트와 엑스비시yon 비주얼라이제이션**: CGM 파일을 PPS로 변환하여 눈길을 끌는 이벤트 그래픽, 展示 디자인, 그리고 트레이드 쇼 디스플레이를 만들 수 있습니다.

CGM 파일을 PPS로 변환하면 최신 프리젠테이션 소프트웨어의 고급 애니메이션, 전환 효과, 그리고 효과를 활용할 수 있도록 해줍니다. 이 변환은 귀하의 시각적 콘텐츠가 최고의 형태로 보이도록 해주며, 프로페셔널한 프리젠퉴을 만드는 데 필수적인 단계입니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}