---
title: Java API pro vykreslení XPS do FODS
description: Export XPS do FODS přes Java API bez použití Microsoft Excel nebo Adobe Reader
url_ignore: /cs/java/conversion/xps-to-fods/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: FODS
otherformats: DIF FODS XLTM XLSM ODS XLT TSV MD XLSB EXCEL XLTX TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Export XPS do FODS přes Java" h2="Převeďte soubor XPS na FODS pomocí premise Java API v jakékoli Java J2SE, J2EE, J2ME aplikací" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete do svých aplikací Java integrovat funkci převodu XPS na FODS ve dvou krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete vykreslit XPS do XLSX. Ve druhém kroku můžete převést XLSX na FODS pomocí Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte soubor XPS na FODS přes Java" %}}
1. Otevřete soubor XPS pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte XPS na XLSX pomocí [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte dokument XLSX pomocí třídy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu FODS pomocí [SaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ve vašem pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Pokud je váš dokument XPS chráněn heslem, nemůžete jej bez hesla převést na FODS. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předejte název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte chráněné XPS na FODS přes Java" %}}
Při převodu souboru XPS na FODS můžete také přidat vodoznak do výstupního formátu souboru FODS. Chcete-li přidat vodoznak, vytvořte nový sešit a otevřete převedený soubor XLSX. Vyberte pracovní list přes jeho index, vytvořte tvar a použijte jeho funkci addTextEffect, nastavte barvy, průhlednost a další. Poté můžete uložit dokument XLSX jako FODS s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Převod XPS na **FODS (Flat OpenDocument Spreadsheet)** zajišťuje kompatibilitu se sešity s otevřeným zdrojovým kódem pro LibreOffice a OpenOffice. Ideální pro organizace používající dodavatelsky neutrální, multiplatformní řešení.



{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}



* Datové sady akademických a výzkumných projektů pro spolupracovní úpravy.

* Finanční zprávy s otevřeným zdrojovým kódem pro neziskové organizace nebo vládní instituce.

* Technické datové listy a provozní záznamy ve formátech s otevřeným zdrojovým kódem.

* Sdílení sešitů mezi týmy na různých platformách.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}



* Automatizované konverzní procesy XPS na FODS pro výzkumné laboratoře.

* Integrace s otevřenými ERP nebo analytickými systémy.

* Plánované aktualizace pro provozní sešity.

* Zjednodušená spolupráce pomocí otevřených dokumentových formátů.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}