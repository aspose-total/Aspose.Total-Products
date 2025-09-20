---
title: Java API를 통해 EPUB을 POTM로 변환
description: Microsoft Word를 사용하지 않고 EPUB을 POTM로 변환하는 Java API
url_ignore: /ko/java/conversion/epub-to-potm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: POTM
otherformats: PPTM OTP PPT PPSM SWF XAML POTM POWERPOINT POT POTX PPSX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EPUB을 POTM로 내보내기 위한 Java API" h2="Microsoft<sup>&reg;</sup> PowerPoint 또는 Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 사내 Java API를 통해 EPUB을 POTM로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 Java J2SE, J2EE, J2ME 애플리케이션 내에서 EPUB을 POTM로 쉽게 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 EPUB을 PPTX로 내보낼 수 있습니다. 그 후 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API를 사용하여 PPTX를 POTM로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB을 POTM로 변환하는 Java API" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 EPUB 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 메소드를 사용하여 EPUB을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPTX 문서를 로드합니다.
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 메소드를 사용하여 문서를 POTM 형식으로 저장하고 ` Potm`를 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Java용 Aspose.Slides](https://docs.aspose.com/slides/java/installation/) pom.xml에 있습니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
EPUB 파일 형식을 로드하는 동안 문서가 암호로 보호될 수 있습니다. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하면 암호화된 문서도 열 수 있습니다. 암호화된 파일을 열기 위해 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java)의 새 인스턴스를 초기화할 수 있습니다. .lang.String-) 클래스를 만들고 파일 이름과 비밀번호를 인수로 전달합니다.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}https://reference.aspose.com/slides/java/com.aspose.slides/ViewType
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 암호화된 EPUB 파일 열기" %}}
EPUB을 POTM로 변환한 후 프리젠테이션에 대해 미리 정의된 보기 유형을 추가할 수도 있습니다. [Aspose.Slides for Java](https://products.aspose.com/slides/java/)는 [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) 클래스. [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) 속성은 [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) 열거자. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
EPUB을 POTM(매크로 활성화 PowerPoint 템플릿)으로 변환하는 것은 eBook에서 자동화된 **대화형 템플릿을 생성**하기 위해 필수적입니다. POTM 파일은 포함된 매크로를 가진 재사용 가능한 슬라이드를 가능하게 하며 자동화된 워크플로우, 동적 콘텐츠 업데이트 및 대화형 기능을 제공합니다. EPUB을 POTM으로 변환함으로써 교육자, 출판사 및 기업은 생산성을 향상시키고 슬라이드 디자인을 표준화하며 교육 및 보고 프로세스를 간소화하는 지능적인 프레젠테이션을 만들 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}
- **자동화된 학술 프레젠테이션** - 사전 구성된 대화형 요소를 포함한 강의 슬라이드 생성.
- **기업 슬라이드 자동화** - 내부 프레젠테이션 워크플로우를 표준화하고 자동화.
- **매크로를 활용한 출판 워크플로우** - 프레젠테이션 템플릿에서 콘텐츠 업데이트를 간소화하기 위해 매크로 삽입.
- **연구 프레임워크** - 학술적 콘텐츠를 대화형 매크로 슬라이드로 변환.
- **기업 규모의 교육 템플릿** - 팀 간에 재사용 가능하고 자동화된 교육 프레젠테이션 제공.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}
- **EPUB에서 POTM으로의 파이프라인** - eBook을 매크로 활성화된 프레젠테이션 템플릿으로 자동 변환.
- **매크로 활성화된 프레젠테이션 자동화** - 슬라이드에 동적 콘텐츠와 상호 작용성 통합.
- **메타데이터 기반 슬라이드 템플릿** - 구조화된 eBook 데이터를 사용하여 프레젠테이션 콘텐츠를 자동으로 채우기.
- **대규모 출판 템플릿 생성** - 기업이나 교육 기관을 위한 대규모 대화형 슬라이드 템플릿 생성.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}