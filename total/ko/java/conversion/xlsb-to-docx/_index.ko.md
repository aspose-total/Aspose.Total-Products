---
title: Java를 사용하여 XLSB를 DOCX로 변환 또는 무료 온라인 변환기 사용
description: Excel 또는 Word를 사용하여 XLSB를 DOCX로 내보내는 Java API 또는 온라인 또는 온라인. 코드를 통합하기 전에 무료 CSV to DOC 온라인 변환기를 빠르게 테스트하십시오.
url_ignore: /ko/java/conversion/xlsb-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCXX
otherformats: PPTX WORD DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XLSB를 DOCX로 내보내는 Java API 또는 온라인" h2="Microsoft Excel에 의존하지 않고 XLSB를 DOCX로 내보내기 위한 온프레미스 Java API&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
XLSB를 DOCX로 렌더링하는 것은 2단계 프로세스입니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java) API를 사용하여 주어진 XLSB 문서를 PDF로 변환한 다음 [Aspose.Pdf for Java](https://products.aspose.com/cells/java)를 사용합니다. ://products.aspose.com/pdf/java) API를 사용하면 PDF 문서를 DOCX로 쉽게 변환할 수 있습니다. 두 API 모두 [Aspose.Total for Java](https://products.aspose.com/total/java/) 파일 형식 자동화 라이브러리 컬렉션에 포함됩니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API를 통해 XLSB를 DOCX로 변환하는 방법" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 XLSB 파일 열기
2. XLSB를 PDF로 변환하고 SaveFormat을 AUTO로 설정
3. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 이용하여 변환된 PDF 파일을 불러옵니다.
4. [저장](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)을 사용하여 문서를 DOCX 형식으로 저장합니다.-) 메서드 및 Docx을 SaveFormat으로 설정
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 사용해야 합니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>XLSB에서 DOCX로 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsb" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsb-to-docx/">XLSB를 DOCX로 변환하는 무료 앱을 사용해 보세요.</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/xlsb-to-docxx/" name="XLSB 에게 DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/xlsb-to-pptx/" name="XLSB 에게 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/xlsb-to-powerpoint/" name="XLSB 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/xlsb-to-word/" name="XLSB 에게 WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}