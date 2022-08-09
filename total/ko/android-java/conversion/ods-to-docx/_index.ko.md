---
title: Android에서 ODS를 DOCX로 내보내기
description: Microsoft Word를 사용하지 않고 ODS를 DOCX로 변환하는 Android API
url: /ko/android-java/conversion/ods-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: DOCX
otherformats: DOC POWERPOINT PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Android에서 ODS를 DOCX로 렌더링" h2="Microsoft<sup>&reg;</sup> Excel을 사용하지 않고 Android 애플리케이션 내에서 ODS를 DOCX로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java를 통한 Android용 Aspose.Total](https://products.aspose.com/total/android-java/)은 강력한 파일 자동화 API 패키지입니다. 두 가지 API를 사용하여 Android 애플리케이션 내에서 ODS를 DOCX로 변환 기능으로 통합할 수 있습니다. 첫 번째 단계에서는 [Java를 통한 Android용 Aspose.Cells](https://products.aspose.com/cells/android-java/)를 사용하여 ODS를 PDF로 내보낼 수 있습니다. 그 후 [Java를 통한 Android용 Aspose.PDF](https://products.aspose.com/pdf/android-java/)를 사용하여 PDF를 DOCX로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ODS를 DOCX로 내보내는 Android API" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 ODS 파일 열기
2. ODS를 PDF로 변환하고 SaveFormat을 AUTO로 설정
3. [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument) 클래스를 이용하여 변환된 PDF 파일을 불러옵니다.
4. [저장](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions)을 사용하여 문서를 DOCX 형식으로 저장합니다. -) 방법
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Java를 통한 Android용 Aspose.PDF](https://docxs.aspose.com/pdf/androidjava/installation/) 및 [Java를 통한 Android용 Aspose.Cells](https://docxs.aspose.com/cells) 설치 /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository).

또는 [다운로드](https://downloads.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android의 ODS 파일에서 사용자 정의 속성 제거" %}}
문서 변환 외에도 [Java를 통한 Android용 Aspose.Cells](https://products.aspose.com/cells/android-java/)는 수많은 다른 기능도 제공합니다. 변환 프로세스 전에 ODS 문서의 사용자 정의 속성을 제거할 수 있습니다. 사용자 정의 속성을 제거하려면 [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) 메서드를 호출하고 제거할 문서 속성입니다.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ods-to-docx/" name="ODS 에게 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ods-to-powerpoint/" name="ODS 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ods-to-pptx/" name="ODS 에게 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/ods-to-word/" name="ODS 에게 WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}