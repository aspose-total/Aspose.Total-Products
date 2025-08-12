---
title: CGM을 FLATOPC으로 내보내기 위한 Java API
description: 온프레미스 Java API를 사용하여 CGM을 FLATOPC으로 변환
url_ignore: /ko/java/conversion/cgm-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: FLAT_OPC
otherformats: PCL MARKDOWN MHTML RTF DOTM FLATOPC XAMLFLOW DOT ODT DOTX PS OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 FLATOPC으로 변환" h2="타사 응용 프로그램을 사용하지 않고 CGM을 FLATOPC으로 렌더링하는 온프레미스 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 사용하여 CGM을 FLATOPC으로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM 파일을 DOC로 렌더링해야 합니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 DOC를 FLATOPC으로 변환할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 FLATOPC으로 변환하는 Java API" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. Aspose.Words의 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOC 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 메소드를 사용하여 문서를 FLATOPC 형식으로 저장하고 FLATOPC 설정 SaveFormat으로
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
CGM을 FLATOPC으로 변환하는 동안 문서가 암호로 보호되어 있더라도 PDF 조작 API[Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/)를 사용하여 문서를 열 수 있습니다. 암호화된 파일을 열기 위해서는 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 객체를 생성하고 소유자의 비밀번호로 CGM을 열어야 합니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 암호로 보호된 CGM 문서 열기" %}}
입력 문서를 FLATOPC 파일 형식으로 저장하는 동안 문서를 파일 시스템 대신 데이터베이스에 저장할 수도 있습니다. 데이터베이스에서 Document 객체를 저장하고 검색하는 것을 구현해야 할 수도 있습니다. 이는 모든 유형의 콘텐츠 관리 시스템을 구현하는 경우에 필요합니다. FLATOPC을 데이터베이스에 저장하려면 바이트 배열을 얻기 위해 문서를 직렬화해야 하는 경우가 많습니다. 이는 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API를 사용하여 수행할 수 있습니다. 바이트 배열을 가져온 후 SQL 문을 사용하여 데이터베이스에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
**컴퓨터 그래픽 메타파일 (CGM)** 파일을 **플랫 OPC (플랫 XML 기반 오픈 패키징 규약)** 형식으로 변환하는 것은 **자바 기반 오피스 문서 조작** 작업을 수행하는 개발자들에게 매우 유익합니다. 플랫 OPC는 워드, 엑셀 또는 파워포인트 콘텐츠를 단일, 잘 구조화된 XML 파일로 저장하여 문서 요소를 검사, 수정 및 유효성 검사하기 쉽게 만듭니다. CGM 다이어그램을 플랫 OPC 표현으로 변환함으로써 엔지니어링 팀은 벡터 그래픽을 XML 기반 오피스 문서에 직접 통합하여 감사, 규정 준수 확인 및 자바 애플리케이션에서의 자동 처리를 위해 사용할 수 있습니다.

## ✅ 주요 사용 사례

- **XML 문서 검사**  
  XML 도구를 사용하여 CGM이 포함된 문서를 Flat OPC로 변환하여 쉽게 분석하고 문제 해결할 수 있습니다.

- **Java DOM/SAX 파서를 통한 문서 편집**  
  Java에서 프로그래밍 방식으로 문서 구조 및 포함된 CGM 그래픽을 조작할 수 있습니다.

- **공학 프로세스에서의 콘텐츠 감사**  
  투명한 XML 형식에서 CGM이 통합된 문서를 검토하여 정확성과 규정 준수를 보장할 수 있습니다.

## ⚙️ 자동화 시나리오

- **docx4j 통합**  
  **docx4j**를 사용하여 CGM이 향상된 오피스 파일을 플랫 OPC XML로 변환하여 직접 자바 기반 조작을 수행할 수 있습니다.

- **JAXB 기반 XML 처리**  
  JAXB를 사용하여 Flat OPC 콘텐츠를 구문 분석하고 변환하여 고급 문서 편집 또는 유효성 검사 작업을 수행할 수 있습니다.

- **Spring 기반 XML 서비스**  
  Spring Boot 서비스 내에서 CGM을 플랫 OPC로 변환하여 확장 가능한 문서 자동화를 구현할 수 있습니다.

- **자동 문서 유효성 검사**  
  자바 파이프라인에 플랫 OPC 출력을 통합하여 스키마 유효성 검사, 콘텐츠 확인 및 공학 규정 준수 검토를 수행할 수 있습니다.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}