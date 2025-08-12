---
title: CGM을 MHTML으로 내보내기 위한 Java API
description: 온프레미스 Java API를 사용하여 CGM을 MHTML으로 변환
url_ignore: /ko/java/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: XAMLFLOW DOTX WORDML OTT FLATOPC DOTM PCL ODT PS MHTML MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 MHTML으로 변환" h2="타사 응용 프로그램을 사용하지 않고 CGM을 MHTML으로 렌더링하는 온프레미스 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 사용하여 CGM을 MHTML으로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM 파일을 DOC로 렌더링해야 합니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 DOC를 MHTML으로 변환할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 MHTML으로 변환하는 Java API" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. Aspose.Words의 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOC 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 메소드를 사용하여 문서를 MHTML 형식으로 저장하고 MHTML 설정 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) pom.xml에 있습니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
CGM을 MHTML으로 변환하는 동안 문서가 암호로 보호되어 있더라도 PDF 조작 API[Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/)를 사용하여 문서를 열 수 있습니다. 암호화된 파일을 열기 위해서는 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 객체를 생성하고 소유자의 비밀번호로 CGM을 열어야 합니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 암호로 보호된 CGM 문서 열기" %}}
입력 문서를 MHTML 파일 형식으로 저장하는 동안 문서를 파일 시스템 대신 데이터베이스에 저장할 수도 있습니다. 데이터베이스에서 Document 객체를 저장하고 검색하는 것을 구현해야 할 수도 있습니다. 이는 모든 유형의 콘텐츠 관리 시스템을 구현하는 경우에 필요합니다. MHTML을 데이터베이스에 저장하려면 바이트 배열을 얻기 위해 문서를 직렬화해야 하는 경우가 많습니다. 이는 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API를 사용하여 수행할 수 있습니다. 바이트 배열을 가져온 후 SQL 문을 사용하여 데이터베이스에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
**컴퓨터 그래픽 메타파일 (CGM)** 파일을 **MHTML (MIME HTML)** 형식으로 변환하는 것은 내장된 그래픽이 포함된 복잡한 공학 및 기술 문서를 단일한, 자체 포함 파일로 보존하는 데 중요합니다. **자바 기반의 웹 아카이빙 시스템**에서 이 변환을 통해 기관은 CGM 시각 자료, 스타일 및 자원을 포함한 완전한 문서를 오프라인 보기 및 인트라넷 배포에 적합한 휴대용 아카이브에 저장할 수 있습니다. MHTML은 디자인 명세, 보고서 및 도면이 장기적으로 접근 가능하고 배포되도록 보장합니다.

---

## ✅ 주요 사용 사례

- **내장된 그래픽이 포함된 공학 문서 묶기**  
  일관된, 자체 포함 기술 기록을 위해 CGM 다이어그램 및 관련 콘텐츠를 MHTML로 패키징합니다.

- **인트라넷 포털에서 오프라인 보기**  
  기업 네트워크 전체에서 원활한 오프라인 액세스를 위해 MHTML 형식의 CGM 향상 문서를 제공합니다.

- **디자인 명세 아카이빙**  
  규정 준수, 참조 및 프로젝트 문서화를 위해 CGM 기반 명세의 MHTML 버전을 저장합니다.

---

## ⚙️ 자동화 시나리오

- **MHTML 지원 Java 라이브러리**  
  **Aspose.Words for Java**와 같은 API 또는 사용자 정의 Java 익스포터를 사용하여 CGM 기반 문서에서 MHTML 파일을 생성합니다.

- **웹 기반 익스포트 도구**  
  CGM에서 MHTML로의 변환을 Java 기반 웹 애플리케이션에 통합하여 즉시 파일 패키징을 수행합니다.

- **서블릿 기반 변환 워크플로우**  
  CGM 입력을 처리하고 안전한 배포를 위해 MHTML 아카이브를 출력하는 Java 서블릿을 배포합니다.

- **자동화된 아카이빙 파이프라인**  
  일정된 아카이빙을 위해 Java 기반 문서 관리 또는 ETL 시스템에 CGM에서 MHTML로의 단계를 포함합니다.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}