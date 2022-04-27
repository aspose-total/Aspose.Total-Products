---
title: Převést DOCM na PPSX přes Java
description: Java API pro export DOCM do PPSX bez použití Microsoft Word nebo PowerPoint
url: /cs/java/conversion/docm-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: PPSX
otherformats: POTX PPTX PPSM POTM POT PPTM POWERPOINT PPS PPSX PPT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést DOCM na PPSX přes Java" h2="Konverze DOCM na PPSX pomocí místního rozhraní Java API v jakékoli aplikaci Java J2SE, J2EE, J2ME bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Často musí vývojáři převést soubor DOCM na PPSX programově. Pomocí knihoven File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete automatizovat proces vykreslování v několika jednoduchých krocích. Soubor DOCM můžete načíst pomocí [Aspose.Words for Java](https://products.aspose.com/words/java/) a převést jej do HTML. Poté pomocí výkonného rozhraní Java API pro manipulaci v PowerPointu [Aspose.Slides for Java](https://products.aspose.com/slides/java/) můžete vytvořit novou prezentaci, napsat do ní obsah HTML a uložit ji jako PPSX .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést DOCM na PPSX přes Java" %}}
1. Otevřete soubor DOCM pomocí třídy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Převeďte soubor DOCM do HTML pomocí [uložit](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions))) metoda
3. Inicializujte nový objekt [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Extrahujte obsah ze souboru HTML pomocí BufferedReader a zapište obsah do souboru prezentace
6. Uložte dokument do PPSX pomocí metody [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Pro konverzi souborů DOCM na PPSX můžete snadno použít Aspose.Total pro Java přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
API také umožňuje převádět dokumenty DOCM chráněné heslem na PPSX. Pokud je váš vstupní dokument DOCM chráněn heslem, nemůžete jej převést do formátu PPSX bez použití hesla. Chcete-li otevřít zašifrovaný dokument, můžete nastavit správné heslo v objektu LoadOptions a předat jej konstruktoru dokumentu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-ppsm/" name="DOCM Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-pot/" name="DOCM Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-powerpoint/" name="DOCM Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-pptx/" name="DOCM Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-potx/" name="DOCM Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-pptm/" name="DOCM Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-potm/" name="DOCM Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-pps/" name="DOCM Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-ppsx/" name="DOCM Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-ppt/" name="DOCM Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-csv/" name="DOCM Na CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-dif/" name="DOCM Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-fods/" name="DOCM Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-ods/" name="DOCM Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-sxc/" name="DOCM Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-tsv/" name="DOCM Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlam/" name="DOCM Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xltm/" name="DOCM Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-excel/" name="DOCM Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xls/" name="DOCM Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlsb/" name="DOCM Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlsm/" name="DOCM Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlsx/" name="DOCM Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlt/" name="DOCM Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xltm/" name="DOCM Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xltx/" name="DOCM Na XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}