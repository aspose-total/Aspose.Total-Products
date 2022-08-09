---
title: XPS을 DOCM으로 렌더링하는 Android API
description: Java API를 통해 Android를 통해 XPS을 DOCM으로 변환
url: /ko/android-java/conversion/xps-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: DOCM
otherformats: DOTX FLATOPC RTF XAMLFLOW WORDML ODT MHTML PS MARKDOWN OTT DOT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Android에서 XPS을 DOCM으로 렌더링" h2="소프트웨어를 설치하지 않고 모바일 앱에서 XPS을 DOCM으로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) 패키지의 두 API를 사용하여 모바일 앱에서 XPS을 DOCM으로 변환 기능을 통합할 수 있습니다. 먼저 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)를 사용하여 XPS 파일을 DOC로 변환해야 합니다. 둘째, Word Processing API[Aspose.Words for Android Java](https://products.aspose.com/words/android-java/)를 사용하여 DOC를 DOCM으로 렌더링할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 Android에서 XPS을 DOCM으로 변환" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 XPS 파일을 엽니다.
2. [저장](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) 방법
3. Aspose.Words의 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOC 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 메소드를 사용하여 문서를 DOCM 형식으로 저장하고 DOCM 설정 SaveFormat으로
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java를 통한 Android용 Aspose.PDF](https://docs.aspose.com/pdf/androidjava/installation/) 및 [Java를 통한 Android용 Aspose.Words](https://docs.aspose.com/words) 설치 /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository).

또는 [다운로드](https://downloads.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOCM
outputDocument.save("output.docm", SaveFormat.DOCM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android에서 XPS 파일 정보 얻기" %}}
XPS을 DOCM으로 변환하기 전에 작성자, 작성 날짜, 키워드, 수정 날짜, 주제 및 제목을 포함한 문서에 대한 정보가 필요할 수 있습니다. 이 정보는 변환 프로세스에 대한 의사 결정에 도움이 됩니다. 강력한 [Java를 통한 Android용 Aspose.PDF](https://docs.aspose.com/pdf/androidjava/) API를 사용하면 이 모든 것을 얻을 수 있습니다. XPS 파일에 대한 파일별 정보를 얻으려면 먼저 [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) 메서드. DocumentInfo 개체가 검색되면 개별 속성의 값을 가져올 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS document
Document doc = new Document("template.xps");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android의 DOCM 문서에 미주 삽입" %}}
문서 변환 외에도 [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API를 사용하여 Android 애플리케이션 내부에 다양한 기능을 추가할 수도 있습니다. 그 기능 중 하나는 DOCM 문서에 미주와 번호를 삽입하는 것입니다. DOCM 문서에 각주 또는 미주를 삽입하려면 DocumentBuilder.InsertFootnote 메소드를 사용하십시오. 이 방법은 문서에 각주 또는 미주를 삽입합니다. EndnoteOptions 및 FootnoteOptions 클래스는 각주 및 미주에 대한 번호 매기기 옵션을 나타냅니다.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.docm", SaveFormat.DOCM);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-dotx/" name="XPS 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-flatopc/" name="XPS 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-rtf/" name="XPS 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-xamlflow/" name="XPS 에게 XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-wordml/" name="XPS 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-odt/" name="XPS 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-mhtml/" name="XPS 에게 MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-ps/" name="XPS 에게 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-markdown/" name="XPS 에게 MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-ott/" name="XPS 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-dot/" name="XPS 에게 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xps-to-dotm/" name="XPS 에게 DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}