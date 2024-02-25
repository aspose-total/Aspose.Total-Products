---
title: Konvertálja az POWERPOINT-t JSON formátumba Java segítségével
description: Konvertálja az POWERPOINT-t JSON formátumba Java segítségével Microsoft Excel vagy PowerPoint használata nélkül
url_ignore: /hu/java/conversion/powerpoint-to-json/
family: total
platformtag: net
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja az POWERPOINT-t JSON formátumba Java segítségével" h2="On Premise Java API az POWERPOINT exportálásához JSON-ba Microsoft<sup>&reg;</sup> Excel vagy PowerPoint használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az POWERPOINT konvertálása JSON formátumba az [Aspose.Total for Java](https://products.aspose.com/total/java/) egy egyszerű kétlépéses folyamat. Az első lépésben az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) használatával exportálhatja az POWERPOINT-t HTML-be. Másodszor, az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával konvertálhatja a HTML-t JSON-ba.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja az POWERPOINT-t JSON formátumba Java segítségével" %}}
1. Nyissa meg az POWERPOINT-fájlt a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. Alakítsa át az POWERPOINT-t HTML-vé a [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével. ISaveOptions-) metódus
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot JSON formátumba a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bevitt POWERPOINT-dokumentum jelszóval védett, nem konvertálhatja azt JSON-formátumba jelszó nélkül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a védett POWERPOINT-t JSON formátumba Java segítségével" %}}
Miközben az POWERPOINT-t JSON-ba konvertálja, beállíthatja a kimeneti JSON-formátum tartományát is. A tartomány beállításához megnyithatja a konvertált HTML-t a Workbook osztály segítségével, létrehozhat egy tartományt exportálandó adatokból a Cells.createRange metódussal, meghívhatja a JsonUtility.exportRangeToJson metódust Range & ExportRangeToJsonOptions hivatkozásokkal, és karakterlánc JSON adatokat írhat a fájlba a következőn keresztül. BufferedWriter.write metódus. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}