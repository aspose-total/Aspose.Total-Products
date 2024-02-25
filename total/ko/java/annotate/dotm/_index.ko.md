---
title: DOTM 주석을 온라인으로 제거하거나 Java를 통해 주석을 관리하세요.
description: 무료로 온라인 앱을 통해 DOTM 파일의 댓글을 삭제하세요. DOTM 파일의 주석을 관리하는 Java API 코드입니다.

family: total
platformtag: Java
feature: Annotate
informat: DOTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="DOTM 문서 온라인에서 주석 지우기 또는 Java를 통해 관리" h2="강력한 Java 기반 DOTM 문서 주석 유틸리티 애플리케이션을 개발합니다.Java를 통해 DOTM 파일의 주석을 관리하기 위한 코드 목록입니다." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="온라인으로 DOTM 주석 제거" %}}

1. DOTM 파일을 업로드하여 댓글을 삭제하려면 가져오기
1. 주석 앱의 드래그 앤 드롭을 통해 드롭 영역 내부를 클릭하면 됩니다.
1. DOTM 파일의 크기와 인터넷 속도에 따라 몇 초 정도 기다립니다.
1. 댓글을 삭제하려면 '삭제' 버튼을 클릭하세요.
1. 즉시 파일을 다운로드하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 DOTM 문서 주석 제거" %}}

1. Java 프로젝트에 라이브러리 참조 추가
1. Document 클래스 객체를 통해 문서 로드
1. [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) 및 NodeType.COMMENT를 사용하여 모든 노드에서 모든 주석을 가져옵니다.
1. 모든 댓글을 삭제하려면 [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) 메서드를 호출하세요.
1. 파일을 저장하려면 save 메소드를 호출하십시오.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="DOTM 파일에서 주석을 삭제하는 Java의 코드 예" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTM 댓글 회신 제거 및 추가" %}}

1. Java 프로젝트에 라이브러리 참조 추가
1. Document 클래스 객체를 통해 문서 로드
1. getChild를 사용하여 댓글 받기
1. 이 댓글에 지정된 답변을 삭제하려면 [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment)를 사용하세요.
1. 이 댓글에 답글을 추가하려면 [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String)를 사용하세요.
1. 파일을 저장하려면 save 메소드를 호출하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 주석 추가" %}}

1. Java 프로젝트에 라이브러리 참조 추가
1. 문서 클래스 객체 생성
1. [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/)를 사용하여 댓글 작성
1. getParagraphs().add 및 getFirstParagraph().getRuns().add를 사용하세요.
1. 파일을 저장하려면 save 메소드를 호출하세요. with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="DOTM 파일에서 주석 응답을 제거하고 추가하는 Java 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java 코드: 주석 추가" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Java를 통해 DOTM 문서 주석 애플리케이션 개발</h2>

피드백을 제공하거나, 제안을 하거나, 문서에 대해 다른 사람과 공동 작업을 수행하기 위해 DOTM 주석 앱 또는 유틸리티를 개발해야 합니까?[Aspose.Total for Java](https://products.aspose.com/total/java/)의 하위 API인 [Aspose.Words for Java](https://products.aspose.com/words/java/)을 사용하면 모든 Java 개발자가 문서 주석 애플리케이션 내에 위의 API 코드를 통합할 수 있습니다.강력한 Java 라이브러리를 사용하면 모든 문서 주석 솔루션을 프로그래밍할 수 있습니다. 또한 DOTM 형식을 포함하여 널리 사용되는 다양한 형식을 지원할 수 있습니다.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTM 파일에 주석을 추가하는 Java 라이브러리" %}}
시스템에 "[Aspose.Words for Java](https://products.aspose.com/words/java/)" 또는 "[Aspose.Total for Java](https://products.aspose.com/total/java/)"을 설치하는 대체 옵션이 있습니다.우리의 Java 패키지는 크로스 플랫폼으로 설계되었으며 Microsoft Windows, Linux, macOS, Android 및 iOS와 같은 다양한 운영 체제에서 JVM 구현과 호환됩니다. 귀하의 요구 사항과 유사한 것을 선택하고 단계별 지침을 따르십시오.<br />

- [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) 설치
- 아니면 [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/)에서
- 단계별 [지침](https://docs.aspose.com/words/java/installation/#install-aspose-words-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

- Java SE 7 또는 최신 Java 버전
- 오래된 JRE를 사용하는 경우를 대비해 Java SE 6용 별도 패키지입니다.

<br />
JogAmp JOGL, Harfbuzz 글꼴 엔진 및 Java Advanced Imaging JAI 세부 정보는 [제품 문서](https://docs.aspose.com/words/java/system-requirements/#optional-dependencies)을 참조하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


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
                          <span itemprop="name"><b>내 애플리케이션에서 위의 Java 코드를 사용할 수 있나요?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">예, 이 코드를 다운로드하여 Java 기반 문서 주석 애플리케이션 개발 목적으로 활용하실 수 있습니다.이 코드는 백엔드 문서 처리 및 조작 영역에서 프로젝트의 기능을 향상시키는 귀중한 리소스 역할을 할 수 있습니다.</span>
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
                          <span itemprop="name"><b>DOTM 문서에 주석을 달기 위해 온라인 앱을 사용하는 것이 안전한가요?</b></span>
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
                          <span itemprop="text">온라인 DOTM 문서 주석을 위해 Google Chrome, Firefox, Opera 또는 Safari와 같은 최신 웹 브라우저를 사용할 수 있습니다.하지만 데스크톱 애플리케이션을 개발하는 경우 효율적인 관리를 위해 Aspose.Total 문서 처리 API를 사용하는 것이 좋습니다.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}