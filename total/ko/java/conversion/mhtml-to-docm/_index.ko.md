---
title: 온라인 MHTML에서 DOCM로 변환 또는 MHTML 파일을 변환하기 위한 Java 기반 애플리케이션 개발
description: MHTML를 DOCM 파일로 변환하는 무료 온라인 앱. MHTML 문서에 대한 Java 변환 라이브러리 코드. 

family: total
platformtag: Java
feature: conversion
informat: MHTML
outformat: DOCM
otherformats: PCL RTF DOTM OTT DOT WORDML PS MARKDOWN ODT FLATOPC DOTX XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="온라인 MHTML에서 DOCM로 변환 앱 및 MHTML 파일을 변환하는 Java 코드" h2="강력한 Java 기반 MHTML 변환 및 내보내기 애플리케이션을 개발합니다. Java 자동화 API를 통해 하나 또는 여러 개의 MHTML 파일을 DOCM 및 기타 형식으로 변환합니다. 앱을 통해 MHTML 파일을 온라인으로 자유롭게 변환하고 즉시 다운로드하세요." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="무료 온라인 MHTML에서 DOCM로 변환 앱" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=docm&from=mhtml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="앱을 사용하여 MHTML를 DOCM 파일로 온라인으로 변환" %}}

1. 변환할 MHTML 파일 업로드
1. MHTML 크기에 따라 몇 초 이상 기다리십시오.
1. 업로드 상태 표시줄을 주시하세요
1. "변환" 버튼을 클릭하세요
1. MHTML가 DOCM 문서로 변환됩니다.
1. 변환된 DOCM 파일을 다운로드하세요

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Java Automation API를 통해 MHTML를 DOCM로 변환" %}}


1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 MHTML 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) 방법
3. Aspose.Words의 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOC 파일을 로드합니다.
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 메소드를 사용하여 문서를 DOCM 형식으로 저장하고 DOCM 설정 SaveFormat으로



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "89f68c1b3e3c772c46b1f2adbaf240e5" "convert-mhtml-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

변환 요구 사항, Java를 통해 암호로 보호된 MHTML 문서 열기와 같은 다른 기능을 사용하여 MHTML를 DOCM로 저장하는 몇 가지 사례가 더 있습니다.

{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOCM);
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


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Java를 사용하여 MHTML 파일 변환 애플리케이션 개발</h2>

MHTML 파일을 DOCM 문서로 쉽게 저장하고 내보낼 수 있는 Java 기반 소프트웨어 애플리케이션을 개발해야 합니까? [Aspose.Total for Java](https://products.aspose.com/total/ko/java/)을 사용하면 모든 Java 개발자가 위의 API 코드를 통합하여 Microsoft Word(DOC, DOCX), Excel(XLS, XLSX), Powerpoint(PPT, PPTX), PDF, 이메일 파일, 이미지(JPG, PNG, BMP, GIF) 및 기타 형식을 포함한 다양한 형식으로 변환 애플리케이션을 프로그래밍할 수 있습니다. 문서 변환을 위한 강력한 Java 라이브러리로, MHTML 형식을 포함한 여러 인기 형식을 지원합니다. 프로그래머는 [Aspose.Words for Java](https://products.aspose.com/words/ko/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/ko/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/ko/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/ko/java/) 등을 포함한 Aspose.Total for Java 자식 API를 사용하여 문서를 다른 형식으로 내보내고 렌더링할 수 있습니다.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTML Java용 변환 라이브러리" %}}

Aspose.Total for Java을 귀하의 시스템에 통합하기 위한 대체 옵션도 있습니다. 귀하의 요구 사항과 유사한 것을 선택하고 단계별 지침을 따르세요.<br /><br />

- Maven 기반 프로젝트에서 Aspose.Total for Java을 직접 사용하고 pom.xml에 관련 자식 API를 포함합니다.
- 혹은 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 얻을 수도 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="MHTML를 DOCM 앱 요구 사항에 저장합니다." %}}

Java Runtime Environment(JRE)를 실행할 수 있는 모든 운영 체제는 Aspose.Total for Java을 실행할 수 있습니다. 다음 목록은 대부분 지원되는 운영 체제이지만, 전부는 아닙니다. <br /><br />
- 마이크로소프트 윈도우
- Linux : Ubuntu, OpenSUSE, CentOS 및 기타
- macOS : 10.9(Mavericks) 이상
- 모바일 : 안드로이드, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



MHTML (MIME HTML) 파일을 DOCM (매크로 활성화 워드 문서)으로 변환하면 자동화된 워크플로우를 위한 상호작용 매크로와 함께 웹 콘텐츠가 보존됩니다. DOCM 파일은 비즈니스 프로세스 자동화, 고급 보고 및 동적 문서 생성에 필수적입니다.



{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}



* 웹 스크랩 콘텐츠에서 생성된 자동화된 회사 보고서.

* e-러닝을 위한 포함된 매크로가 있는 대화형 교육 모듈.

* 실시간 웹 데이터를 통합하는 비즈니스 프로세스 문서화.

* 매크로로 구동되는 대시보드를 클릭할 수 있는 프로젝트 관리 템플릿.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}



* 보관된 MHTML 보고서를 매크로 활성화 DOCM 파일로 일괄 변환.

* 실시간 문서 업데이트를 위한 ERP 시스템 통합.

* 웹 콘텐츠 변환 후 매크로 실행 트리거.

* MHTML 소스에서 반복되는 비즈니스 템플릿의 자동 생성.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}