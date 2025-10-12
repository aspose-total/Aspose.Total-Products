---
title: Java를 통해 OFT을 RTF로 내보내기
description: Microsoft Word 또는 Outlook을 사용하지 않고 OFT을 RTF로 변환하는 Java API
url_ignore: /ko/java/conversion/oft-to-rtf/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: RTF
otherformats: DOC PS SVG PDF FLATOPC WORDML XPS JPEG TEXT DOTM EMF PNG OTT DOCM GIF EPUB PCL MD ODT RTF DOCX TIFF DOTX DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFT을 RTF로 렌더링하는 Java API" h2="타사 종속성을 사용하지 않고 사내 Java API를 사용하여 OFT을 RTF로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
이메일 변환은 Java 개발자가 [Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 모든 Java J2SE, J2EE, J2ME 애플리케이션에 통합할 수 있는 강력한 기능입니다. 패키지 내에서 두 개의 API를 사용하여 타사 종속성 없이 이메일 OFT을 RTF로 변환할 수 있습니다. 먼저 이메일 조작 API[Aspose.Oft for Java](https://products.aspose.com/email/java/)를 사용하여 OFT 파일 형식을 HTML로 변환할 수 있습니다. 둘째, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 HTML을 RTF로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="이메일을 RTF로 변환하는 방법" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 클래스를 사용하여 OFT 파일을 엽니다.
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)을 사용하여 OFT을 HTML로 변환합니다.)) 방법
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 HTML 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 문서를 RTF 형식으로 저장합니다.)) 메서드 및 RTF를 SaveFormat으로 설정
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

**OFT를 RTF로 변환**은 Outlook 템플릿을 **Rich Text Format**으로 내보내어 기본 서식과 레이아웃을 유지하면서 워드 프로세서 간의 넓은 호환성을 보장합니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

* 가벼운, 보편적으로 읽을 수 있는 문서 생성
* 편집 가능한 형식으로 이메일 템플릿 보관
* 문서 및 분석을 위한 텍스트 추출
* 템플릿 콘텐츠의 크로스 플랫폼 호환성
* 모든 텍스트 또는 워드 프로세싱 소프트웨어에서 빠른 편집

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* 간단한 텍스트 재사용을 위한 자동 OFT-to-RTF 변환
* 문서 보관 시스템과의 통합
* 가벼운 콘텐츠 배포 파이프라인
* RTF로의 통신 템플릿 일괄 내보내기
* 레거시 응용 프로그램을 위한 이메일 템플릿 이전

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}