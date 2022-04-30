---
title: Java를 사용하여 TSV를 PPTX로 변환
description: Excel 또는 Word를 사용하여 TSV를 PPTX로 내보내는 Java API
url: /ko/java/conversion/tsv-to-pptx/
family: total
platformtag: net
feature: conversion
informat: TSV
outformat: PPTX
otherformats: PPTX WORD POWERPOINT PPTXX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="TSV를 PPTX로 내보내는 Java API" h2="Microsoft Excel에 의존하지 않고 TSV를 PPTX로 내보내기 위한 온프레미스 Java API&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
TSV를 PPTX로 렌더링하는 것은 2단계 프로세스입니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java) API를 사용하여 주어진 TSV 문서를 PDF로 변환한 다음 [Aspose.Pdf for Java](https://products.aspose.com/cells/java)를 사용합니다. ://products.aspose.com/pdf/java) API를 사용하면 PDF 문서를 PPTX로 쉽게 변환할 수 있습니다. 두 API 모두 [Aspose.Total for Java](https://products.aspose.com/total/java/) 파일 형식 자동화 라이브러리 컬렉션에 포함됩니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API를 통해 TSV를 PPTX로 변환하는 방법" %}}
1. [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 TSV 파일 열기
2. TSV를 PDF로 변환하고 SaveFormat을 AUTO로 설정
3. [문서](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Pptxument) 클래스를 이용하여 변환된 PDF 파일을 불러옵니다.
4. [저장](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions)을 사용하여 문서를 PPTX 형식으로 저장합니다.-) 메서드 및 Pptx을 SaveFormat으로 설정
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 기반 프로젝트에서 직접 Java용 Aspose.Total을 사용해야 합니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://downloads.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/tsv-to-pptxx/" name="TSV 에게 PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/tsv-to-pptx/" name="TSV 에게 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/tsv-to-powerpoint/" name="TSV 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/tsv-to-word/" name="TSV 에게 WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}