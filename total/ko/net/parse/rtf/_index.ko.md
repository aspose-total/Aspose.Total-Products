---
title: .NET을 사용하여 온라인으로 RTF 파일에서 텍스트와 이미지를 추출합니다.
description: 온라인 RTF 파일 파서 앱. RTF 문서에서 이미지와 텍스트 콘텐츠를 추출하는 .NET API C# 코드입니다.

family: total
platformtag: net
feature: Parse
informat: RTF
otherformats: Word DOCX DOC DOTX DOT RTF ODT OTT PDF Excel XLS XLSX XLSM XLSB ODS Powerpoint PPT PPTX ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1=".NET을 통해뿐만 아니라 온라인으로 RTF 파일을 구문 분석합니다." h2="강력한 .NET 기반 RTF 문서 파서 유틸리티 애플리케이션을 개발합니다. RTF 문서 텍스트 추출을 위해 나열된 C# 코드입니다." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="온라인 앱을 통해 RTF 문서 구문 분석" %}}

1. RTF 파일을 업로드하여 구문 분석할 수 있습니다.
1. 파서 앱의 드래그 앤 드롭을 통해 드롭 영역 내부를 클릭하여 수행합니다.
1. RTF 파일의 크기와 인터넷 속도에 따라 몇 초 정도 기다립니다.
1. 문서를 구문 분석하려면 '지금 구문 분석' 버튼을 클릭하세요.
1. 즉시 보려면 구문 분석된 파일을 다운로드하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title=".NET을 통해 RTF 파일 구문 분석" %}}

1. .NET 프로젝트에 라이브러리 참조 추가
1. Document 클래스 객체를 사용하여 RTF 파일 로드
1. GetChildNodes()를 사용하여 모든 하위 노드를 가져옵니다.
1. NodeType.Shape를 매개변수로 사용
1. 각 노드를 반복하고 이미지를 저장합니다.
1. 텍스트 추출의 경우 각 페이지를 반복합니다.
1. ExtractPages 메서드 호출
1. Node.ToString 메소드를 사용하여 추출된 파일을 텍스트로 저장

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C# 코드: RTF 문서 이미지 추출" offSpacer="" %}}

{{< gist "aspose-com-gists" "ab98758eea66dd544d4a7964d10ec4fc" "extract-images-from-word-document.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# 코드: RTF 문서 텍스트 추출" offSpacer="" %}}

{{< gist "aspose-com-gists" "ab98758eea66dd544d4a7964d10ec4fc" "extract-text-from-word-document.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}


{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>.NET을 통해 RTF 파일 파서 애플리케이션 개발</h2>

RTF 파서 애플리케이션이나 소프트웨어를 개발해야 합니까?[Aspose.Total for .NET](https://products.aspose.com/total/ko/net/)의 하위 API인 [Aspose.Words for .NET](https://products.aspose.com/words/ko/net/)을 사용하면 모든 .NET 개발자가 문서 파서 애플리케이션 내에 위의 API 코드를 통합할 수 있습니다.강력한 .NET 라이브러리를 사용하면 모든 문서 구문 분석 솔루션을 프로그래밍하여 텍스트는 물론 이미지도 추출할 수 있습니다.또한 RTF 형식을 포함하여 널리 사용되는 다양한 형식을 지원할 수 있습니다.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="파서 애플리케이션용 RTF 파일을 처리하는 .NET 유틸리티" %}}

시스템에 Aspose.Words for .NET 또는 Aspose.Total for .NET를 설치하는 대체 옵션이 있습니다.귀하의 요구 사항과 유사한 것을 선택하고 단계별 지침을 따르십시오.<br /><br />

- [NuGet 패키지](https://www.nuget.org/packages/Aspose.Words/)을 설치하세요. [선적 서류 비치](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget) 보기
- Visual Studio IDE 내에서 [패키지 관리자 콘솔](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console)를 사용하여 라이브러리 설치
- [Windows 설치 프로그램](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer)를 사용하여 직접 라이브러리 설치

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

당사 제품은 완전히 크로스 플랫폼이며 '.NET Standard 2.0' 사양을 따르는 모든 주요 .NET 구현을 지원합니다.<br /><br />

- Microsoft .NET Framework, 초기 2.0 버전부터 시작하여 최신 '.NET Framework 4.8'로 끝납니다.
- .NET Core, 초기 2.0부터 시작하여 최신 '.NET 6'으로 끝남
- 모노 >= 2.6.7
<br /><br />
.NET 코드는 기본 하드웨어나 운영 체제에 의존하지 않고 가상 머신에만 의존하므로 Windows, macOS, Android, iOS 및 Linux용 모든 종류의 소프트웨어를 자유롭게 개발할 수 있습니다.해당 버전의 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin을 설치했는지 확인하세요.<br /><br />
C#, F#, VB.NET 애플리케이션을 만들려면 Microsoft Visual Studio, Xamarin 및 MonoDevelop IDE를 사용하는 것이 좋습니다.
<br /><br />
자세한 내용은 [제품 문서](https://docs.aspose.com/words/net/system-requirements/)를 참고하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}
## .rtf 파일 구문 분석을 위한 사용 사례

- 📄 Rich Text Format 파일에서 서식이 지정된 텍스트 및 기본 이미지 추출.
- 🧾 `.rtf` 문서를 일반 텍스트 또는 웹용 HTML로 변환.
- 📚 레거시 `.rtf` 문서를 현대적인 콘텐츠 시스템으로 이관.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="자주 묻는 질문" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>자주 묻는 질문</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>내 애플리케이션에서 위의 .NET 코드를 사용할 수 있나요?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">예, 이 코드를 다운로드하여 .NET 기반 문서 파서 애플리케이션 개발 목적으로 활용하실 수 있습니다.이 코드는 노드 읽기, 텍스트 및 이미지 추출을 위한 문서 로드 등 백엔드 문서 처리 영역에서 프로젝트의 기능과 성능을 향상시키는 귀중한 리소스 역할을 할 수 있습니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>이 온라인 문서 파서 앱은 Windows에서만 작동합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Windows, Linux, Mac OS, Android 등 실행되는 운영 체제에 관계없이 모든 장치에서 문서 구문 분석을 시작할 수 있는 유연성이 있습니다. 필요한 것은 최신 웹 브라우저와 활성 인터넷 연결뿐입니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>RTF 문서를 구문 분석하기 위해 온라인 앱을 사용하는 것이 안전한가요?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">물론! 당사 서비스를 통해 생성된 출력 파일은 24시간 이내에 당사 서버에서 안전하고 자동으로 제거됩니다.결과적으로 해당 파일과 관련된 표시 링크는 이 기간 이후에는 더 이상 작동하지 않습니다.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>앱을 사용하려면 어떤 브라우저를 사용해야 하나요?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">온라인 RTF 문서 파서에는 Google Chrome, Firefox, Opera 또는 Safari와 같은 최신 웹 브라우저를 사용할 수 있습니다.하지만 데스크톱 애플리케이션을 개발하는 경우 효율적인 관리를 위해 Aspose.Total 문서 처리 API를 사용하는 것이 좋습니다.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}