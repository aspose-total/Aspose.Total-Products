---
title: C# API를 통해 EPUB을 PPSX로 내보내기
description: Microsoft Word를 사용하지 않고 EPUB을 PPSX로 변환하는 .NET API
url_ignore: /ko/net/conversion/epub-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPSX
otherformats: PPSM POTX PPT PPS XAML OTP PPTM PPSX POTM POT SWF POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 EPUB을 PPSX로 렌더링" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 Windows, macOS 및 Linux에서 EPUB을 PPSX로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
강력한 파일 형식 자동화 API [Aspose.Total for .NET](https://products.aspose.com/total/net/) 패키지를 사용하면 간단한 두 단계로 EPUB을 PPSX로 쉽게 렌더링할 수 있습니다. PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 EPUB 파일 형식을 PPTX로 변환할 수 있습니다. 그 후 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)를 사용하여 PPTX를 PPSX로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB을 PPSX로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 EPUB 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 EPUB을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 이용하여 PPTX 파일 불러오기
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 메서드를 사용하여 문서를 PPSX 형식으로 저장하고 'Ppsx'를 SaveFormat으로 설정합니다.
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
EPUB을 PPSX로 변환하는 동안 일괄 변환 프로세스의 우선 순위를 지정하기 위해 추가 XMP 메타데이터 정보가 필요할 수 있습니다. 예를 들어 생성 날짜를 기준으로 변환 문서를 가져와 정렬하고 그에 따라 문서를 처리할 수 있습니다. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)에서는 EPUB 파일의 XMP 메타데이터에 액세스할 수 있습니다. EPUB 파일의 메타데이터를 얻으려면 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 개체를 생성하고 입력된 EPUB 파일을 열 수 있습니다. 이후 [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 속성을 통해 파일의 메타데이터를 얻을 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 PPSX 파일 생성" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API를 사용하면 변환 애플리케이션의 기능을 더욱 향상시킬 수 있습니다. 기능 중 하나는 보안을 강화하기 위해 출력 파일을 읽기 전용으로 만드는 것입니다. API를 사용하면 PPSX 파일을 읽기 전용으로 설정할 수 있습니다. 즉, 프레젠테이션을 연 후 사용자에게 읽기 전용 권장 사항이 표시됩니다. 
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsx", SaveFormat.Ppsx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EPUB 파일을 PPSX로 변환: 사용 사례" %}}
전자출판물(Epub)파일은 다양한 디지털 콘텐츠를 저장하고 공유하기 위해 사용되는 파일 형식입니다. 이 파일들은 특히 프레젠테이션에 있어서는 한계가 있습니다. Microsoft Powerpoint와 같은 프레젠테이션 소프트웨어로 만들어진 프리젠테이션에서, 정적 그래픽과 삽화만을 지원하는 데 불편이 있습니다.

전자출판물 형식에서 Powerpoint XML(PPSX)으로의 전환은 이 프리젠테이션의 완전한 잠재력을 끌어내는 데 있어 필수적입니다. 이를 통해 다음 기능을 제공할 수 있습니다:

**사용 사례:**

* **기업 내용 발표**: 정확하고专业한 Powerpoint 프레젠테이션을 만들기 위해 epub파일을 전환하며, 동적인 그래픽과 애니메이션을 포함한 프리젠테이션을 생성할 수 있습니다.
* **학术적 프리젠테이션**: 복잡한 데이터, 예를 들어 연구 결과나 통계 분석을 시각적으로 표현하고 인터랙티브하게 보여주기 위해 PPSX를 사용할 수 있습니다.
* **마케팅 및 판매 자료**: 제품 데모와 고객 테스트imonials 등을 포함한 흥미로운销售 자료를 만들기 위해 epub파일을 전환하며, 손쉽게 클라이언트나 잠재고객에게 공유할 수 있습니다.
* **교육적 프리젠테이션**: 학생들에게 인터랙티브한 프리젠테이션을 제공하고, 멀티 미디어 콘텐츠와 퀴즈, 평가를 포함한 자료를 만들기 위해 PPSX를 사용할 수 있습니다.
* **컨퍼런스 프리젠테이션**: 프로페셔널한 컨퍼런스 프레젠테이션을 만들기 위해 epub파일을 전환하며, 슬라이드 전환, 애니메이션, 그리고 기타 효과를 포함한 프리젠테이션을 생성할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}