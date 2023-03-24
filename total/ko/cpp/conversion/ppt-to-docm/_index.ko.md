---
title: PPT를 DOCM로 변환하는 C++ API 또는 무료 온라인 변환기 사용
description: C++ 애플리케이션 내에서 PPT을 DOCM로 내보내기 또는 온라인. 코드를 통합하기 전에 무료 POT to CSV 온라인 변환기를 빠르게 테스트하십시오.

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOCM
otherformats: ODT FLATOPC DOCX DOT DOC OTT DOTM DOTX TEXT WORDML WORD RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPT을 DOCM로 렌더링하는 C++ API 또는 온라인 앱" h2="Microsoft PowerPoint 또는 Word 종속성 없이 C++ 응용 프로그램에서 PPT을 DOCM로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)는 C++ 파일 형식 자동화 라이브러리의 완전한 패키지입니다. 패키지에서 사용할 수 있는 API의 풍부한 기능을 사용하여 PowerPoint PPT을 Word DOCM로 쉽게 변환할 수 있습니다. 변환을 수행하려면 먼저 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API를 사용하여 PPT를 HTML로 변환할 수 있습니다. 그 후 기능이 풍부한 워드 프로세싱 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)를 사용하여 HTML을 DOCM로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPT를 DOCM로 변환하는 C++ API" %}}
1. [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 클래스 참조를 사용하여 PPT 파일 로드
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 멤버 기능을 사용하여 PPT을 HTML로 렌더링하고 Html을 SaveFormat으로 설정합니다.
3. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument) 클래스 참조를 이용하여 변환된 HTML 파일을 로드합니다.
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string) 멤버 함수를 사용하여 문서를 DOCM 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"htmlOutput.html");
// save docmument in DOCM format
docm->Save(u"output.docm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>PPT를 DOCM로 변환하는 무료 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docm&from=ppt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}