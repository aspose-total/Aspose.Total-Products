---
title: EPUB을 XAMLFLOW으로 내보내기 위한 Java API
description: 온프레미스 Java API를 사용하여 EPUB을 XAMLFLOW으로 변환
url_ignore: /ko/java/conversion/epub-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: XAML_FLOW
otherformats: MARKDOWN DOTM PCL DOT WORDML DOTX FLATOPC XAMLFLOW ODT PS MHTML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 EPUB을 XAMLFLOW으로 변환" h2="타사 응용 프로그램을 사용하지 않고 EPUB을 XAMLFLOW으로 렌더링하는 온프레미스 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 사용하여 EPUB을 XAMLFLOW으로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 EPUB 파일을 DOC로 렌더링해야 합니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 DOC를 XAMLFLOW으로 변환할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB을 XAMLFLOW으로 변환하는 Java API" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 EPUB 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. Aspose.Words의 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOC 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 메소드를 사용하여 문서를 XAMLFLOW 형식으로 저장하고 XAMLFLOW 설정 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) pom.xml에 있습니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-xaml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
EPUB을 XAMLFLOW으로 변환하는 동안 문서가 암호로 보호되어 있더라도 PDF 조작 API[Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/)를 사용하여 문서를 열 수 있습니다. 암호화된 파일을 열기 위해서는 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 객체를 생성하고 소유자의 비밀번호로 EPUB을 열어야 합니다.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.epub", "password");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 암호로 보호된 EPUB 문서 열기" %}}
입력 문서를 XAMLFLOW 파일 형식으로 저장하는 동안 문서를 파일 시스템 대신 데이터베이스에 저장할 수도 있습니다. 데이터베이스에서 Document 객체를 저장하고 검색하는 것을 구현해야 할 수도 있습니다. 이는 모든 유형의 콘텐츠 관리 시스템을 구현하는 경우에 필요합니다. XAMLFLOW을 데이터베이스에 저장하려면 바이트 배열을 얻기 위해 문서를 직렬화해야 하는 경우가 많습니다. 이는 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API를 사용하여 수행할 수 있습니다. 바이트 배열을 가져온 후 SQL 문을 사용하여 데이터베이스에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.XAML_FLOW);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**EPUB을 XAMLFLOW로 변환하는 것**은 현대적인 애플리케이션을 위한 **플로우 기반 문서 레이아웃**을 생성하는 데 필수적입니다. XAMLFLOW는 동적이고 대화형 그리고 적응형 콘텐츠 렌더링을 가능하게 하며, 디지털 출판, 연구 시각화 및 애플리케이션 중심 문서에 이상적입니다. EPUB을 XAMLFLOW로 변환함으로써 출판사와 개발자는 가독성, 참여도 및 플랫폼 간 상호 작용을 향상시키는 반응형 레이아웃을 만들 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}
- **디지털 출판 워크플로우** – 적응형 및 대화형 eBook 레이아웃을 간소화합니다.
- **대화형 eBook** – 동적인 플로우 기반 콘텐츠로 사용자 참여도를 향상시킵니다.
- **애플리케이션 중심 콘텐츠** – 출판물을 앱 기반 인터페이스에 원활하게 통합합니다.
- **연구 문서 시각화** – 구조화되고 가독성 있는 플로우로 복잡한 데이터 집합과 출판물을 제시합니다.
- **동적 레이아웃** – 장치 및 플랫폼 간 반응형 디자인을 가능하게 합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}
- **EPUB-to-XAMLFLOW 파이프라인** – eBook을 플로우 기반 레이아웃으로 자동 변환합니다.
- **자동화된 플로우 문서 생성** – 출판 콘텐츠로부터 대화형 문서를 생성합니다.
- **대량 콘텐츠 변환** – 대량의 EPUB을 효율적으로 XAMLFLOW로 변환합니다.
- **기업급 출판 앱** – 확장 가능한 디지털 출판 플랫폼에 XAMLFLOW 생성을 통합합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}