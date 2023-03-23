---
title: Převeďte XLSM na DOCX pomocí Java nebo pomocí bezplatného online převodníku
description: Java API pro export XLSM do DOCX nebo online pomocí Excelu nebo Wordu nebo online. Před integrací kódu rychle otestujte bezplatný online převodník CSV na DOC.
url_ignore: /cs/java/conversion/xlsm-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: DOCX
otherformats: DOCX WORD POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro export XLSM do DOCX nebo online" h2="On Premise Java API pro export XLSM do DOCX nebo online bez spoléhání se na Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vykreslení XLSM do DOCX je dvoufázový proces. Nejprve použijete [Aspose.Cells for Java](https://products.aspose.com/cells/java) API k převodu daného XLSM dokumentu do PDF a poté pomocí [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, můžete snadno převést dokument PDF na DOCX. Obě rozhraní API spadají do kolekce knihoven automatizace formátu souborů [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést XLSM na DOCX přes Java API" %}}
1. Otevřete soubor XLSM pomocí třídy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Převeďte XLSM na PDF a nastavte SaveFormat na AUTO
3. Načtěte převedený soubor PDF pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Uložte dokument ve formátu DOCX pomocí [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) a nastavte Docx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Musíte použít Aspose.Total pro Javu přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Online převodník XLSM na DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsm" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsm-to-docx/">Vyzkoušejte naši bezplatnou aplikaci pro převod XLSM na DOCX</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}DOCX
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xlsm-to-docxx/" name="XLSM Na DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xlsm-to-pptx/" name="XLSM Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xlsm-to-powerpoint/" name="XLSM Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xlsm-to-word/" name="XLSM Na WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}