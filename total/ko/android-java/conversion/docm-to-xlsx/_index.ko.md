---
title: DOCM를 XLSX로 변환하는 Android API
description: Microsoft Word 또는 Microsoft Excel을 사용하지 않고 Java를 통해 Android에서 DOCM를 XLSX로 변환

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: XLSX
otherformats: XLTM XLS XLSM ODS DIF SXC XLAM EXCEL XLSB FODS XLT TSV XLTX CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android 애플리케이션에서 DOCM를 XLSX로 변환" h2="Microsoft<sup>&reg;</sup> Word 또는 Microsoft<sup>&reg;</sup> Excel을 사용하지 않고 Java를 통해 Android에서 DOCM를 XLSX로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)을 사용하여 Android 애플리케이션 내에서 DOCM를 XLSX로 변환 기능을 통합할 수 있습니다. 첫째, 기능이 풍부한 문서 조작 및 변환 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)를 사용하여 DOCM를 HTML로 변환할 수 있습니다. 이후 [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/)를 사용하여 HTML을 XLSX로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCM를 XLSX로 변환하는 Android API" %}}
1. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOCM 파일을 엽니다.
2. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions))을 사용하여 DOCM를 HTML로 변환합니다. ) 방법
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 HTML 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 XLSX 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. [Aspose.Cells for Android via Java](https://docms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) 설치 및 [Aspose.Words for Android via Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository).

또는 [다운로드](https://releases.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android의 DOCM 문서에서 사용하지 않는 정보 제거" %}}
DOCM를 XLSX로 변환하기 전에 [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)를 통해 DOCM 문서에서 사용하지 않는 정보를 제거할 수 있습니다. 출력 문서의 크기와 처리 시간을 줄이기 위해 사용하지 않거나 중복된 정보를 제거해야 하는 경우가 있습니다. [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) 클래스를 사용하면 문서 정리 옵션을 지정할 수 있습니다. 문서에서 중복된 스타일이나 사용하지 않는 스타일 또는 목록만 제거하려면 [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) 메서드를 사용할 수 있습니다. [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) 및 [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) 속성을 사용하여 "미사용"으로 표시된 스타일을 감지하고 제거합니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docmument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android에서 스트림에 XLSX 파일 저장" %}}
DOCM를 XLSX로 변환한 후 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)를 사용하여 문서를 스트림에 저장할 수 있습니다. 스트림에 파일을 저장해야 하는 경우 FileOutputStream 객체를 생성한 다음 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)의 save 메소드를 호출하여 해당 Stream 객체에 파일 물체.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-xltm/" name="DOCM 에게 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-xls/" name="DOCM 에게 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-xlsm/" name="DOCM 에게 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-ods/" name="DOCM 에게 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-dif/" name="DOCM 에게 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-sxc/" name="DOCM 에게 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-xlam/" name="DOCM 에게 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-excel/" name="DOCM 에게 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-xlsb/" name="DOCM 에게 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-fods/" name="DOCM 에게 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-xlt/" name="DOCM 에게 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-tsv/" name="DOCM 에게 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-xltx/" name="DOCM 에게 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/docm-to-xlsx/" name="DOCM 에게 XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}