---
title: C++를 통해 WORDML를 PPS로 변환 또는 무료 온라인 변환기 사용
description: PowerPoint의 Microsoft Word를 사용하지 않고 C++ 응용 프로그램에서 WORDML를 PPS로 내보내기 또는 온라인. 코드를 통합하기 전에 무료 WORDML to PPS 온라인 변환기를 빠르게 테스트하십시오.

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: PPS
otherformats: PPSM ODP PPTM PPTX POTX PPT POTM POT POWERPOINT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="WORDML를 PPS로 변환하는 C++ API 또는 온라인 앱" h2="Microsoft Word&reg;를 사용하지 않고 C++ 응용 프로그램 내에서 WORDML를 PPS로 내보내기 또는 파워포인트" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)는 두 개의 API를 사용하면서 WORDML에서 PPS로의 변환을 자동화할 수 있는 강력한 파일 자동화 API로 구성되어 있습니다. [Aspose.Words for C++](https://products.aspose.com/words/cpp/)를 사용하여 WORDML를 로드하고 HTML로 변환한 다음 PowerPoint 조작 C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 새 프레젠테이션을 만들고 PPS로 저장합니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++에서 WORDML에서 PPS로 변환" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) 클래스 참조를 사용하여 WORDML 파일을 엽니다.
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_stdbasicostream_saveoptions) 멤버 함수를 사용하여 WORDML를 HTML로 변환
3. 새 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 개체를 초기화합니다.
4. 슬라이드에 도형을 추가하고 거기에 AddTextFrame을 추가합니다.
5. HTML 콘텐츠를 로드하고 프레젠테이션 파일에 작성
6. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 메서드를 사용하여 문서를 PPS 형식으로 저장하고 Pps를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORDML file with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("template.wordml");
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"sourceFile.wordml");
// save the wordmlument in HTML file format
wordml->Save(u"HtmlOutput.HTML");
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>WORDML를 PPS로 변환하는 무료 온라인 변환기</h3>

<iframe title="pps에서 wordml로 변환 온라인 도구" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pps&from=wordml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 암호로 보호된 WORDML 문서 로드" %}}
문서 변환 외에도 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API는 C++ 개발자를 위한 수많은 문서 조작 기능을 허용합니다. Microsoft Word WORDML 파일 형식이 암호로 보호되어 있는 경우에도 API를 사용하여 열 수 있습니다. 암호화된 문서를 로드하기 위해 [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) 개체를 허용하는 특수 생성자 오버로드를 사용할 수 있습니다. 이 개체에는 암호 문자열을 지정하는 Password 속성이 포함되어 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordmlument, the password is passed to the wordmlument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordmlPassword");
// load the wordmlument from the local file system by filename:
SharedPtr<Wordmlument> wordml = MakeObject<Wordmlument>(u"Encrypted.wordml", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 PPS 문서에 주석 추가" %}}
WORDML를 PPS로 저장하는 동안 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)를 사용하여 PPS 문서에 추가 기능을 추가할 수도 있습니다. 예를 들어 프레젠테이션에 주석을 추가할 수 있습니다. 프레젠테이션 슬라이드 주석은 특정 작성자와 연결되어 있습니다. Presentation 클래스는 슬라이드 주석 추가를 담당하는 ICommentAuthorCollection의 작성자 컬렉션을 보유합니다. 각 작성자에 대해 ICommentCollection에 주석 모음이 있습니다.
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>자주 묻는 질문</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>어떻게 WORDML를 PPS 온라인으로 변환할 수 있습니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">위에서 WORDML 변환을 위한 온라인 앱을 찾을 수 있습니다. 변환 프로세스를 시작하려면 WORDML 파일을 드래그 앤 드롭하거나 흰색 영역 내부를 클릭하여 문서를 가져오는 방식으로 WORDML 파일을 추가할 수 있습니다. 파일을 추가했으면 "변환" 버튼을 클릭하기만 하면 됩니다. WORDML에서 PPS로 변환이 완료되면 클릭 한 번으로 변환된 파일을 다운로드할 수 있습니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>WORDML를 변환하는 데 얼마나 걸립니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">이 온라인 변환기의 속도는 변환되는 WORDML 파일의 크기에 크게 좌우됩니다. 작은 WORDML 파일은 단 몇 초 만에 PPS로 변환할 수 있습니다. C++ 애플리케이션 내에서 변환 코드를 사용하는 경우 변환 속도는 애플리케이션을 얼마나 잘 최적화했는지에 따라 달라집니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>무료 Aspose.Total 변환기를 사용하여 WORDML를 PPS로 변환하는 것이 안전합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">물론! 온라인 변환기를 사용하여 WORDML 파일을 PPS로 변환하면 PPS 파일의 다운로드 링크를 즉시 사용할 수 있습니다. 업로드된 파일의 보안 및 개인 정보 보호를 중요하게 생각하며 변환 프로세스가 완료된 후 24시간 후에 삭제합니다. 아무도 귀하의 파일에 액세스할 수 없으므로 안심하십시오. WORDML 변환을 포함한 변환 프로세스는 완전히 안전합니다. 코드를 통합하기 전에 결과를 확인할 수 있도록 테스트 목적으로 무료 앱을 제공합니다.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>WORDML를 변환하려면 어떤 브라우저를 사용해야 합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">온라인 WORDML 변환의 경우 Google Chrome, Firefox, Opera 또는 Safari와 같은 최신 브라우저를 사용할 수 있습니다. 그러나 데스크톱 애플리케이션을 개발하는 경우 원활한 성능을 위해 Aspose.Total WORDML Conversion API를 사용하는 것이 좋습니다.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}