---
title: Java API를 통해 PS을 POTX로 변환
description: Microsoft Word를 사용하지 않고 PS을 POTX로 변환하는 Java API
url_ignore: /ko/java/conversion/ps-to-potx/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POTX
otherformats: PPTM POWERPOINT POT PPSM POTX PPSX PPS PPT POTM OTP XAML SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PS을 POTX로 내보내기 위한 Java API" h2="Microsoft<sup>&reg;</sup> PowerPoint 또는 Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 사내 Java API를 통해 PS을 POTX로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 Java J2SE, J2EE, J2ME 애플리케이션 내에서 PS을 POTX로 쉽게 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 PS을 PPTX로 내보낼 수 있습니다. 그 후 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API를 사용하여 PPTX를 POTX로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS을 POTX로 변환하는 Java API" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 PS 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 메소드를 사용하여 PS을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPTX 문서를 로드합니다.
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 메소드를 사용하여 문서를 POTX 형식으로 저장하고 ` Potx`를 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Java용 Aspose.Slides](https://docs.aspose.com/slides/java/installation/) pom.xml에 있습니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
PS 파일 형식을 로드하는 동안 문서가 암호로 보호될 수 있습니다. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하면 암호화된 문서도 열 수 있습니다. 암호화된 파일을 열기 위해 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java)의 새 인스턴스를 초기화할 수 있습니다. .lang.String-) 클래스를 만들고 파일 이름과 비밀번호를 인수로 전달합니다.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}https://reference.aspose.com/slides/java/com.aspose.slides/ViewType
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 암호화된 PS 파일 열기" %}}
PS을 POTX로 변환한 후 프리젠테이션에 대해 미리 정의된 보기 유형을 추가할 수도 있습니다. [Aspose.Slides for Java](https://products.aspose.com/slides/java/)는 [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) 클래스. [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) 속성은 [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) 열거자. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

PS (PostScript) 파일을 POTX (매크로 없는 PowerPoint 템플릿)으로 변환하면 팀이 매크로 보안 위험을 피하면서 깨끗하고 재사용 가능한 프레젠테이션 템플릿을 만들 수 있습니다. POTX는 PS 디자인과 레이아웃을 안전한 템플릿 형식으로 보존합니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

* PS 슬라이드를 재사용 가능한 매크로 없는 템플릿으로 변환하기.
* 교육용이나 교육용 프레젠테이션을 표준화하기.
* PS 마케팅 시각 자료를 일관된 브랜딩을 위해 PowerPoint으로 이전하기.
* 자동화 우려 없이 전문적인 슬라이드 템플릿 준비하기.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* 템플릿 라이브러리를 위한 자동화된 PS-to-POTX 일괄 변환.
* 기업 프레젠테이션 관리 시스템 통합.
* PS 파일로부터 프레젠테이션 템플릿의 예약된 업데이트.
* PS 콘텐츠로부터 AI 지원 레이아웃 최적화 및 슬라이드 추출.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}