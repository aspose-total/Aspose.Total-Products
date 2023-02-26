---
title: Export XLS do PPTX v Androidu nebo pomocí bezplatného online převodníku
description: Android API pro převod XLS na PPTX bez použití aplikace Microsoft Word nebo online. Před integrací kódu rychle otestujte bezplatný online převodník CSV na DOC.

family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: PPTX
otherformats: WORD POWERPOINT DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslení XLS do PPTX na Androidu přes Java nebo online" h2="Transformujte XLS na PPTX ve svých aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pro Android přes Javu](https://products.aspose.com/total/android-java/) je balíček výkonných rozhraní API pro automatizaci souborů. Pomocí dvou jeho rozhraní API můžete integrovat funkci převodu XLS na PPTX do aplikací pro Android. V prvním kroku můžete exportovat XLS do PDF pomocí [Aspose.Cells pro Android přes Java](https://products.aspose.com/cells/android-java/). Poté můžete pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/) převést PDF na PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro export XLS do PPTX" %}}
1. Otevřete soubor XLS pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Převeďte XLS na PDF a nastavte SaveFormat na AUTO
3. Načtěte převedený soubor PDF pomocí třídy [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Uložte dokument ve formátu PPTX pomocí [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Aspose.Total pro Android můžete snadno používat prostřednictvím Javy přímo z [Maven](https://releases.aspose.com/total/java/) a nainstalovat [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/) a [Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Zdarma online převodník XLS na PPTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xls" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Odeberte uživatelské vlastnosti ze souboru XLS v systému Android přes Java" %}}
Kromě převodu dokumentů nabízí [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) také spoustu dalších funkcí. Před procesem převodu můžete odebrat uživatelské vlastnosti dokumentu XLS. Chcete-li odebrat vlastní vlastnosti, zavolejte metodu [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) a předejte název vlastnost dokumentu, která má být odstraněna.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xls-to-word/" name="XLS Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xls-to-powerpoint/" name="XLS Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xls-to-pptx/" name="XLS Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xls-to-pptxx/" name="XLS Na PPTXX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}