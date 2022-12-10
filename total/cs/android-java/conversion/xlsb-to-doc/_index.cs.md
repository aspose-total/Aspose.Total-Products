---
title: Export XLSB do DOC v Androidu
description: Android API pro převod XLSB na DOC bez použití aplikace Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: DOC
otherformats: WORD POWERPOINT DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslení XLSB do DOC na Androidu přes Java" h2="Transformujte XLSB na DOC ve svých aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pro Android přes Javu](https://products.aspose.com/total/android-java/) je balíček výkonných rozhraní API pro automatizaci souborů. Pomocí dvou jeho rozhraní API můžete integrovat funkci převodu XLSB na DOC do aplikací pro Android. V prvním kroku můžete exportovat XLSB do PDF pomocí [Aspose.Cells pro Android přes Java](https://products.aspose.com/cells/android-java/). Poté můžete pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/) převést PDF na DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro export XLSB do DOC" %}}
1. Otevřete soubor XLSB pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Převeďte XLSB na PDF a nastavte SaveFormat na AUTO
3. Načtěte převedený soubor PDF pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Uložte dokument ve formátu DOC pomocí [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Aspose.Total pro Android můžete snadno používat prostřednictvím Javy přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) a [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Odeberte uživatelské vlastnosti ze souboru XLSB v systému Android přes Java" %}}
Kromě převodu dokumentů nabízí [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) také spoustu dalších funkcí. Před procesem převodu můžete odebrat uživatelské vlastnosti dokumentu XLSB. Chcete-li odebrat vlastní vlastnosti, zavolejte metodu [DocumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) a předejte název vlastnost dokumentu, která má být odstraněna.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// retrieve a list of all custom document properties of the Excel file
DocumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xlsb-to-word/" name="XLSB Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xlsb-to-powerpoint/" name="XLSB Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xlsb-to-docx/" name="XLSB Na DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xlsb-to-pptx/" name="XLSB Na PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}