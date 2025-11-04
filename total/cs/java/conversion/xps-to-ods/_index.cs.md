---
title: Java API pro vykreslení XPS do ODS
description: Export XPS do ODS přes Java API bez použití Microsoft Excel nebo Adobe Reader
url_ignore: /cs/java/conversion/xps-to-ods/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: ODS
otherformats: XLTX TSV XLSB ODS SXC DIF FODS TXT MD EXCEL XLAM XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Export XPS do ODS přes Java" h2="Převeďte soubor XPS na ODS pomocí premise Java API v jakékoli Java J2SE, J2EE, J2ME aplikací" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete do svých aplikací Java integrovat funkci převodu XPS na ODS ve dvou krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete vykreslit XPS do XLSX. Ve druhém kroku můžete převést XLSX na ODS pomocí Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte soubor XPS na ODS přes Java" %}}
1. Otevřete soubor XPS pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte XPS na XLSX pomocí [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte dokument XLSX pomocí třídy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu ODS pomocí [SaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ve vašem pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Pokud je váš dokument XPS chráněn heslem, nemůžete jej bez hesla převést na ODS. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předejte název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte chráněné XPS na ODS přes Java" %}}
Při převodu souboru XPS na ODS můžete také přidat vodoznak do výstupního formátu souboru ODS. Chcete-li přidat vodoznak, vytvořte nový sešit a otevřete převedený soubor XLSX. Vyberte pracovní list přes jeho index, vytvořte tvar a použijte jeho funkci addTextEffect, nastavte barvy, průhlednost a další. Poté můžete uložit dokument XLSX jako ODS s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Převod XPS na **ODS (OpenDocument Spreadsheet)** umožňuje širokou kompatibilitu jak s LibreOffice, tak s OpenOffice, přičemž zachovává strukturované rozložení dat. Ideální pro spolupracovní prostředí.



{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}



* Podnikové tabulky sdílené napříč různými kancelářskými balíky.

* Zprávy o datech vládních institucí nebo neziskových organizací vyžadující otevřené formáty.

* Sledování týmových projektů a výkonnostních metrik.

* Technická a výzkumná dokumentace ve formě tabulky.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}



* Hromadný automatizovaný převod z archivů XPS do ODS.

* Integrace do systémů správy dokumentů a pracovních postupů.

* Plánovaná generace ODS pro opakující se zprávy.

* Automatické distribuce dat napříč platformami.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}