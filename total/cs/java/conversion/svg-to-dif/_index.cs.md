---
title: Java API pro vykreslení SVG do DIF
description: Export SVG do DIF přes Java API bez použití Microsoft Excel nebo Adobe Reader
url: /cs/java/conversion/svg-to-dif/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: DIF
otherformats: ODS XLSB XLT XLSM TXT XLAM EXCEL DIF SXC TSV XLTX FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Export SVG do DIF přes Java" h2="Převeďte soubor SVG na DIF pomocí premise Java API v jakékoli Java J2SE, J2EE, J2ME aplikací" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete do svých aplikací Java integrovat funkci převodu SVG na DIF ve dvou krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete vykreslit SVG do XLSX. Ve druhém kroku můžete převést XLSX na DIF pomocí Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte soubor SVG na DIF přes Java" %}}
1. Otevřete soubor SVG pomocí třídy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte SVG na XLSX pomocí [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte dokument XLSX pomocí třídy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu DIF pomocí [SaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ve vašem pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Pokud je váš dokument SVG chráněn heslem, nemůžete jej bez hesla převést na DIF. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předejte název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte chráněné SVG na DIF přes Java" %}}
Při převodu souboru SVG na DIF můžete také přidat vodoznak do výstupního formátu souboru DIF. Chcete-li přidat vodoznak, vytvořte nový sešit a otevřete převedený soubor XLSX. Vyberte pracovní list přes jeho index, vytvořte tvar a použijte jeho funkci addTextEffect, nastavte barvy, průhlednost a další. Poté můžete uložit dokument XLSX jako DIF s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-dif/" name="SVG Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xltx/" name="SVG Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-md/" name="SVG Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-fods/" name="SVG Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xltm/" name="SVG Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-excel/" name="SVG Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xlsm/" name="SVG Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xlam/" name="SVG Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xlt/" name="SVG Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xlsb/" name="SVG Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-ods/" name="SVG Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-sxc/" name="SVG Na SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}