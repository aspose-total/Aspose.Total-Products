---
title: Java를 통해 OFT을 WORDML로 내보내기
description: Microsoft Word 또는 Outlook을 사용하지 않고 OFT을 WORDML로 변환하는 Java API
url_ignore: /ko/java/conversion/oft-to-wordml/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: WORD_ML
otherformats: RTF MD DOC EPUB PNG TEXT FLATOPC DOTM PS JPEG XPS TIFF ODT SVG PCL DOCX PDF DOCM WORDML DOT GIF OTT DOTX EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFT을 WORDML로 렌더링하는 Java API" h2="타사 종속성을 사용하지 않고 사내 Java API를 사용하여 OFT을 WORDML로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
이메일 변환은 Java 개발자가 [Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 모든 Java J2SE, J2EE, J2ME 애플리케이션에 통합할 수 있는 강력한 기능입니다. 패키지 내에서 두 개의 API를 사용하여 타사 종속성 없이 이메일 OFT을 WORDML로 변환할 수 있습니다. 먼저 이메일 조작 API[Aspose.Oft for Java](https://products.aspose.com/email/java/)를 사용하여 OFT 파일 형식을 HTML로 변환할 수 있습니다. 둘째, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 HTML을 WORDML로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="이메일을 WORDML로 변환하는 방법" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 클래스를 사용하여 OFT 파일을 엽니다.
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)을 사용하여 OFT을 HTML로 변환합니다.)) 방법
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 HTML 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 문서를 WORDML 형식으로 저장합니다.)) 메서드 및 WORDML를 SaveFormat으로 설정
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

**OFT를 WORDML로 변환**은 **아웃룩 템플릿**을 **워드프로세싱ML(XML)** 형식으로 변환하여 개발자, 통합자 및 자동화 시스템을 위한 문서의 구조화된, 마크업 기반 버전을 제공합니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

* XML 기반 처리를 위한 OFT 콘텐츠 구조화
* 웹이나 문서 생성 프레임워크 통합
* 변환 또는 스타일링을 위한 의미론적 요소 추출
* 데이터 주도 조작을 위해 XML에 템플릿 보관
* 워드 호환 XML로 OFT 데이터의 사용자 정의 렌더링

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* 자동화된 OFT-to-WORDML 변환 파이프라인
* XML 기반 문서 템플릿 및 콘텐츠 추출
* REST API 및 문서 서버 통합
* WordprocessingML을 사용한 기업 콘텐츠 모델링
* 구조화된 OFT 데이터로부터 문서의 동적 생성

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}