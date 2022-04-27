---
title: Java API pro vykreslení CGM do XLTM
description: Export CGM do XLTM přes Java API bez použití Microsoft Excel nebo Adobe Reader
url: /cs/java/conversion/cgm-to-xltm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLTM
otherformats: XLTM TSV TXT XLT ODS EXCEL XLTX MD SXC XLSB DIF XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Export CGM do XLTM přes Java" h2="Převeďte soubor CGM na XLTM pomocí premise Java API v jakékoli Java J2SE, J2EE, J2ME aplikací" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete do svých aplikací Java integrovat funkci převodu CGM na XLTM ve dvou krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete vykreslit CGM do XLSX. Ve druhém kroku můžete převést XLSX na XLTM pomocí Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte soubor CGM na XLTM přes Java" %}}
1. Otevřete soubor CGM pomocí třídy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte CGM na XLSX pomocí [uložit](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte dokument XLSX pomocí třídy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu XLTM pomocí [SaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ve vašem pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Pokud je váš dokument CGM chráněn heslem, nemůžete jej bez hesla převést na XLTM. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předejte název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte chráněné CGM na XLTM přes Java" %}}
Při převodu souboru CGM na XLTM můžete také přidat vodoznak do výstupního formátu souboru XLTM. Chcete-li přidat vodoznak, vytvořte nový sešit a otevřete převedený soubor XLSX. Vyberte pracovní list přes jeho index, vytvořte tvar a použijte jeho funkci addTextEffect, nastavte barvy, průhlednost a další. Poté můžete uložit dokument XLSX jako XLTM s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-dif/" name="CGM Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-xltx/" name="CGM Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-md/" name="CGM Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-fods/" name="CGM Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-xltm/" name="CGM Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-excel/" name="CGM Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-xlsm/" name="CGM Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-xlam/" name="CGM Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-xlt/" name="CGM Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-xlsb/" name="CGM Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-ods/" name="CGM Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-sxc/" name="CGM Na SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}