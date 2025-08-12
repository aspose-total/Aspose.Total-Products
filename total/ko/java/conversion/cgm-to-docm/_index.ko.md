---
title: CGM을 DOCM으로 내보내기 위한 Java API
description: 온프레미스 Java API를 사용하여 CGM을 DOCM으로 변환
url_ignore: /ko/java/conversion/cgm-to-docm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOCM
otherformats: RTF WORDML ODT FLATOPC PS PCL MHTML DOTM OTT DOTX XAMLFLOW MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 DOCM으로 변환" h2="타사 응용 프로그램을 사용하지 않고 CGM을 DOCM으로 렌더링하는 온프레미스 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 사용하여 CGM을 DOCM으로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM 파일을 DOC로 렌더링해야 합니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 DOC를 DOCM으로 변환할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 DOCM으로 변환하는 Java API" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. Aspose.Words의 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOC 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 메소드를 사용하여 문서를 DOCM 형식으로 저장하고 DOCM 설정 SaveFormat으로
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
CGM을 DOCM으로 변환하는 동안 문서가 암호로 보호되어 있더라도 PDF 조작 API[Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/)를 사용하여 문서를 열 수 있습니다. 암호화된 파일을 열기 위해서는 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 객체를 생성하고 소유자의 비밀번호로 CGM을 열어야 합니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 암호로 보호된 CGM 문서 열기" %}}
입력 문서를 DOCM 파일 형식으로 저장하는 동안 문서를 파일 시스템 대신 데이터베이스에 저장할 수도 있습니다. 데이터베이스에서 Document 객체를 저장하고 검색하는 것을 구현해야 할 수도 있습니다. 이는 모든 유형의 콘텐츠 관리 시스템을 구현하는 경우에 필요합니다. DOCM을 데이터베이스에 저장하려면 바이트 배열을 얻기 위해 문서를 직렬화해야 하는 경우가 많습니다. 이는 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API를 사용하여 수행할 수 있습니다. 바이트 배열을 가져온 후 SQL 문을 사용하여 데이터베이스에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
**컴퓨터 그래픽 메타파일 (CGM)** 파일을 **DOCM (매크로 활성화 워드 문서)**로 변환하는 것은 상호 작용적이고 자동화되며 동적 문서 워크플로우가 필요한 조직에게 매우 가치가 있습니다. **자바 기반 문서 자동화 시스템**에서 이 변환은 CGM에서 기술 다이어그램, 공학 도면 및 프로세스 시각 자료를 매크로 활성화된 보고서에 포함할 수 있게 합니다. DOCM 형식은 VBA 매크로를 지원하여 자동 계산, 데이터 업데이트 및 상호 작용적 보고를 가능하게 하며, 공학, 산업 및 기업 문서 작성 요구에 적합합니다.


## ✅ 주요 사용 사례

- **동적 기술 보고**  
  CGM 기반 그림을 DOCM 템플릿에 포함하여 차트, 표 및 분석 콘텐츠를 자동으로 업데이트합니다.

- **공학 로그용 매크로 활성화 문서 생성**  
  매크로가 CGM 다이어그램 데이터를 처리하고 계산 결과와 함께 제시하는 공학 로그북을 생성합니다.

- **워크플로 문서화**  
  CGM 시각 자료와 매크로 기반 탐색이 포함된 대화식 매뉴얼이나 운영 가이드를 생성합니다.


## ⚙️ 자동화 시나리오

- **DOCM 생성을 위한 자바 라이브러리**  
  **Apache POI**, **docx4j**, 또는 **Aspose.Words for Java**와 같은 API를 사용하여 CGM을 DOCM으로 변환하고 매크로를 지원합니다.

- **기업 문서 어셈블리**  
  Java 기반 기업 콘텐츠 관리 시스템에 변환 프로세스를 통합하여 즉시 매크로 활성화 파일 생성을 수행합니다.

- **매크로 기반 데이터 처리**  
  CGM 시각 자료에 연결된 데이터를 읽고 해석하며 업데이트하는 매크로를 포함하여 기술 분석을 자동화합니다.

- **일괄 처리 워크플로**  
  Java 기반 일괄 처리 자동화 도구를 통해 여러 CGM 파일을 매크로 활성화된 DOCM 보고서로 변환하고 편집합니다.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}