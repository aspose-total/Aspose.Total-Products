---
title: Java를 통해 OFT을 XPS로 내보내기
description: Microsoft Word 또는 Outlook을 사용하지 않고 OFT을 XPS로 변환하는 Java API
url_ignore: /ko/java/conversion/oft-to-xps/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: XPS
otherformats: PNG TEXT PDF ODT PS DOT TIFF XPS MD FLATOPC RTF EMF PCL JPEG GIF OTT DOTX SVG DOCX DOCM DOTM EPUB WORDML DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFT을 XPS로 렌더링하는 Java API" h2="타사 종속성을 사용하지 않고 사내 Java API를 사용하여 OFT을 XPS로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
이메일 변환은 Java 개발자가 [Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 모든 Java J2SE, J2EE, J2ME 애플리케이션에 통합할 수 있는 강력한 기능입니다. 패키지 내에서 두 개의 API를 사용하여 타사 종속성 없이 이메일 OFT을 XPS로 변환할 수 있습니다. 먼저 이메일 조작 API[Aspose.Oft for Java](https://products.aspose.com/email/java/)를 사용하여 OFT 파일 형식을 HTML로 변환할 수 있습니다. 둘째, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 HTML을 XPS로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="이메일을 XPS로 변환하는 방법" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 클래스를 사용하여 OFT 파일을 엽니다.
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)을 사용하여 OFT을 HTML로 변환합니다.)) 방법
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 HTML 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 문서를 XPS 형식으로 저장합니다.)) 메서드 및 XPS를 SaveFormat으로 설정
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 사용해야 합니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/agp/feature-section >}}

**OFT를 XPS로 변환**하면 **XML Paper Specification 파일**이 생성되어 Outlook 템플릿의 플랫폼 독립적인 고정 레이아웃 문서 표현을 가능하게 하여 보기, 공유 및 인쇄가 가능해집니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

* 다양한 기기 간 템플릿 레이아웃 및 서식 보존
* 이메일 템플릿을 고정 레이아웃 문서로 공유
* 규정 준수 및 기록 보관을 위한 OFT 콘텐츠 아카이빙
* 일관된 외관으로 템플릿 인쇄
* Microsoft Outlook 또는 Word 없이 템플릿 보기

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* 기업 배포를 위한 자동화된 OFT-to-XPS 변환
* 문서 관리 시스템과의 통합
* 이메일 템플릿에서 고정 레이아웃 아카이브의 일괄 생성
* 템플릿의 안전한 공유 및 인쇄를 위한 파이프라인
* Outlook 템플릿 디자인의 장기 보존

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}