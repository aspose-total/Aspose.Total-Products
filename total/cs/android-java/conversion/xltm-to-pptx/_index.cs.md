---
title: Export XLTM do PPTX v Androidu
description: Android API pro převod XLTM na PPTX bez použití aplikace Microsoft Word
url: /cs/android-java/conversion/xltm-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOCX DOC WORD POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslení XLTM do PPTX na Androidu přes Java" h2="Transformujte XLTM na PPTX ve svých aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pro Android přes Javu](https://products.aspose.com/total/android-java/) je balíček výkonných rozhraní API pro automatizaci souborů. Pomocí dvou jeho rozhraní API můžete integrovat funkci převodu XLTM na PPTX do aplikací pro Android. V prvním kroku můžete exportovat XLTM do PDF pomocí [Aspose.Cells pro Android přes Java](https://products.aspose.com/cells/android-java/). Poté můžete pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/) převést PDF na PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro export XLTM do PPTX" %}}
1. Otevřete soubor XLTM pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Převeďte XLTM na PDF a nastavte SaveFormat na AUTO
3. Načtěte převedený soubor PDF pomocí třídy [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Uložte dokument ve formátu PPTX pomocí [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Aspose.Total pro Android můžete snadno používat prostřednictvím Javy přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.PDF pro Android přes Javu](https://pptxs.aspose.com/pdf/androidjava/installation/) a [Aspose.Cells pro Android přes Javu](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// save XLTM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Odeberte uživatelské vlastnosti ze souboru XLTM v systému Android přes Java" %}}
Kromě převodu dokumentů nabízí [Aspose.Cells pro Android přes Javu](https://products.aspose.com/cells/android-java/) také spoustu dalších funkcí. Před procesem převodu můžete odebrat uživatelské vlastnosti dokumentu XLTM. Chcete-li odebrat vlastní vlastnosti, zavolejte metodu [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) a předejte název vlastnost dokumentu, která má být odstraněna.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xltm-to-pptxx/" name="XLTM Na PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xltm-to-pptx/" name="XLTM Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xltm-to-word/" name="XLTM Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xltm-to-powerpoint/" name="XLTM Na POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}