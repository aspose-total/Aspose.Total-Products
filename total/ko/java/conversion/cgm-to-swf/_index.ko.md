---
title: Java API를 통해 CGM을 SWF로 변환
description: Microsoft Word를 사용하지 않고 CGM을 SWF로 변환하는 Java API
url_ignore: /ko/java/conversion/cgm-to-swf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SWF
otherformats: POWERPOINT PPTM PPSX POTM XAML PPT PPSM POT POTX OTP PPS SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM을 SWF로 내보내기 위한 Java API" h2="Microsoft<sup>&reg;</sup> PowerPoint 또는 Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 사내 Java API를 통해 CGM을 SWF로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 Java J2SE, J2EE, J2ME 애플리케이션 내에서 CGM을 SWF로 쉽게 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM을 PPTX로 내보낼 수 있습니다. 그 후 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API를 사용하여 PPTX를 SWF로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 SWF로 변환하는 Java API" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 메소드를 사용하여 CGM을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PPTX 문서를 로드합니다.
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 메소드를 사용하여 문서를 SWF 형식으로 저장하고 ` Swf`를 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Java용 Aspose.Slides](https://docs.aspose.com/slides/java/installation/) pom.xml에 있습니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
CGM 파일 형식을 로드하는 동안 문서가 암호로 보호될 수 있습니다. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하면 암호화된 문서도 열 수 있습니다. 암호화된 파일을 열기 위해 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java)의 새 인스턴스를 초기화할 수 있습니다. .lang.String-) 클래스를 만들고 파일 이름과 비밀번호를 인수로 전달합니다.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}https://reference.aspose.com/slides/java/com.aspose.slides/ViewType
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 암호화된 CGM 파일 열기" %}}
CGM을 SWF로 변환한 후 프리젠테이션에 대해 미리 정의된 보기 유형을 추가할 수도 있습니다. [Aspose.Slides for Java](https://products.aspose.com/slides/java/)는 [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) 클래스. [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) 속성은 [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) 열거자. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM을 SWF(Shockwave Flash)로 변환하는 것은 Flash 기반 콘텐츠에 의존하는 레거시 환경에서 필수적입니다. 이 형식은 애니메이션과 상호 작용을 지원하여 오래된 훈련 시뮬레이터, 기술 매뉴얼 및 시각화 도구에 유용합니다.

## ✅ 주요 사용 사례
- **레거시 훈련 시뮬레이터** – 운영자 훈련용 대화식 다이어그램 표시.
- **애니메이션 기술 매뉴얼** – 유지보수 및 운영 안내서에 동작 추가.
- **브라우저 기반 시각화 도구** – Flash 지원 환경에서 벡터 그래픽 제공.

## ⚙️ 자동화 시나리오
- **자바 기반 벡터-플래시 라이브러리** – 레거시 앱을 위해 CGM 그래픽을 SWF로 변환.
- **레거시 렌더링 서비스** – 재설계 없이 기존 플랫폼 지원.
- **e러닝 콘텐츠 이전 도구** – Flash 기반 훈련 과정과의 호환성 유지.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}