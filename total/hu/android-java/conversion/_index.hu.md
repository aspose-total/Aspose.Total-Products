---
title: Dokumentumkonverzió Android API-n keresztül 

description: Konvertálja a Word, Excel, PowerPoint, HTML, PDF és képformátumokat az Android konverziós API segítségével. Az Android az Office docx, xlsx, pptx fájlokat PDF formátumba konvertálja. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Dokumentumkonverzió Android API használatával" h2="Konvertálja a Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Képek és számos egyéb formátumot az Aspose.Total for Android segítségével Java segítségével." >}}

{{% blocks/products/pf/feature-page-summary %}}
A [Total Android API](https://products.aspose.com/total/android-java/) dokumentumkonverziós és -kezelési megoldást nyújt Android-alkalmazásokhoz anélkül, hogy bármilyen más szoftverre támaszkodna. A programozók egyszerűen automatizálhatják a dokumentumkezelési és -manipulációs megoldást az API új fejlesztésű vagy meglévő alkalmazásokba való integrálásával. Az API integrálásával a Programmer könnyen hozzáadhat olyan funkciókat, amelyek segítségével különféle formátumú dokumentumokat hozhat létre, szerkeszthet vagy konvertálhat az alkalmazáson belül. Az Android PDF Converter API kezeli az olyan konvertálási eseteket, mint az Office DOCX, XLSX, PPTX PDF-be és fordítva. Ezenkívül az alábbiakban felsorolt néhány API-val foglalkozó eset, és néhány hivatkozás található a releváns konverziós esetekhez. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PDF konvertálása CSV formátumba" %}}
A Total Android API támogatja a PDF-ből Excel XLSX-be és CSV-be való konvertálást. Ez egy két lépésből álló folyamat. Két Total API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) és [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) érintett. A folyamat az, hogy először rejtett PDF-et Excel XLSX formátumba, majd XLSX-et CSV formátumba. Részletesebben, töltse be a PDF-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztályon keresztül, és jelenítse meg XLSX-ben a [mentés](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) módszerrel. Ezután töltse be a renderelt XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával, és hívja meg a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metódus.

{{% blocks/products/pf/feature-page-code h3="Android - PDF konvertálás Excelbe" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Konverzió Excelből Wordbe" %}}
Az Android API kezeli az Excel konvertálását is. A folyamat a következő: töltse be az EXCEL XLSX fájlt a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály segítségével, és konvertálja az EXCEL-t PDF-be a SaveFormat automatikus beállításával. Ezután töltse be a mentett PDF-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával, és hívja meg a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) módszerrel mentheti a dokumentumot Word DOC/DOCX formátumba.

{{% blocks/products/pf/feature-page-code h3="Android - Konverzió Excelből Wordbe" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="A POWERPOINT konvertálása HTML és MHTML formátumba" %}}
Az Android Total API különféle formátumokkal foglalkozik, beleértve a PowerPoint fájlokat, így a prezentációkat HTML és MHTML formátumba tudja konvertálni. A folyamat a következő: töltse be a POWERPOINT PPT/PPTX fájlt a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával, és hívja meg a [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) metódus a POWERPOINT HTML-lé konvertálásához. Ezenkívül most töltse be a konvertált HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával, és hívja a [save](https://reference.aspose.com/cells/java/com.aspose.cells/) módszerrel az MHTML konverzióhoz. 
{{% blocks/products/pf/feature-page-code h3="Android – PowerPoint diák HTML-vé és MHTML-vé konvertálás" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}