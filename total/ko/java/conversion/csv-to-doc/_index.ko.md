---
title: Java를 사용하여 CSV를 DOC로 변환 또는 무료 온라인 변환기 사용
description: Excel 또는 Word를 사용하여 CSV를 DOC로 내보내는 Java API 또는 온라인 또는 온라인. 코드를 통합하기 전에 무료 CSV to DOC 온라인 변환기를 빠르게 테스트하십시오.
url_ignore: /ko/java/conversion/csv-to-doc/
family: total
platformtag: net
feature: conversion
informat: CSV
outformat: DOC
otherformats: DOCX PPTX POWERPOINT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CSV를 DOC로 내보내는 Java API 또는 온라인" h2="Microsoft Excel에 의존하지 않고 CSV를 DOC로 내보내기 위한 온프레미스 Java API&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
CSV를 DOC로 렌더링하는 것은 2단계 프로세스입니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java) API를 사용하여 주어진 CSV 문서를 PDF로 변환한 다음 [Aspose.Pdf for Java](https://products.aspose.com/cells/java)를 사용합니다. ://products.aspose.com/pdf/java) API를 사용하면 PDF 문서를 DOC로 쉽게 변환할 수 있습니다. 두 API 모두 [Aspose.Total for Java](https://products.aspose.com/total/java/) 파일 형식 자동화 라이브러리 컬렉션에 포함됩니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API를 통해 CSV를 DOC로 변환하는 방법" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 CSV 파일 열기
2. CSV를 PDF로 변환하고 SaveFormat을 AUTO로 설정
3. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 이용하여 변환된 PDF 파일을 불러옵니다.
4. [저장](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)을 사용하여 문서를 DOC 형식으로 저장합니다.-) 메서드 및 Doc을 SaveFormat으로 설정
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 사용해야 합니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cs
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
// save CSV as PDF
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
<div class="demobox tc col-md-12 padding-0">

<h3>CSV에서 DOC로 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=csv" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/csv-to-doc/">CSV를 DOC로 변환하는 무료 앱을 사용해 보세요.</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}