---
title: 온라인으로 PPTM 주석을 제거하거나 Android 모바일 앱을 사용하여 주석을 관리하세요.
description: 무료로 온라인 앱을 통해 PPTM 파일의 댓글을 삭제하세요.PPTM 파일의 주석을 관리하는 Android API 코드입니다.

family: total
platformtag: Android
feature: Annotate
informat: PPTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="PPTM 프레젠테이션 온라인에서 댓글 지우기 또는 Android 앱을 통해 관리" h2="강력한 Android 기반 PPTM 프레젠테이션 주석 유틸리티 애플리케이션을 개발합니다.PPTM 파일의 주석을 관리하기 위해 나열된 코드입니다." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="온라인으로 PPTM 주석 제거" %}}

1. PPTM 파일을 업로드하여 댓글을 삭제하려면 가져오기
1. 주석 앱의 드래그 앤 드롭을 통해 드롭 영역 내부를 클릭하면 됩니다.
1. PPTM 파일의 크기와 인터넷 속도에 따라 몇 초 정도 기다립니다.
1. 댓글을 삭제하려면 '삭제' 버튼을 클릭하세요.
1. 즉시 파일을 다운로드하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android 앱을 통해 PPTM 프레젠테이션 댓글 제거" %}}

1. Android 프로젝트에 라이브러리 참조 추가
1. 프레젠테이션 클래스 객체를 통해 PPTM 로드
1. Presentation.getCommentAuthors() 컬렉션을 통해 각 작성자를 반복합니다.
1. 해당 주석을 삭제하려면 clear() 메서드를 호출하세요.
1. 마지막으로 getCommentAuthors().clear()를 호출하여 모든 작성자를 제거합니다.
1. 파일을 저장하려면 save 메소드를 호출하세요.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="코드 : PPTM 프레젠테이션에서 주석 및 작성자 삭제" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Android 앱을 통해 PPTM 프레젠테이션 댓글 추가" %}}

1. Android 프로젝트에 라이브러리 참조 추가
1. 프레젠테이션 클래스 객체를 통해 PPTM 로드
1. 작성자를 추가하려면 Presentation.getCommentAuthors().addAuthor(String, String)를 호출하세요.
1. 코멘트 추가를 위해 ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date) 사용
1. 파일을 저장하려면 save 메소드를 호출하세요. with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="코드: 주석 추가" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>PPTM 문서 주석 Android 앱 개발</h2>

피드백을 제공하거나, 제안을 하거나, 문서에 대해 다른 사람과 협력하기 위해 PPTM 주석 모바일 앱 또는 유틸리티를 개발해야 합니까?[Aspose.Total for Android via Java](https://products.aspose.com/total/ko/android-java/)의 하위 API인 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/ko/android-java/)을 사용하면 모든 안드로이드 개발자가 문서 주석 애플리케이션 내에 위의 API 코드를 통합할 수 있습니다.강력한 안드로이드 라이브러리를 사용하면 모든 문서 주석 솔루션을 프로그래밍할 수 있습니다.또한 PPTM 형식을 포함하여 널리 사용되는 다양한 형식을 지원할 수 있습니다.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPTM 파일에 주석을 추가하는 Android 라이브러리" %}}

- 우리는 Java 패키지를 [메이븐 저장소](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/)로 호스팅합니다. 
- Aspose.Slides for Java는 바이트 코드를 포함하는 일반적인 JAR 파일입니다.
- Aspose.Slides for Android via Java 설치 방법은 [단계별 지침](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository)를 따르세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

- J2SE 6.0(Java 1.6) 이상
- Java 패키지는 크로스 플랫폼이며 JVM 구현을 통해 모든 운영 체제에서 실행됩니다.

<br />
자세한 내용은 [제품 문서](https://docs.aspose.com/slides/java/system-requirements/)를 참고하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}