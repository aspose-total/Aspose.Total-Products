---
title: Android에서 XLSM를 DOC로 내보내기 또는 무료 온라인 변환기 사용
description: Microsoft Word를 사용하지 않고 XLSM를 DOC로 변환하는 Android API 또는 온라인. 코드를 통합하기 전에 무료 CSV to DOC 온라인 변환기를 빠르게 테스트하십시오.

family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: DOC
otherformats: POWERPOINT WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Android에서 XLSM를 DOC로 렌더링 또는 온라인 앱" h2="Microsoft<sup>&reg;</sup> Excel을 사용하지 않고 Android 애플리케이션 내에서 XLSM를 DOC로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)은 강력한 파일 자동화 API 패키지입니다. 두 가지 API를 사용하여 Android 애플리케이션 내에서 XLSM를 DOC로 변환 기능으로 통합할 수 있습니다. 첫 번째 단계에서는 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)를 사용하여 XLSM를 PDF로 내보낼 수 있습니다. 그 후 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)를 사용하여 PDF를 DOC로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSM를 DOC로 내보내는 Android API" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 XLSM 파일 열기
2. XLSM를 PDF로 변환하고 SaveFormat을 AUTO로 설정
3. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 이용하여 변환된 PDF 파일을 불러옵니다.
4. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)을 사용하여 문서를 DOC 형식으로 저장합니다. -) 방법
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) 및 [Aspose.Cells for Android via Java](https://docs.aspose.com/cells) 설치 /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository).

또는 [다운로드](https://releases.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>XLSM를 DOC로 변환하는 무료 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=xlsm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android의 XLSM 파일에서 사용자 정의 속성 제거" %}}
문서 변환 외에도 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)는 수많은 다른 기능도 제공합니다. 변환 프로세스 전에 XLSM 문서의 사용자 정의 속성을 제거할 수 있습니다. 사용자 정의 속성을 제거하려면 [DocumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) 메서드를 호출하고 제거할 문서 속성입니다.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// retrieve a list of all custom document properties of the Excel file
DocumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xlsm-to-powerpoint/" name="XLSM 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xlsm-to-word/" name="XLSM 에게 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xlsm-to-pptx/" name="XLSM 에게 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/xlsm-to-docx/" name="XLSM 에게 DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}