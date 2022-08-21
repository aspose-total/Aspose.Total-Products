---
title: Export XLSX do POWERPOINT v Androidu
description: Android API pro převod XLSX na POWERPOINT bez použití aplikace Microsoft Word
url: /cs/android-java/conversion/xlsx-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: DOC WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslení XLSX do POWERPOINT na Androidu přes Java" h2="Transformujte XLSX na POWERPOINT ve svých aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pro Android přes Javu](https://products.aspose.com/total/android-java/) je balíček výkonných rozhraní API pro automatizaci souborů. Pomocí dvou jeho rozhraní API můžete integrovat funkci převodu XLSX na POWERPOINT do aplikací pro Android. V prvním kroku můžete exportovat XLSX do PDF pomocí [Aspose.Cells pro Android přes Java](https://products.aspose.com/cells/android-java/). Poté můžete pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/) převést PDF na POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro export XLSX do POWERPOINT" %}}
1. Otevřete soubor XLSX pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Převeďte XLSX na PDF a nastavte SaveFormat na AUTO
3. Načtěte převedený soubor PDF pomocí třídy [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Uložte dokument ve formátu POWERPOINT pomocí [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Aspose.Total pro Android můžete snadno používat prostřednictvím Javy přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) a [Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Odeberte uživatelské vlastnosti ze souboru XLSX v systému Android přes Java" %}}
Kromě převodu dokumentů nabízí [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) také spoustu dalších funkcí. Před procesem převodu můžete odebrat uživatelské vlastnosti dokumentu XLSX. Chcete-li odebrat vlastní vlastnosti, zavolejte metodu [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) a předejte název vlastnost dokumentu, která má být odstraněna.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xlsx-to-powerpoint/" name="XLSX Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xlsx-to-word/" name="XLSX Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xlsx-to-pptx/" name="XLSX Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xlsx-to-powerpointx/" name="XLSX Na POWERPOINTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}