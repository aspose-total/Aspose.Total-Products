---
title: CGM을 PS으로 내보내기 위한 Java API
description: 온프레미스 Java API를 사용하여 CGM을 PS으로 변환
url_ignore: /ko/java/conversion/cgm-to-ps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PS
otherformats: MHTML MARKDOWN ODT DOT WORDML OTT RTF PS FLATOPC DOTM DOTX PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 PS으로 변환" h2="타사 응용 프로그램을 사용하지 않고 CGM을 PS으로 렌더링하는 온프레미스 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 사용하여 CGM을 PS으로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM 파일을 DOC로 렌더링해야 합니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 DOC를 PS으로 변환할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 PS으로 변환하는 Java API" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. Aspose.Words의 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOC 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 메소드를 사용하여 문서를 PS 형식으로 저장하고 PS 설정 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) 및 [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) pom.xml에 있습니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
CGM을 PS으로 변환하는 동안 문서가 암호로 보호되어 있더라도 PDF 조작 API[Java용 Aspose.PDF](https://docs.aspose.com/pdf/java/installation/)를 사용하여 문서를 열 수 있습니다. 암호화된 파일을 열기 위해서는 [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 객체를 생성하고 소유자의 비밀번호로 CGM을 열어야 합니다.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.cgm", "password");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 암호로 보호된 CGM 문서 열기" %}}
입력 문서를 PS 파일 형식으로 저장하는 동안 문서를 파일 시스템 대신 데이터베이스에 저장할 수도 있습니다. 데이터베이스에서 Document 객체를 저장하고 검색하는 것을 구현해야 할 수도 있습니다. 이는 모든 유형의 콘텐츠 관리 시스템을 구현하는 경우에 필요합니다. PS을 데이터베이스에 저장하려면 바이트 배열을 얻기 위해 문서를 직렬화해야 하는 경우가 많습니다. 이는 [Aspose.Words for Java](https://products.aspose.com/words/Java/) API를 사용하여 수행할 수 있습니다. 바이트 배열을 가져온 후 SQL 문을 사용하여 데이터베이스에 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PS);
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
{{% blocks/products/pf/feature-page-summary %}}
```
CGM (컴퓨터 그래픽스 메타파일)를 PS (포스트스크립트)로 변환하는 것은 정확하고 고품질의 인쇄 및 전문 출판 결과를 얻기 위한 중요한 단계입니다. PostScript의 장치 독립적 형식은 복잡한 벡터 그래픽, 공학 다이어그램 및 기술 일러스트레이션이 인쇄 프레스나 출판 시스템으로 전송될 때 정확도와 충실도를 유지하도록 보장합니다. 이는 일관된, 확장 가능하고 인쇄 준비가 된 출력물이 필요한 산업에게 CGM을 PS로 변환하는 것이 필수적임을 의미합니다.

## ✅ 주요 사용 사례
- **산업용 벡터 인쇄** – 제조, 공학 및 건축 문서용으로 선명하고 확장 가능한 기술 다이어그램 생성.
- **포스트스크립트 기반 시스템에 기술 일러스트레이션 아카이빙** – 장기적 접근성과 인쇄 호환성을 위해 최적화된 형식으로 벡터 자산 저장.
- **타입세팅을 위한 CGM 다이어그램 준비** – 전문 페이지 레이아웃 및 타입세팅 워크플로에 매끄럽게 통합되도록 보장.
- **물리적 문서 제작** – 매뉴얼, 카탈로그 및 대형 기술 차트용 인쇄 준비 파일 생성.

## ⚙️ 자동화 시나리오
- **자바 기반 프린트 스트림 생성기** – 기업용 인쇄 워크플로에 대해 CGM 파일을 프로그래밍적으로 고해상도 PS 출력으로 변환.
- **벡터를 포스트스크립트로 일괄 변환하는 변환기** – 대규모 변환 프로세스를 자동화하여 방대한 그래픽 아카이브를 효율적으로 처리.
- **출판 파이프라인 통합** – 일관된 고품질 결과를 위해 CGM을 PS로 변환하여 자동 문서 렌더링 및 전문 출판 시스템에 통합.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}