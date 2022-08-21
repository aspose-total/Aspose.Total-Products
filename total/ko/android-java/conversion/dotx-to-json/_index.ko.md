---
title: Java를 통해 Android에서 DOTX를 JSON 형식으로 변환
description: Microsoft Word 또는 Excel을 사용하지 않고 Java를 통해 Android에서 DOTX를 JSON 형식으로 구문 분석
url: /ko/android-java/conversion/dotx-to-json/
family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Android에서 DOTX를 JSON 형식으로 변환" h2="Microsoft<sup>&reg;</sup> Word 또는 Excel을 사용하지 않고 DOTX를 JSON으로 내보내도록 Android 애플리케이션 설계" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)을 통해 Android 애플리케이션에서 DOTX를 JSON 형식으로 변환할 수 있습니다. 문서 조작 및 변환 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)를 사용하여 DOTX를 HTML로 내보낼 수 있습니다. 이후 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)를 사용하여 HTML을 JSON으로 변환할 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android에서 DOTX를 JSON 형식으로 변환" %}}
1. [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument) 클래스를 사용하여 DOTX 파일을 엽니다.
2. [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 DOTX를 HTML로 변환합니다. ) 방법
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 HTML 문서 로드
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 JSON 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)에서 직접 Java를 통해 Android용 Aspose.Total을 쉽게 사용할 수 있습니다. 앱에 라이브러리를 설치합니다.

또는 [다운로드](https://downloads.aspose.com/total/androidjava)에서 ZIP 파일을 얻을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android에서 보호된 DOTX를 JSON 형식으로 변환" %}}
API를 사용하여 암호로 보호된 문서를 열 수도 있습니다. 입력 DOTX 문서가 비밀번호로 보호되어 있는 경우 비밀번호를 사용하지 않고는 JSON 형식으로 변환할 수 없습니다. API를 사용하면 LoadOptions 개체에 올바른 암호를 전달하여 암호화된 문서를 열 수 있습니다. 다음 코드 예제는 암호로 암호화된 문서를 여는 방법을 보여줍니다.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java를 통해 Android의 Range에서 DOTX를 JSON으로 변환" %}}
DOTX를 JSON으로 변환하는 동안 범위를 출력 JSON 형식으로 설정할 수도 있습니다. 범위를 설정하려면 변환된 HTML을 Workbook 클래스를 사용하여 열고 Cells.createRange 메서드를 사용하여 내보낼 데이터 범위를 만들고 Range & ExportRangeToJsonOptions의 참조로 JsonUtility.exportRangeToJson 메서드를 호출하고 문자열 JSON 데이터를 파일에 씁니다. BufferedWriter.write 메서드.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-sxc/" name="DOTX 에게 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-xlsm/" name="DOTX 에게 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-xlsb/" name="DOTX 에게 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-tsv/" name="DOTX 에게 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-xlam/" name="DOTX 에게 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-xlt/" name="DOTX 에게 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-dif/" name="DOTX 에게 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-excel/" name="DOTX 에게 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-xltx/" name="DOTX 에게 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-csv/" name="DOTX 에게 CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-xltm/" name="DOTX 에게 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-fods/" name="DOTX 에게 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-ods/" name="DOTX 에게 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/android-java/conversion/dotx-to-xlsx/" name="DOTX 에게 XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}