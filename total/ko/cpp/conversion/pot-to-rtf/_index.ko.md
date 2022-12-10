---
title: POT를 RTF로 변환하는 C++ API
description: C++ 애플리케이션 내에서 POT을 RTF로 내보내기

family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: RTF
otherformats: ODT DOCM DOTM FLATOPC WORDML WORD OTT DOTX DOCX TEXT DOC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="POT을 RTF로 렌더링하는 C++ API" h2="Microsoft PowerPoint 또는 Word 종속성 없이 C++ 응용 프로그램에서 POT을 RTF로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)는 C++ 파일 형식 자동화 라이브러리의 완전한 패키지입니다. 패키지에서 사용할 수 있는 API의 풍부한 기능을 사용하여 PowerPoint POT을 Word RTF로 쉽게 변환할 수 있습니다. 변환을 수행하려면 먼저 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API를 사용하여 POT를 HTML로 변환할 수 있습니다. 그 후 기능이 풍부한 워드 프로세싱 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)를 사용하여 HTML을 RTF로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POT를 RTF로 변환하는 C++ API" %}}
1. [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 클래스 참조를 사용하여 POT 파일 로드
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 멤버 기능을 사용하여 POT을 HTML로 렌더링하고 Html을 SaveFormat으로 설정합니다.
3. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument) 클래스 참조를 이용하여 변환된 HTML 파일을 로드합니다.
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string) 멤버 함수를 사용하여 문서를 RTF 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pot");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Rtfument
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"htmlOutput.html");
// save rtfument in RTF format
rtf->Save(u"output.rtf"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-odt/" name="POT 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-rtfm/" name="POT 에게 RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-dotm/" name="POT 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-flatopc/" name="POT 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-wordml/" name="POT 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-word/" name="POT 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-ott/" name="POT 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-dotx/" name="POT 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-rtfx/" name="POT 에게 RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-text/" name="POT 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-rtf/" name="POT 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/pot-to-dot/" name="POT 에게 DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}