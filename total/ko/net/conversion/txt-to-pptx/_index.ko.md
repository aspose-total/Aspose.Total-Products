---
title: C# .NET을 통해 TXT를 PPTX로 변환 또는 무료 온라인 변환기 사용
description: C#을 사용하여 Word 문서 문서를 PowerPoint pptx 파일로 변환합니다. ASP.NET 또는 기타 .NET 응용 프로그램 내에서 여러 파일을 변환합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C#을 사용하여 TXT를 PPTX로 변환 또는 온라인" h2=".NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 Microsoft Word TXT에서 PowerPoint PPTX로 변환 앱을 빌드하세요." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="C#을 사용하여 TXT를 PPTX로 변환 또는 온라인하는 방법" %}}

Word 문서 파일에서 PowerPoint pptx 프레젠테이션 일괄 변환 프로세스를 자동화하기 위해 [Aspose.Words for .NET](https://products.aspose.com/words/net) 및 [Aspose.Slides .NET](https://products.aspose.com/slides/net) API. 전자는 Microsoft Word 문서를 처리하거나 조작하기 위한 워드 프로세싱 API입니다. 반면 후자는 Microsoft PowerPoint 슬라이드를 만들거나 수정할 수 있는 프레젠테이션 조작 API입니다. 두 API 모두 [.NET용 Aspose.Total](https://products.aspose.com/total/net) 패키지의 일부입니다. Nuget에서 직접 [다운로드](https://releases.aspose.com/)하거나 패키지 관리자 콘솔에서 다음 명령을 사용할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="패키지 관리자 콘솔 명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#을 통해 TXT를 PPTX로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. .NET용 Aspose.Total 참조 추가
1. [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 TXT 파일 로드
1. TXT 문서를 HTML로 저장
1. [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) 객체 생성
1. 프레젠테이션 내부의 모든 슬라이드 모양의 텍스트 프레임에 HTML 콘텐츠 가져오기
1. [Aspose.Slides.Presentation.Save("output.pptx", SaveFormat.Pptx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods를 사용하여 문서 저장 /5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼과 호환되는 OS.
- Microsoft Visual Studio와 같은 개발 환경.
- Aspose.Words for .NET &amp; 프로젝트에서 참조되는 .NET DLL의 경우 Aspose.Slides 또는 .NET DLL의 경우 Aspose.Total입니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 코드 샘플은 C#을 사용하여 TXT를 PPTX로 변환 또는 온라인하는 방법을 보여줍니다." offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word TXT file
Aspose.Words.Document txt = new Aspose.Words.Document("sourceWordFile.txt");

// Save TXT file to HTML 
txt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages TXT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPTX.

using (Presentation pptx = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the PPTX Presentation
	pptx.Save("filepath\\pres.pptx", Aspose.Slides.Export.SaveFormat.Pptx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>TXT에서 PPTX로 온라인 변환기</h3>

<iframe title="pptx에서 txt로 변환 온라인 도구" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pptx&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="TXT를 PPTX로 변환하는 무료 앱" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 TXT 파일을 PPTX로 변환: 사용 사례" %}}
텍스트 파일(.txt)을 파워포인트 프레젠테이션(.pptx)으로 변환하는 것은 귀하의 프레젠테이션 가능성을 극대화할 수 있는 중요한 과정입니다. 이 변환을 통해 다음과 같은 기능을 활용할 수 있습니다:

**사용 케이스:**

* **비즈니스 프레젠테이션:** .txt 파일을 활용하여 인터랙티브한 프레젠테이션을 만들고 복잡한 정보를清명하게 전달하고 관众과 소통할 수 있습니다.
* **연구 및 학문적 프레젠테이션:** 파워포인트를 통해 연구 데이터를 시각화하고 결과를 공유하고 지식을 전달할 수 있습니다.
* **마케팅 및 세일즈 프레젠테이션:** .txt 파일을 활용하여 설득력 있는 프레젠테이션을 만들고 제품或 서비스를展示하고 거래를 진행할 수 있습니다.
* **훈련 및 교육 자료:** 파워포인트를 통해 인터랙티브한 튜토리얼을 만들고 학생들이 복잡한 개념을 안내하고 실습 훈련을 제공할 수 있습니다.
* **내부 통신:** .txt 파일을 활용하여 회사 내부 발표자료를 만들고 소식을 공유하고 팀 내 협업을 이끌을 수 있습니다.

이러한 텍스트 파일을 파워포인트로 변환하면:

* 시각적 콘텐츠에 이미지, 차트, 그래프 등을 추가할 수 있습니다.
* 인터랙티브한 요소，如 하이퍼링크, 애니메이션, 전환 효과를 포함할 수 있습니다.
* 멀티미디어 콘텐츠,如 오디오나 비디오 파일을 포함하여 더 흥미로운 프레젠테이션을 만들 수 있습니다.
* 다양한 포맷으로 프레젠테이션을 내보내기 위해 준비할 수 있습니다.

기억하세요, 텍스트 파일을 파워포인트로 변환하는 것은 효과적인 시각적 커뮤니케이션을 위한 필수적인 단계입니다.
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
                          <span itemprop="name"><b>어떻게 TXT를 PPTX 온라인으로 변환할 수 있습니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">TXT 변환을 위한 온라인 앱은 위에 통합되어 있습니다. 이 앱을 사용하려면 TXT 파일을 지정된 흰색 영역으로 끌어다 놓거나 영역 내부를 클릭하여 문서를 가져오면 됩니다. 그런 다음 변환 버튼을 눌러 변환 프로세스를 시작하십시오. TXT에서 PPTX로 변환이 완료되면 클릭 한 번으로 새로 변환된 파일을 다운로드할 수 있으며 PPTX 파일 형식으로 사용할 수 있습니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>TXT를 변환하는 데 얼마나 걸립니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">이 온라인 변환기는 빠르게 작동하지만 주로 변환 중인 TXT 파일의 크기에 따라 달라집니다. 작은 TXT 파일의 경우 PPTX로의 변환이 몇 초 만에 완료될 수 있습니다. 그러나 변환 코드를 .NET 응용 프로그램에 통합한 경우 변환 속도는 응용 프로그램이 변환 프로세스에 얼마나 잘 최적화되었는지에 따라 달라집니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>무료 Aspose.Total 변환기를 사용하여 TXT를 PPTX로 변환하는 것이 안전합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">물론! TXT에서 PPTX로 변환이 완료되면 새로 변환된 PPTX 파일의 다운로드 링크를 즉시 사용할 수 있습니다. 또한 TXT 파일을 포함하여 업로드된 모든 파일이 완전히 안전하고 24시간 후에 시스템에서 삭제되므로 변환 프로세스의 안전을 보장합니다. 또한 이 기간이 지나면 다운로드 링크 작동이 중지되어 개인 정보와 파일 보호가 보장됩니다. 통합 앱은 무료로 사용할 수 있으며 테스트 목적으로 설계되어 사용자가 코드를 프로젝트에 통합하기 전에 결과를 평가할 수 있습니다.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>TXT를 변환하려면 어떤 브라우저를 사용해야 합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Google Chrome, Firefox, Opera 또는 Safari와 같은 최신 웹 브라우저를 사용하여 온라인 TXT에서 PPTX로 변환할 수 있습니다. 그러나 데스크톱 애플리케이션을 개발하는 경우 원활하고 효율적인 처리를 위해 Aspose.Total TXT Conversion API를 사용하는 것이 좋습니다.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}