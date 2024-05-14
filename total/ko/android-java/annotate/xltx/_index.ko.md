---
title: 온라인으로 XLTX 주석을 제거하거나 Android 모바일 앱을 사용하여 주석을 관리하세요.
description: 무료로 온라인 앱을 통해 XLTX 파일의 댓글을 삭제하세요.XLTX 파일의 주석을 관리하는 Android API 코드입니다.

family: total
platformtag: Android
feature: Annotate
informat: XLTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="XLTX 문서 온라인에서 댓글 지우기 또는 Android 앱을 통해 관리" h2="강력한 Android 기반 XLTX 문서 주석 유틸리티 애플리케이션을 개발합니다.XLTX 파일의 주석을 관리하기 위해 나열된 코드입니다." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="온라인으로 XLTX 주석 제거" %}}

1. XLTX 파일을 업로드하여 댓글을 삭제하려면 가져오기
1. 주석 앱의 드래그 앤 드롭을 통해 드롭 영역 내부를 클릭하면 됩니다.
1. XLTX 파일의 크기와 인터넷 속도에 따라 몇 초 정도 기다립니다.
1. 댓글을 삭제하려면 '삭제' 버튼을 클릭하세요.
1. 즉시 파일을 다운로드하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android 앱 API를 통해 XLTX 문서 주석 제거" %}}

1. Android 프로젝트에 라이브러리 참조 추가
1. Workbook 클래스 개체를 통해 문서 로드
1. 특정 워크시트를 선택하세요.
1. [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)를 사용하여 모든 의견을 가져옵니다.
1. getThreadedComments를 통해 모든 스레드 댓글을 가져옵니다.
1. 댓글과 작성자를 각각 제거하려면 RemoveAt를 사용하세요.
1. 파일을 저장하려면 save 메소드를 호출하세요.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="코드 : XLTX 문서에서 주석 제거" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="스레드된 XLTX 주석 업데이트" %}}

1. Workbook 클래스 개체를 통해 문서 로드
1. 특정 워크시트 가져오기
1. getComments().getThreadedComments(Index).get(Index)를 사용하여 스레드 주석 가져오기
1. setNotes 방법을 사용하여 주석 업데이트
1. 파일을 저장하려면 save 메소드를 호출하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android 앱 API를 통해 댓글 추가" %}}

1. 통합 문서 클래스 개체를 통해 문서 만들기
1. 특정 워크시트 가져오기
1. getComments().add을 통해 댓글 색인 추가
1. setNotes 메소드를 사용하여 주석 추가
1. 파일을 저장하려면 save 메소드를 호출하세요. with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="코드: XLTX 파일의 스레드 주석 업데이트" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="코드: 주석 추가" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>XLTX 문서 주석 Android 앱 개발</h2>

피드백을 제공하거나, 제안을 하거나, 문서에 대해 다른 사람과 공동 작업하기 위해 Android 기반 XLTX 주석 앱 또는 유틸리티를 개발해야 합니까?[Aspose.Total for Android via Java](https://products.aspose.com/total/ko/android-java/)의 하위 API인 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/ko/android-java/)을 사용하면 모든 안드로이드 개발자가 위의 API 코드를 문서 주석 애플리케이션에 통합할 수 있습니다.강력한 안드로이드 라이브러리를 사용하면 모든 문서 주석 솔루션을 프로그래밍할 수 있습니다.또한 XLTX 형식을 포함하여 널리 사용되는 다양한 형식을 지원할 수 있습니다.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLTX 파일에 주석을 추가하는 Android API" %}}

- 우리는 Java 패키지를 [메이븐 저장소](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/)로 호스팅합니다. 
- Aspose.Cells for Java는 바이트 코드를 포함하는 일반적인 JAR 파일입니다.
- Aspose.Cells for Android via Java 설치 방법은 [단계별 지침](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository)를 따르세요.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

- 안드로이드 OS 2.0 이상.
- Java 패키지는 크로스 플랫폼이며 JVM 구현을 통해 모든 운영 체제에서 실행됩니다.

<br />
자세한 내용은 [제품 문서](https://docs.aspose.com/cells/java/system-requirements/)를 참고하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}