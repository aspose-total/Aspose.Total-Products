---
title: Java를 통해 OFT을 TEXT로 내보내기
description: Microsoft Word 또는 Outlook을 사용하지 않고 OFT을 TEXT로 변환하는 Java API
url_ignore: /ko/java/conversion/oft-to-text/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: TEXT
otherformats: WORDML DOTX SVG DOCM RTF MD TIFF TEXT XPS GIF PDF OTT DOT DOCX EMF EPUB JPEG ODT DOTM PNG DOC PCL FLATOPC PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFT을 TEXT로 렌더링하는 Java API" h2="타사 종속성을 사용하지 않고 사내 Java API를 사용하여 OFT을 TEXT로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
이메일 변환은 Java 개발자가 [Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 모든 Java J2SE, J2EE, J2ME 애플리케이션에 통합할 수 있는 강력한 기능입니다. 패키지 내에서 두 개의 API를 사용하여 타사 종속성 없이 이메일 OFT을 TEXT로 변환할 수 있습니다. 먼저 이메일 조작 API[Aspose.Oft for Java](https://products.aspose.com/email/java/)를 사용하여 OFT 파일 형식을 HTML로 변환할 수 있습니다. 둘째, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 HTML을 TEXT로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="이메일을 TEXT로 변환하는 방법" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 클래스를 사용하여 OFT 파일을 엽니다.
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)을 사용하여 OFT을 HTML로 변환합니다.)) 방법
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 HTML 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 문서를 TEXT 형식으로 저장합니다.)) 메서드 및 TEXT를 SaveFormat으로 설정
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

**OFT를 TEXT로 변환**하면 **Outlook 템플릿**에서 일반 텍스트 콘텐츠를 추출하여 형식을 모두 제거하여 원시 콘텐츠 분석, 기록 또는 데이터베이스 삽입에 사용할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

* 이메일 텍스트 분석을 위한 콘텐츠 추출
* 자동화 스크립트용 평문 템플릿 준비
* 텍스트 데이터베이스에 통신 콘텐츠 저장
* 템플릿 콘텐츠의 SEO 및 NLP 전처리
* 대량 OFT 파일로부터 데이터 정리 또는 색인

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* OFT 저장소에서 대량 텍스트 추출
* 기계 학습 텍스트 파이프라인과 통합
* 자동 구문 분석 및 콘텐츠 변환
* 검색 가능한 아카이브용 워크플로 통합
* 텍스트 전용 콘텐츠 저장소 생성

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}