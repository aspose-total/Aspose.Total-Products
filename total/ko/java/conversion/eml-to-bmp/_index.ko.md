---
title: Java를 통해 EML을 BMP로 내보내기
description: Microsoft Word 또는 Outlook을 사용하지 않고 EML을 BMP로 변환하는 Java API
url_ignore: /ko/java/conversion/eml-to-bmp/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: BMP
otherformats: MD SVG EMF WORDML TEXT PS TIFF DOT PCL DOC FLATOPC DOCX DOCM DOTM ODT PDF GIF OTT EPUB DOTX XPS JPEG PNG RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EML을 BMP로 렌더링하는 Java API" h2="타사 종속성을 사용하지 않고 사내 Java API를 사용하여 EML을 BMP로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
이메일 변환은 Java 개발자가 [Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 모든 Java J2SE, J2EE, J2ME 애플리케이션에 통합할 수 있는 강력한 기능입니다. 패키지 내에서 두 개의 API를 사용하여 타사 종속성 없이 이메일 EML을 BMP로 변환할 수 있습니다. 먼저 이메일 조작 API[Aspose.Email for Java](https://products.aspose.com/email/java/)를 사용하여 EML 파일 형식을 HTML로 변환할 수 있습니다. 둘째, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 HTML을 BMP로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="이메일을 BMP로 변환하는 방법" %}}
1. [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) 클래스를 사용하여 EML 파일을 엽니다.
2. [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)을 사용하여 EML을 HTML로 변환합니다.)) 방법
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 HTML 로드
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 문서를 BMP 형식으로 저장합니다.)) 메서드 및 BMP를 SaveFormat으로 설정
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 사용해야 합니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-formats-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-summary %}}
```
<h2>✅ 주요 사용 사례</h2>
- **이메일 아카이빙**: 기록을 위해 편집할 수 없는 이메일 스냅샷 저장.
- **법적 증거**: 규정 준수 및 법정 사용을 위해 이메일의 원본 모습 캡처.
- **인쇄용 문서**: 포스터나 물리적 기록을 위해 이메일을 BMP로 변환.
- **그래픽 디자인**: 비트맵 이미지를 필요로 하는 디자인 작업에서 이메일 콘텐츠 사용.

<h2>⚙️ 자동화 시나리오</h2>
- **일괄 이메일 스냅샷**: 여러 EML 파일을 BMP 이미지로 변환.
- **규정 준수 파이프라인**: 모든 기업 이메일을 자동으로 비트맵 형식으로 저장.
- **법의학 아카이빙**: 변경되지 않은 이미지 증거로 이메일 보존.
- **시스템 간 공유**: 이메일 클라이언트를 필요로 하지 않고 일관된 보기 확보.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}