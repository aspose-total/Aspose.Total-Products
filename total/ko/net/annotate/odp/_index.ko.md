---
title: ODP 주석을 온라인으로 제거하거나 .NET을 통해 주석을 관리하세요.
description: 무료로 온라인 앱을 통해 ODP 파일의 댓글을 삭제하세요.ODP 파일의 주석을 관리하는 .NET API 코드입니다.

family: total
platformtag: net
feature: Annotate
informat: ODP
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT POL PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="ODP 프레젠테이션 온라인에서 주석 지우기 또는 .NET을 통해 관리" h2="강력한 .NET 기반 ODP 프레젠테이션 주석 유틸리티 애플리케이션을 개발합니다..NET을 통해 ODP 파일의 주석을 관리하기 위한 코드 목록입니다." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="온라인으로 ODP 주석 제거" %}}

1. ODP 파일을 업로드하여 댓글을 삭제하려면 가져오기
1. 주석 앱의 드래그 앤 드롭을 통해 드롭 영역 내부를 클릭하면 됩니다.
1. ODP 파일의 크기와 인터넷 속도에 따라 몇 초 정도 기다립니다.
1. 댓글을 삭제하려면 '삭제' 버튼을 클릭하세요.
1. 즉시 파일을 다운로드하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title=".NET을 통해 ODP 프레젠테이션 주석 제거" %}}

1. .NET 프로젝트에 라이브러리 참조 추가
1. 프레젠테이션 클래스 객체를 통해 ODP 로드
1. Presentation.CommentAuthors를 통해 각 작성자를 반복합니다.
1. Comments.Clear() 메서드를 호출하여 해당 주석을 삭제합니다.
1. 파일을 저장하려면 save 메소드를 호출하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C# 코드: ODP 프레젠테이션에서 주석 및 작성자 삭제" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "delete-all-presentation-comments.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET을 통해 ODP 프레젠테이션 댓글 추가" %}}

1. .NET 프로젝트에 라이브러리 참조 추가
1. 프레젠테이션 클래스 객체를 통해 ODP 로드
1. AddEmptySlide 메서드를 사용하여 빈 슬라이드 추가
1. CommentAuthors.AddAuthor를 사용하여 새 작성자를 추가하세요.
1. 댓글 삽입을 위해 Comments.AddComment와 함께 새 작성자를 사용하세요.
1. 프레젠테이션 저장

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title=".NET 코드: 주석 추가" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-slide-comments.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>.NET을 통해 ODP 문서 주석 애플리케이션 개발</h2>

피드백을 제공하거나, 제안을 하거나, 문서에 대해 다른 사람과 공동 작업을 수행하기 위해 ODP 주석 앱 또는 유틸리티를 개발해야 합니까?[Aspose.Total for .NET](https://products.aspose.com/total/net/)의 하위 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)을 사용하면 모든 .NET 개발자가 문서 주석 애플리케이션 내에 위의 API 코드를 통합할 수 있습니다.강력한 .NET 라이브러리를 사용하면 모든 문서 주석 솔루션을 프로그래밍할 수 있습니다.또한 ODP 형식을 포함하여 널리 사용되는 다양한 형식을 지원할 수 있습니다.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ODP 파일에 주석을 추가하는 .NET 라이브러리" %}}

시스템에 "Aspose.Slides for .NET" 또는 "Aspose.Total for .NET"를 설치하는 세 가지 대체 옵션이 있습니다.귀하의 요구 사항과 유사한 것을 선택하고 단계별 지침을 따르십시오.<br /><br />

- [NuGet 패키지](https://www.nuget.org/packages/Aspose.Slides/)을 설치하세요. [선적 서류 비치](https://docs.aspose.com/slides/net/installation/#method-1-install-or-update-asposeslides-from-the-nuget-package-manager) 보기
- Visual Studio IDE 내에서 [패키지 관리자 콘솔](https://docs.aspose.com/slides/net/installation/#method-2-install-or-update-asposeslides-through-the-package-manager-console)를 사용하여 라이브러리 설치

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}
당사 제품은 완전히 크로스 플랫폼이며 '.NET Standard 2.0' 사양을 따르는 모든 주요 .NET 구현을 지원합니다.<br /><br />

- Microsoft .NET Framework, 초기 2.0 버전부터 시작하여 최신 '.NET Framework 4.8'까지
- .NET Core, 초기 2.0부터 시작하여 최신 '.NET 6'으로 끝남
- 모노 >= 2.6.7
<br /><br />
.NET 코드는 기본 하드웨어나 운영 체제에 의존하지 않고 가상 머신에만 의존하므로 Windows, macOS, Android, iOS 및 Linux용 모든 종류의 소프트웨어를 자유롭게 개발할 수 있습니다.해당 버전의 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin을 설치했는지 확인하세요.<br /><br />
C#, F#, VB.NET 애플리케이션을 만들려면 Microsoft Visual Studio, Xamarin 및 MonoDevelop IDE를 사용하는 것이 좋습니다.
<br /><br />
자세한 내용은 [제품 문서](https://docs.aspose.com/slides/net/system-requirements/)를 참고하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}
ODP (OpenDocument Presentation)은 주로 오픈 소스 오피스 스위트에서 사용되는 프레젠테이션을 만들고 공유하기 위한 오픈 표준 형식입니다. ODP 파일에 주석을 추가하면 플랫폼 간 또는 정부/교육용도에서 협업 및 콘텐츠 유효성 검증을 향상시킬 수 있습니다.

#### 오픈 포맷 프레젠테이션 협업용 ODP 파일 주석:

- **오픈 소스 팀 리뷰**  
  협업 환경에서 슬라이드 콘텐츠 개선, 디자인 문제 또는 누락된 요소에 대한 의견 추가.

- **공공 부문 프레젠테이션 개발**  
  검토 중에 정책 지침, 규정 준수 기준 또는 접근성 요구 사항을 충족시키기 위해 주석 삽입.

- **플랫폼 간 콘텐츠 피드백**  
  다른 오피스 스위트 간의 서식이나 레이아웃 불일치를 식별하기 위해 주석 사용.

- **교육용 슬라이드 피드백**  
  오픈 포맷 프레젠테이션을 사용하여 학술 환경에서 학습자 또는 강사 의견 제공.

- **버전 관리 및 반복적 개발**  
  문서 개정 중 슬라이드 편집 또는 콘텐츠 변경을 강조하여 추적 및 조정을 개선.
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
                          <span itemprop="text">예, 이 코드를 다운로드하여 .NET 기반 문서 주석 애플리케이션 개발 목적으로 활용하실 수 있습니다.이 코드는 백엔드 문서 처리 및 조작 영역에서 프로젝트의 기능을 향상시키는 귀중한 리소스 역할을 할 수 있습니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>이 온라인 문서 주석 앱은 Windows에서만 작동합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Windows, Linux, Mac OS, Android 등 실행되는 운영 체제에 관계없이 모든 장치에서 주석 제거를 위해 문서 주석을 유연하게 시작할 수 있습니다.필요한 것은 최신 웹 브라우저와 활성 인터넷 연결뿐입니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ODP 문서에 주석을 달기 위해 온라인 앱을 사용하는 것이 안전한가요?</b></span>
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
                          <span itemprop="text">온라인 ODP 문서 주석을 위해 Google Chrome, Firefox, Opera 또는 Safari와 같은 최신 웹 브라우저를 사용할 수 있습니다.하지만 데스크톱 애플리케이션을 개발하는 경우 효율적인 관리를 위해 Aspose.Total 문서 처리 API를 사용하는 것이 좋습니다.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}