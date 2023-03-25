---
title: Převést CGM na XLAM v Androidu přes Java
description: Vykreslete CGM do XLAM v systému Android přes Java API bez použití Microsoft Excel nebo Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: XLAM
otherformats: MD TSV SXC EXCEL CSV DIF XLTX TXT ODS XLT XLSM FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslit CGM do XLAM v Androidu přes Java" h2="Transformujte CGM na XLAM v rámci aplikací pro Android, aniž byste potřebovali Microsoft<sup>&reg;</sup> Excel nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu CGM na XLAM můžete integrovat do svých aplikací pro Android ve dvou krocích. Za prvé, pomocí [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) můžete převést CGM na XLSX. Za druhé, můžete převést XLSX na XLAM pomocí Powerful Spreadsheet Processing API [Aspose.Cells pro Android přes Java](https://products.aspose.com/cells/android-java/). Obě rozhraní API spadají do rodiny produktů [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro vykreslení CGM do XLAM" %}}
1. Otevřete soubor CGM pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte CGM na XLSX pomocí [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metoda
3. Načtěte dokument XLSX pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu XLAM pomocí [uložit](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://releases.aspose.com/total/java/) a nainstalovat [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) a [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte metadata XMP souboru CGM v systému Android přes Java" %}}
[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) umožňuje přístup k metadatům XMP souboru CGM. Chcete-li získat metadata, vytvořte objekt [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) a otevřete vstupní soubor CGM a použijte [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) pro získání metadat.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chraňte dokument XLAM v systému Android přes Java" %}}
[Aspose.Cells pro Android přes Java](https://products.aspose.com/cells/android-java/) podporuje ochranu vašeho souboru XLAM v závislosti na vašich potřebách. K ochraně vašeho dokumentu můžete použít metodu [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) metody [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) třídy.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-xlam.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}