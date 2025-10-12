---
title: Java를 통해 OFT을 DOCM로 내보내기
description: Microsoft Word 또는 Outlook을 사용하지 않고 OFT을 DOCM로 변환하는 Java API
url_ignore: /ko/java/conversion/oft-to-docm/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: DOCM
otherformats: PS DOCM EPUB DOC TEXT JPEG GIF RTF MD DOTX ODT TIFF OTT PNG PDF WORDML DOCX DOTM SVG DOT EMF FLATOPC PCL XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFT을 DOCM로 렌더링하는 Java API" h2="타사 종속성을 사용하지 않고 사내 Java API를 사용하여 OFT을 DOCM로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
이메일 변환은 Java 개발자가 [Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 모든 Java J2SE, J2EE, J2ME 애플리케이션에 통합할 수 있는 강력한 기능입니다. 패키지 내에서 두 개의 API를 사용하여 타사 종속성 없이 이메일 OFT을 DOCM로 변환할 수 있습니다. 먼저 이메일 조작 API[Aspose.Oft for Java](https://products.aspose.com/email/java/)를 사용하여 OFT 파일 형식을 HTML로 변환할 수 있습니다. 둘째, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 HTML을 DOCM로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="이메일을 DOCM로 변환하는 방법" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 클래스를 사용하여 OFT 파일을 엽니다.
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)을 사용하여 OFT을 HTML로 변환합니다.)) 방법
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 HTML 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 문서를 DOCM 형식으로 저장합니다.)) 메서드 및 DOCM를 SaveFormat으로 설정
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

**OFT를 DOCM으로 변환**하면 Outlook 템플릿을 **매크로가 활성화된 Word 문서**로 변환할 수 있어서 자동화 스크립트나 포함된 작업을 사용하여 콘텐츠를 동적으로 처리, 개인화 또는 배포할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

* 이메일 기반 문서에 자동화 매크로 추가
* 문서 자동화를 위한 템플릿 기반 워크플로 활성화
* 기업용 OFT 템플릿을 대화형 DOCM 양식으로 변환
* CRM이나 데이터베이스에서 동적 데이터 채우기
* 반복 보고서나 알림의 간소화된 생성

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* 포함된 VBA 매크로로 자동 OFT-to-DOCM 변환
* 변환 후 Word 매크로를 트리거하는 워크플로 시스템
* 이메일 기반 문서 조립 파이프라인
* 표준화된 통신을 위한 매크로 기반 콘텐츠 유효성 검사
* 반복되는 이메일 템플릿에서 자동 보고서 생성

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}