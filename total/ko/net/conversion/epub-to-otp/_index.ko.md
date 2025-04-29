---
title: C# API를 통해 EPUB을 OTP로 내보내기
description: Microsoft Word를 사용하지 않고 EPUB을 OTP로 변환하는 .NET API
url_ignore: /ko/net/conversion/epub-to-otp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTP
otherformats: OTP PPSX PPSM POTM POWERPOINT PPS POTX XAML SWF PPT PPTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 EPUB을 OTP로 렌더링" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 Windows, macOS 및 Linux에서 EPUB을 OTP로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
강력한 파일 형식 자동화 API [Aspose.Total for .NET](https://products.aspose.com/total/net/) 패키지를 사용하면 간단한 두 단계로 EPUB을 OTP로 쉽게 렌더링할 수 있습니다. PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 EPUB 파일 형식을 PPTX로 변환할 수 있습니다. 그 후 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)를 사용하여 PPTX를 OTP로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB을 OTP로 변환하는 .NET API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 EPUB 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 EPUB을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 클래스를 이용하여 PPTX 파일 불러오기
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 메서드를 사용하여 문서를 OTP 형식으로 저장하고 'Otp'를 SaveFormat으로 설정합니다.
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
EPUB을 OTP로 변환하는 동안 일괄 변환 프로세스의 우선 순위를 지정하기 위해 추가 XMP 메타데이터 정보가 필요할 수 있습니다. 예를 들어 생성 날짜를 기준으로 변환 문서를 가져와 정렬하고 그에 따라 문서를 처리할 수 있습니다. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)에서는 EPUB 파일의 XMP 메타데이터에 액세스할 수 있습니다. EPUB 파일의 메타데이터를 얻으려면 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 개체를 생성하고 입력된 EPUB 파일을 열 수 있습니다. 이후 [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 속성을 통해 파일의 메타데이터를 얻을 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 OTP 파일 생성" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API를 사용하면 변환 애플리케이션의 기능을 더욱 향상시킬 수 있습니다. 기능 중 하나는 보안을 강화하기 위해 출력 파일을 읽기 전용으로 만드는 것입니다. API를 사용하면 OTP 파일을 읽기 전용으로 설정할 수 있습니다. 즉, 프레젠테이션을 연 후 사용자에게 읽기 전용 권장 사항이 표시됩니다. 
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EPUB 파일을 OTP로 변환: 사용 사례" %}}
이북(전자책) 파일은 디지털 콘텐츠를 저장하는 데 사용됩니다. 이들은 δυνα미콘텐츠와 인터렉티브한 경험을 창출하기 위해 이상적이라고 할 수 있습니다.

그러나 오프라인 데이터를 작업할 때, 텍스트 파일은 장기적인 저장과 아카이브 목적에 필수적입니다.

이북 파일을 오프라인 텍스트 파일로 변환하는 것은 당신의 아카이브와 라이브러리 기능을 최대한 활용할 수 있도록 합니다. 이 변환을 통해 다음을 할 수 있습니다:

**사용 사례:**

* **디지털 보존:** 영구적인 아카이브를 만들고, 시간에 따라 접근할 수 있는 디지털 콘텐츠를 보장합니다.
* **오프라인 읽기 및 공유:** 인터넷 연결 없이도 콘텐츠를 분배하고, 제한된 지역에서도 사용할 수 있습니다.
* **라이브러리 관리 및 조직:** 텍스트 데이터를 조직ized하고, 특정 정보를 검색하고 회득할 수 있도록 합니다.
* **디지털 아카이브 복원 및 복구:** 손상된 콘텐츠를 저장하고, 미래 세代에게 전달할 수 있습니다.
* **오프라인 콘텐츠 창작 및 편집:** 인터넷 연결 없이도 편집하고, 작가나 작가자와 출판사에게 유용합니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}