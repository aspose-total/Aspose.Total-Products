---
title: PPSX를 WORDML로 변환하는 C++ API
description: C++ 애플리케이션 내에서 PPSX을 WORDML로 내보내기
url: /ko/cpp/conversion/ppsx-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: WORDML
otherformats: ODT WORD RTF DOT TEXT DOCX DOC DOCM OTT DOTX DOTM FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPSX을 WORDML로 렌더링하는 C++ API" h2="Microsoft PowerPoint 또는 Word 종속성 없이 C++ 응용 프로그램에서 PPSX을 WORDML로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)는 C++ 파일 형식 자동화 라이브러리의 완전한 패키지입니다. 패키지에서 사용할 수 있는 API의 풍부한 기능을 사용하여 PowerPoint PPSX을 Word WORDML로 쉽게 변환할 수 있습니다. 변환을 수행하려면 먼저 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API를 사용하여 PPSX를 HTML로 변환할 수 있습니다. 그 후 기능이 풍부한 워드 프로세싱 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)를 사용하여 HTML을 WORDML로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSX를 WORDML로 변환하는 C++ API" %}}
1. [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 클래스 참조를 사용하여 PPSX 파일 로드
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 멤버 기능을 사용하여 PPSX을 HTML로 렌더링하고 Html을 SaveFormat으로 설정합니다.
3. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) 클래스 참조를 이용하여 변환된 HTML 파일을 로드합니다.
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string) 멤버 함수를 사용하여 문서를 WORDML 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Wordmlument
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"htmlOutput.html");
// save wordmlument in WORDML format
wordml->Save(u"output.wordml"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-odt/" name="PPSX 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-word/" name="PPSX 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-rtf/" name="PPSX 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-dot/" name="PPSX 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-text/" name="PPSX 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-wordmlx/" name="PPSX 에게 WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-wordml/" name="PPSX 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-wordmlm/" name="PPSX 에게 WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-ott/" name="PPSX 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-dotx/" name="PPSX 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-dotm/" name="PPSX 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/ppsx-to-flatopc/" name="PPSX 에게 FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}