---
title: Java를 통해 Android에서 XSLFO을 EXCEL로 변환
description: Microsoft Excel 또는 Adobe Reader를 사용하지 않고 Java API를 통해 Android에서 XSLFO을 EXCEL로 렌더링

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: CSV
otherformats: TSV FODS SXC XLSB ODS XLAM MD XLTX DIF CSV TXT XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Android에서 XSLFO을 EXCEL로 렌더링" h2="Microsoft<sup>&reg;</sup> Excel 또는 Adobe<sup>&reg;</sup> Acrobat Reader 없이 Android 애플리케이션 내에서 XSLFO을 EXCEL로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}
2단계 프로세스로 Android 애플리케이션 내에서 XSLFO에서 EXCEL로의 변환 기능을 통합할 수 있습니다. 먼저 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)를 사용하여 XSLFO을 XLSX로 변환할 수 있습니다. 둘째, 강력한 스프레드시트 처리 API[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)를 사용하여 XLSX를 EXCEL로 변환할 수 있습니다. 두 API 모두 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 제품군에 속합니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XSLFO을 EXCEL로 렌더링하는 Android API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 XSLFO 파일을 엽니다.
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) 방법
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 XLSX 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 EXCEL 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) 및 [Aspose.Cells for Android via Java](https://docs.aspose.com/cells) 설치 /java/aspose-cells-for-android-via-java-installation/)을 애플리케이션에 추가합니다.

또는 [다운로드](https://releases.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android에서 XSLFO 파일의 XMP 메타데이터 가져오기" %}}
[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)를 사용하면 XSLFO 파일의 XMP 메타데이터에 액세스할 수 있습니다. 메타데이터를 얻기 위해서는 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 객체를 생성하고 입력된 XSLFO 파일을 열어 [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) 속성을 사용하여 메타데이터를 가져옵니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android에서 EXCEL 문서 보호" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)는 필요에 따라 EXCEL 파일 보호를 지원합니다. 문서를 보호하기 위해 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}