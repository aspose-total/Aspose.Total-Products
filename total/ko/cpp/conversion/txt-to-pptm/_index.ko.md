---
title: C++를 통해 TXT를 PPTM로 변환 또는 무료 온라인 변환기 사용
description: PowerPoint의 Microsoft Word를 사용하지 않고 C++ 응용 프로그램에서 TXT를 PPTM로 내보내기 또는 온라인. 코드를 통합하기 전에 무료 POT to CSV 온라인 변환기를 빠르게 테스트하십시오.

family: total
platformtag: cpp
feature: conversion
informat: TXT
outformat: PPTM
otherformats: PPT ODP PPS POWERPOINT PPSM POT PPTX PPSX POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="TXT를 PPTM로 변환하는 C++ API 또는 온라인" h2="Microsoft Word&reg;를 사용하지 않고 C++ 응용 프로그램 내에서 TXT를 PPTM로 내보내기 또는 파워포인트" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)는 두 개의 API를 사용하면서 TXT에서 PPTM로의 변환을 자동화할 수 있는 강력한 파일 자동화 API로 구성되어 있습니다. [Aspose.Words for C++](https://products.aspose.com/words/cpp/)를 사용하여 TXT를 로드하고 HTML로 변환한 다음 PowerPoint 조작 C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 새 프레젠테이션을 만들고 PPTM로 저장합니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++에서 TXT에서 PPTM로 변환" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.txtument) 클래스 참조를 사용하여 TXT 파일을 엽니다.
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.txtument#save_stdbasicostream_saveoptions) 멤버 함수를 사용하여 TXT를 HTML로 변환
3. 새 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 개체를 초기화합니다.
4. 슬라이드에 도형을 추가하고 거기에 AddTextFrame을 추가합니다.
5. HTML 콘텐츠를 로드하고 프레젠테이션 파일에 작성
6. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 메서드를 사용하여 문서를 PPTM 형식으로 저장하고 Pptm를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TXT file with an instance of Txtument
Txtument txtument = new Txtument("template.txt");
System::SharedPtr<Txtument> txt = System::MakeObject<Txtument>(u"sourceFile.txt");
// save the txtument in HTML file format
txt->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>TXT를 PPTM로 변환하는 무료 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptm&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 암호로 보호된 TXT 문서 로드" %}}
문서 변환 외에도 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API는 C++ 개발자를 위한 수많은 문서 조작 기능을 허용합니다. Microsoft Word TXT 파일 형식이 암호로 보호되어 있는 경우에도 API를 사용하여 열 수 있습니다. 암호화된 문서를 로드하기 위해 [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) 개체를 허용하는 특수 생성자 오버로드를 사용할 수 있습니다. 이 개체에는 암호 문자열을 지정하는 Password 속성이 포함되어 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected txtument, the password is passed to the txtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"txtPassword");
// load the txtument from the local file system by filename:
SharedPtr<Txtument> txt = MakeObject<Txtument>(u"Encrypted.txt", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 PPTM 문서에 주석 추가" %}}
TXT를 PPTM로 저장하는 동안 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)를 사용하여 PPTM 문서에 추가 기능을 추가할 수도 있습니다. 예를 들어 프레젠테이션에 주석을 추가할 수 있습니다. 프레젠테이션 슬라이드 주석은 특정 작성자와 연결되어 있습니다. Presentation 클래스는 슬라이드 주석 추가를 담당하는 ICommentAuthorCollection의 작성자 컬렉션을 보유합니다. 각 작성자에 대해 ICommentCollection에 주석 모음이 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-ppt/" name="TXT 에게 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-pptm/" name="TXT 에게 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-pps/" name="TXT 에게 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-powerpoint/" name="TXT 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-ppsm/" name="TXT 에게 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-pot/" name="TXT 에게 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-pptx/" name="TXT 에게 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-ppsx/" name="TXT 에게 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-potx/" name="TXT 에게 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/txt-to-potm/" name="TXT 에게 POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}