---
title: Java API pro vykreslení XSLFO do XLTM
description: Export XSLFO do XLTM přes Java API bez použití Microsoft Excel nebo Adobe Reader
url_ignore: /cs/java/conversion/xslfo-to-xltm/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: XLTM
otherformats: TSV FODS SXC XLT XLTM EXCEL ODS MD DIF XLTX XLAM XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Export XSLFO do XLTM přes Java" h2="Převeďte soubor XSLFO na XLTM pomocí premise Java API v jakékoli Java J2SE, J2EE, J2ME aplikací" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete do svých aplikací Java integrovat funkci převodu XSLFO na XLTM ve dvou krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete vykreslit XSLFO do XLSX. Ve druhém kroku můžete převést XLSX na XLTM pomocí Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte soubor XSLFO na XLTM přes Java" %}}
1. Otevřete soubor XSLFO pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte XSLFO na XLSX pomocí [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte dokument XLSX pomocí třídy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu XLTM pomocí [SaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ve vašem pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Pokud je váš dokument XSLFO chráněn heslem, nemůžete jej bez hesla převést na XLTM. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předejte název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte chráněné XSLFO na XLTM přes Java" %}}
Při převodu souboru XSLFO na XLTM můžete také přidat vodoznak do výstupního formátu souboru XLTM. Chcete-li přidat vodoznak, vytvořte nový sešit a otevřete převedený soubor XLSX. Vyberte pracovní list přes jeho index, vytvořte tvar a použijte jeho funkci addTextEffect, nastavte barvy, průhlednost a další. Poté můžete uložit dokument XLSX jako XLTM s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Převod XSLFO na **XLTM (šablona Excelu s makry)** podporuje opakovaně použitelné sešity s vestavěnou automatizací. Šablony XLTM usnadňují opakované hlášení a pokročilé pracovní postupy.



{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}



* Standardizace XSLFO zpráv s vestavěnými makry pro automatizaci.

* Distribuce interaktivních šablon pro hlášení napříč odděleními.

* Příprava opakovaně použitelných šablon pro finanční modelování z XSLFO.

* Vytváření automatizovaných šablon sestav z tabulkových dat XSLFO.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}



* Hromadná generace šablon XLTM pro firemní hlášení.

* Integrace s automatizovanými pracovními postupy VBA.

* Plánovaný převod XSLFO na XLTM pro opakující se projekty.

* Spouštěná tvorba šablony XLTM pro analytické dashboardy řízené makry.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}