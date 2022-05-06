---
title: OTT를 XLSM로 변환하는 Java API
description: Microsoft Word 또는 Microsoft Excel을 사용하지 않고 Java를 통해 OTT를 XLSM로 변환
url_ignore: /ko/java/conversion/ott-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: XLSM
otherformats: EXCEL XLT XLSX TSV XLTX SXC XLSB ODS XLSM XLS XLTM FODS XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 OTT를 XLSM로 변환" h2="Microsoft<sup>&reg;</sup> Word 또는 Microsoft<sup>&reg;</sup> Excel을 사용하지 않고 OTT를 XLSM로 변환하는 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 통해 OTT를 XLSM로 변환하는 것은 간단한 2단계 프로세스입니다. 기능이 풍부한 문서 조작 및 변환 API [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 OTT를 HTML로 내보낼 수 있습니다. 그 후 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 HTML을 XLSM로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OTT를 XLSM로 변환하는 C++ API" %}}
1. [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 OTT 파일을 엽니다.
2. [저장](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 OTT를 HTML로 변환합니다. ) 방법
3. [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 HTML 문서 로드
4. [저장](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))을 사용하여 문서를 XLSM 형식으로 저장합니다. SaveOptions)) 메서드
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) 및 [Aspose.Cells for Java](https://docs.aspose.com/cells/java/) 포함 설치/) pom.xml에 있습니다.

또는 [다운로드](https://downloads.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}/Document
OTT를 XLSM로 변환하기 전에 [Aspose.Words for Java](https://products.aspose.com/words/java/)를 통해 OTT 문서에서 사용하지 않는 정보를 제거할 수 있습니다. 출력 문서의 크기와 처리 시간을 줄이기 위해 사용하지 않거나 중복된 정보를 제거해야 하는 경우가 있습니다. [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) 클래스를 사용하면 문서 정리 옵션을 지정할 수 있습니다. 문서에서 중복된 스타일이나 사용하지 않는 스타일 또는 목록만 제거하려면 [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Document#cleanup()) 메서드를 사용할 수 있습니다. [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) 및 [UnusedBuiltinStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) 속성을 사용하여 "미사용"으로 표시된 스타일을 감지하고 제거합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 OTT 문서에서 사용하지 않는 정보 제거" %}}
OTT를 XLSM로 변환한 후 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 문서를 스트림에 저장할 수 있습니다. 스트림에 파일을 저장해야 하는 경우 FileOutputStream 객체를 생성한 다음 [저장](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)의 save 메소드를 호출하여 해당 Stream 객체에 파일 물체. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-xlsm/" name="OTT 에게 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-xlt/" name="OTT 에게 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-ods/" name="OTT 에게 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-tsv/" name="OTT 에게 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-xls/" name="OTT 에게 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-xlsb/" name="OTT 에게 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-fods/" name="OTT 에게 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-dif/" name="OTT 에게 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-xltx/" name="OTT 에게 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-xlam/" name="OTT 에게 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-xlsx/" name="OTT 에게 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-xltm/" name="OTT 에게 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-sxc/" name="OTT 에게 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/ott-to-excel/" name="OTT 에게 EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}