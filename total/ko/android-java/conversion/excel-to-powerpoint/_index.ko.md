---
title: Android에서 EXCEL를 POWERPOINT로 내보내기
description: Microsoft Word를 사용하지 않고 EXCEL를 POWERPOINT로 변환하는 Android API

family: total
platformtag: cpp
feature: conversion
informat: EXCEL
outformat: POWERPOINT
otherformats: WORD DOC DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Android에서 EXCEL를 POWERPOINT로 렌더링" h2="Microsoft<sup>&reg;</sup> Excel을 사용하지 않고 Android 애플리케이션 내에서 EXCEL를 POWERPOINT로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)은 강력한 파일 자동화 API 패키지입니다. 두 가지 API를 사용하여 Android 애플리케이션 내에서 EXCEL를 POWERPOINT로 변환 기능으로 통합할 수 있습니다. 첫 번째 단계에서는 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)를 사용하여 EXCEL를 PDF로 내보낼 수 있습니다. 그 후 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)를 사용하여 PDF를 POWERPOINT로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EXCEL를 POWERPOINT로 내보내는 Android API" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 EXCEL 파일 열기
2. EXCEL를 PDF로 변환하고 SaveFormat을 AUTO로 설정
3. [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument) 클래스를 이용하여 변환된 PDF 파일을 불러옵니다.
4. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions)을 사용하여 문서를 POWERPOINT 형식으로 저장합니다. -) 방법
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) 및 [Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells) 설치 /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository).

또는 [다운로드](https://releases.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android의 EXCEL 파일에서 사용자 정의 속성 제거" %}}
문서 변환 외에도 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)는 수많은 다른 기능도 제공합니다. 변환 프로세스 전에 EXCEL 문서의 사용자 정의 속성을 제거할 수 있습니다. 사용자 정의 속성을 제거하려면 [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) 메서드를 호출하고 제거할 문서 속성입니다.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}