---
title: CGM을 ODT으로 내보내기 위한 Java API
description: 온프레미스 Java API를 사용하여 CGM을 ODT으로 변환
url_ignore: /ko/java/conversion/cgm-to-odt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODT
otherformats: WORDML PCL MHTML MARKDOWN DOTM XAMLFLOW DOTX FLATOPC PS DOT RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 ODT으로 변환" h2="타사 응용 프로그램을 사용하지 않고 CGM을 ODT으로 렌더링하는 온프레미스 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 사용하여 CGM을 ODT으로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM 파일을 DOC로 렌더링해야 합니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 DOC를 ODT으로 변환할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 ODT으로 변환하는 Java API" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. Aspose.Words의 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOC 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 메소드를 사용하여 문서를 ODT 형식으로 저장하고 ODT 설정 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) pom.xml에 있습니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "cgm-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
CGM을 ODT으로 변환하는 동안 문서가 암호로 보호되어 있더라도 PDF 조작 API[Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/)를 사용하여 문서를 열 수 있습니다. 암호화된 파일을 열기 위해서는 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 객체를 생성하고 소유자의 비밀번호로 CGM을 열어야 합니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 암호로 보호된 CGM 문서 열기" %}}
입력 문서를 ODT 파일 형식으로 저장하는 동안 문서를 파일 시스템 대신 데이터베이스에 저장할 수도 있습니다. 데이터베이스에서 Document 객체를 저장하고 검색하는 것을 구현해야 할 수도 있습니다. 이는 모든 유형의 콘텐츠 관리 시스템을 구현하는 경우에 필요합니다. ODT을 데이터베이스에 저장하려면 바이트 배열을 얻기 위해 문서를 직렬화해야 하는 경우가 많습니다. 이는 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API를 사용하여 수행할 수 있습니다. 바이트 배열을 가져온 후 SQL 문을 사용하여 데이터베이스에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM (Computer Graphics Metafile) 파일을 ODT (OpenDocument Text)로 변환하면 정확한 벡터 그림을 오픈 포맷 문서에 삽입하는 실용적인 방법을 제공합니다. 이를 통해 기술 매뉴얼, 공학 보고서 및 보존 문서에서 고품질 시각 자료를 유지하면서 오픈 소스 편집 도구와의 호환성을 유지할 수 있습니다.

## ✅ 주요 사용 사례
- 내장된 벡터 다이어그램을 사용하여 기술 문서 발행.
- 확장 가능한 그림을 사용하여 유지보수 매뉴얼 작성.
- 오픈 포맷에서 산업 표준 다이어그램 보관.
- 정부 및 기관 문서 작성.
- 벡터 기반 그래픽을 사용한 과학 논문 형식 지정.

## ⚙️ 자동화 시나리오
- 기술 문서 작성을 위한 Java 기반 문서 생성 엔진.
- 벡터 통합을 갖춘 오픈 소스 텍스트 편집기 워크플로우.
- 기술 매뉴얼을 위한 자동 게시 시스템.
- 다이어그램 삽입이 가능한 기업 보고 시스템.
- 버전 관리되는 문서 저장소.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}