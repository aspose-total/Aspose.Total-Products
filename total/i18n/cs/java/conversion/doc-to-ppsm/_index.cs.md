---
title: Převést DOC na PPSM přes Java
description: Java API pro export DOC do PPSM bez použití Microsoft Word nebo PowerPoint
url: /cs/java/conversion/doc-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: PPSM
otherformats: PPTX POWERPOINT PPSM POT PPSX PPS POTX POTM PPT PPTM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést DOC na PPSM přes Java" h2="Konverze DOC na PPSM pomocí místního rozhraní Java API v jakékoli aplikaci Java J2SE, J2EE, J2ME bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Často musí vývojáři převést soubor DOC na PPSM programově. Pomocí knihoven File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete automatizovat proces vykreslování v několika jednoduchých krocích. Soubor DOC můžete načíst pomocí [Aspose.Words for Java](https://products.aspose.com/words/java/) a převést jej do HTML. Poté pomocí výkonného rozhraní Java API pro manipulaci v PowerPointu [Aspose.Slides for Java](https://products.aspose.com/slides/java/) můžete vytvořit novou prezentaci, napsat do ní obsah HTML a uložit ji jako PPSM .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést DOC na PPSM přes Java" %}}
1. Otevřete soubor DOC pomocí třídy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Převeďte soubor DOC do HTML pomocí [uložit](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) metoda
3. Inicializujte nový objekt [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Extrahujte obsah ze souboru HTML pomocí BufferedReader a zapište obsah do souboru prezentace
6. Uložte dokument do PPSM pomocí metody [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Pro konverzi souborů DOC na PPSM můžete snadno použít Aspose.Total pro Java přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
API také umožňuje převádět dokumenty DOC chráněné heslem na PPSM. Pokud je váš vstupní dokument DOC chráněn heslem, nemůžete jej převést do formátu PPSM bez použití hesla. Chcete-li otevřít zašifrovaný dokument, můžete nastavit správné heslo v objektu LoadOptions a předat jej konstruktoru dokumentu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-doc-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-ppsm/" name="DOC Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-pot/" name="DOC Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-powerpoint/" name="DOC Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-pptx/" name="DOC Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-potx/" name="DOC Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-pptm/" name="DOC Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-potm/" name="DOC Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-pps/" name="DOC Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-ppsx/" name="DOC Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-ppt/" name="DOC Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-csv/" name="DOC Na CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-dif/" name="DOC Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-fods/" name="DOC Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-ods/" name="DOC Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-sxc/" name="DOC Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-tsv/" name="DOC Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-xlam/" name="DOC Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-xltm/" name="DOC Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-excel/" name="DOC Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-xls/" name="DOC Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-xlsb/" name="DOC Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-xlsm/" name="DOC Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-xlsx/" name="DOC Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-xlt/" name="DOC Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-xltm/" name="DOC Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/doc-to-xltx/" name="DOC Na XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}