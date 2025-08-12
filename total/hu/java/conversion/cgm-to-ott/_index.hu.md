---
title: Java API a CGM exportálásához OTT-be
description: Konvertálja a CGM-et OTT-re a helyszíni Java API használatával
url_ignore: /hu/java/conversion/cgm-to-ott/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: OTT
otherformats: WORDML RTF ODT DOT DOTM XAMLFLOW PCL MHTML DOTX OTT MARKDOWN PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A CGM átalakítása OTT-re Java segítségével" h2="On Premise Java API a CGM megjelenítéséhez OTT-ben harmadik féltől származó alkalmazások használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépéssel a CGM-et OTT-má konvertálhatja. Először is le kell renderelnie a CGM-fájlt DOC-ban az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Ezt követően a hatékony dokumentumfeldolgozási API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával a DOC-t OTT-má konvertálhatja. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) csomagban található.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API a CGM OTT-má konvertálásához" %}}
1. Nyissa meg a CGM-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. A [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) segítségével konvertálja a CGM-et DOC-vé ) módszerrel
3. Töltse be a DOC-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words osztály használatával
4. Mentse a dokumentumot OTT formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) módszerrel, és állítsa be a OTT-et mint SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-ott.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
A CGM OTT-re konvertálása közben még akkor is megnyithatja a PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) segítségével, ha dokumentuma jelszóval védett. A titkosított fájl megnyitásához létre kell hoznia egy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) objektumot, és meg kell nyitnia a CGM-et a tulajdonos jelszavával.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a jelszóval védett CGM-dokumentumot Java-n keresztül" %}}
Miközben a bemeneti dokumentumot OTT fájlformátumba menti, fájlrendszer helyett adatbázisba is mentheti. Előfordulhat, hogy meg kell valósítania a dokumentumobjektumok tárolását és lekérését egy adatbázisba, illetve adatbázisból. Erre akkor lenne szükség, ha bármilyen típusú tartalomkezelő rendszert implementálna. A OTT adatbázisba mentéséhez gyakran szükség van a dokumentum szerializálására egy bájttömb beszerzéséhez. Ezt az [Aspose.Words for Java](https://products.aspose.com/words/Java/) API használatával teheti meg. A bájttömb beszerzése után SQL utasítás segítségével tárolhatja az adatbázisban. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Az **Computer Graphics Metafile (CGM)** fájlok átalakítása **OTT (OpenDocument Text Template)** formátumba létfontosságú az open-source és ODF-kompatibilis környezeteket használó szervezetek számára. A **Java alapú platformokon** ez a konverzió lehetővé teszi a CGM diagramok és műszaki vizuális elemek beágyazását újrafelhasználható sablonokba, amelyek kompatibilisek a LibreOffice és más OpenDocument szerkesztőkkel. Az OTT sablonok biztosítják a design konzisztenciát, elősegítik a közös szerkesztést, és egyszerűsítik az egységesített jelentések generálását a terjesztett csapatok számára, miközben fenntartják az interoperabilitásra vonatkozó nyílt szabványokat.


## ✅ Fő felhasználási esetek

- **ODF-kompatibilis jelentésgenerálás**  
  Hozzon létre szabványokon alapuló jelentéseket, ahol a CGM vizuális elemek zökkenőmentesen integrálódnak a strukturált OpenDocument tartalommal.

- **Közös dokumentumszerkesztés**  
  Tárolja a CGM-mel kiegészített OTT sablonokat megosztott tárolókban valós idejű, többfelhasználós szerkesztéshez open-source platformokon.


## ⚙️ Automatizálási forgatókönyvek

- **Java automatizálás konverter segítségével**  
  Használja az Aspose API-kat Java munkafolyamatokban a CGM fájlok átalakításához OTT sablonokká automatizált telepítés céljából.

- **LibreOffice SDK integrációk**  
  Használja a LibreOffice SDK-t Java alkalmazásokban a CGM-alapú OTT sablonok kitöltéséhez és testreszabásához.

- **ETL rendszerek nagy mennyiségű dokumentum létrehozásához**  
  Integrálja a CGM-OTT konverziót Java alapú ETL csövekbe nagy léptékű, sablonvezérelt dokumentumgenerálás céljából.

- **Open-source vállalati platformok**  
  Telepítse az OTT sablonokat beágyazott CGM diagramokkal Java-alapú tartalomkezelő és dokumentumautomatizáló rendszerekben.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}