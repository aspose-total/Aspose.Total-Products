---
title: A OTT konvertálása ODP-re Java segítségével vagy ingyenes online konverterrel 
description: Java API a OTT exportálásához ODP-be Microsoft Word vagy PowerPoint használata nélkül vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes POT-CSV online konvertert. 
url_ignore: /hu/java/conversion/ott-to-odp/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: ODP
otherformats: PPTX PPTM PPS POTM POTX PPSX POWERPOINT POT PPT PPSM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A OTT konvertálása ODP-re Java segítségével vagy Online App" h2="OTT konvertálása ODP-be helyszíni Java API használatával bármely Java J2SE, J2EE, J2ME alkalmazáson belül Microsoft<sup>&reg;</sup> PowerPoint vagy Word használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A fejlesztőknek gyakran programozottan kell konvertálniuk a OTT fájlt ODP-vé. A File Automation Java könyvtárak [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával néhány egyszerű lépésben automatizálhatja a renderelési folyamatot. A OTT-fájlt az [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával töltheti be, és konvertálhatja HTML formátumba. Ezt követően a hatékony PowerPoint manipulációs Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) segítségével új prezentációt hozhat létre, HTML-tartalmat írhat bele, és ODP-ként mentheti. .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet OTT-t ODP-vé konvertálni Java-n keresztül" %}}
1. Nyissa meg a OTT-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
2. Alakítsa át a OTT fájlt HTML formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével)) módszer
3. Inicializáljon egy új [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) objektumot
5. Bontsa ki a tartalmat a HTML-fájlból a BufferedReader segítségével, és írja be a tartalmat a bemutatófájlba
6. Mentse a dokumentumot az ODP-be a [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A OTT-fájl ODP-vé konvertálásához egyszerűen használhatja az Aspose.Total for Java-t közvetlenül a [Maven]-ből (https://releases.aspose.com/total/java/) alapú projektet, és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-ott-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Ingyenes online konverter OTT-hez ODP-be</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=odp&from=ott" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API azt is lehetővé teszi, hogy jelszóval védett OTT dokumentumokat konvertáljon ODP-vé. Ha a bevitt OTT-dokumentum jelszóval védett, nem konvertálhatja ODP formátumba jelszó nélkül. A titkosított dokumentum megnyitásához beállíthatja a megfelelő jelszót a LoadOptions objektumban, és átadhatja a dokumentum konstruktorának.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-ott-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}