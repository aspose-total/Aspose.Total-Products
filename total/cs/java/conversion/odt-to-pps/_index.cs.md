---
title: Převést ODT na PPS přes Java
description: Java API pro export ODT do PPS bez použití Microsoft Word nebo PowerPoint
url_ignore: /cs/java/conversion/odt-to-pps/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: PPS
otherformats: POTX POTM PPT POT PPTM PPTX PPSX PPS PPSM POWERPOINT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést ODT na PPS přes Java" h2="Konverze ODT na PPS pomocí místního rozhraní Java API v jakékoli aplikaci Java J2SE, J2EE, J2ME bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Často musí vývojáři převést soubor ODT na PPS programově. Pomocí knihoven File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete automatizovat proces vykreslování v několika jednoduchých krocích. Soubor ODT můžete načíst pomocí [Aspose.Words for Java](https://products.aspose.com/words/java/) a převést jej do HTML. Poté pomocí výkonného rozhraní Java API pro manipulaci v PowerPointu [Aspose.Slides for Java](https://products.aspose.com/slides/java/) můžete vytvořit novou prezentaci, napsat do ní obsah HTML a uložit ji jako PPS .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést ODT na PPS přes Java" %}}
1. Otevřete soubor ODT pomocí třídy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Převeďte soubor ODT do HTML pomocí [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
3. Inicializujte nový objekt [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Extrahujte obsah ze souboru HTML pomocí BufferedReader a zapište obsah do souboru prezentace
6. Uložte dokument do PPS pomocí metody [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Pro konverzi souborů ODT na PPS můžete snadno použít Aspose.Total for Java přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
API také umožňuje převádět dokumenty ODT chráněné heslem na PPS. Pokud je váš vstupní dokument ODT chráněn heslem, nemůžete jej převést do formátu PPS bez použití hesla. Chcete-li otevřít zašifrovaný dokument, můžete nastavit správné heslo v objektu LoadOptions a předat jej konstruktoru dokumentu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-ppsm/" name="ODT Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-pot/" name="ODT Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-powerpoint/" name="ODT Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-pptx/" name="ODT Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-potx/" name="ODT Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-pptm/" name="ODT Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-potm/" name="ODT Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-pps/" name="ODT Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-ppsx/" name="ODT Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-ppt/" name="ODT Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-csv/" name="ODT Na CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-dif/" name="ODT Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-fods/" name="ODT Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-ods/" name="ODT Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-sxc/" name="ODT Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-tsv/" name="ODT Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlam/" name="ODT Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xltm/" name="ODT Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-excel/" name="ODT Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xls/" name="ODT Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlsb/" name="ODT Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlsm/" name="ODT Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlsx/" name="ODT Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlt/" name="ODT Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xltm/" name="ODT Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xltx/" name="ODT Na XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}