---
title: Java API pro vykreslení MD do TXT
description: Export MD do TXT přes Java API bez použití Microsoft Excel nebo Adobe Reader
url_ignore: /cs/java/conversion/md-to-txt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: TXT
otherformats: ODS XLT XLTM XLSM TXT FODS XLTX XLSB DIF XLAM TSV EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Export MD do TXT přes Java" h2="Převeďte soubor MD na TXT pomocí premise Java API v jakékoli Java J2SE, J2EE, J2ME aplikací" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete do svých aplikací Java integrovat funkci převodu MD na TXT ve dvou krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete vykreslit MD do XLSX. Ve druhém kroku můžete převést XLSX na TXT pomocí Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte soubor MD na TXT přes Java" %}}
1. Otevřete soubor MD pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte MD na XLSX pomocí [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte dokument XLSX pomocí třídy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu TXT pomocí [SaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ve vašem pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Pokud je váš dokument MD chráněn heslem, nemůžete jej bez hesla převést na TXT. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předejte název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte chráněné MD na TXT přes Java" %}}
Při převodu souboru MD na TXT můžete také přidat vodoznak do výstupního formátu souboru TXT. Chcete-li přidat vodoznak, vytvořte nový sešit a otevřete převedený soubor XLSX. Vyberte pracovní list přes jeho index, vytvořte tvar a použijte jeho funkci addTextEffect, nastavte barvy, průhlednost a další. Poté můžete uložit dokument XLSX jako TXT s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Převádění souborů ve formátu Markdown (MD) na TXT (čistý text) vytváří čistou a lehkou verzi vašeho obsahu zbavenou formátování a značkování. Soubory TXT jsou vysoce kompatibilní, ideální pro zpracování textu, skriptování a integraci s aplikacemi, které nepodporují formátování Markdown.



{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}



* Exportování dokumentace ve formátu Markdown pro distribuci pomocí čistého textového e-mailu.

* Generování surového obsahu pro analýzu založenou na textu nebo pro pracovní postupy strojového učení.

* Vytváření lehkých, přenosných kopií poznámek a dokumentace.

* Sdílení obsahu ve formátu Markdown v prostředích, kde není podporováno bohaté formátování.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}



* Plánovaná hromadná konverze repozitářů Markdown do formátu TXT pro zálohování a archivaci.

* ETL potrubí transformující dokumentaci ve formátu Markdown do TXT pro zpracování skripty nebo nástroji pro automatizaci.

* Automatizované generování čistých textových protokolů z poznámek k projektům založeným na Markdown.

* Integrace s potrubími obsahu pro exportování Markdownu do formátu TXT pro následné systémy.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}