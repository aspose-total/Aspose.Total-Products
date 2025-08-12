---
title: Java API a CGM exportálásához MHTML-be
description: Konvertálja a CGM-et MHTML-re a helyszíni Java API használatával
url_ignore: /hu/java/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: XAMLFLOW DOTX WORDML OTT FLATOPC DOTM PCL ODT PS MHTML MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A CGM átalakítása MHTML-re Java segítségével" h2="On Premise Java API a CGM megjelenítéséhez MHTML-ben harmadik féltől származó alkalmazások használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépéssel a CGM-et MHTML-má konvertálhatja. Először is le kell renderelnie a CGM-fájlt DOC-ban az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Ezt követően a hatékony dokumentumfeldolgozási API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával a DOC-t MHTML-má konvertálhatja. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) csomagban található.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API a CGM MHTML-má konvertálásához" %}}
1. Nyissa meg a CGM-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. A [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) segítségével konvertálja a CGM-et DOC-vé ) módszerrel
3. Töltse be a DOC-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words osztály használatával
4. Mentse a dokumentumot MHTML formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) módszerrel, és állítsa be a MHTML-et mint SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
A CGM MHTML-re konvertálása közben még akkor is megnyithatja a PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) segítségével, ha dokumentuma jelszóval védett. A titkosított fájl megnyitásához létre kell hoznia egy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) objektumot, és meg kell nyitnia a CGM-et a tulajdonos jelszavával.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a jelszóval védett CGM-dokumentumot Java-n keresztül" %}}
Miközben a bemeneti dokumentumot MHTML fájlformátumba menti, fájlrendszer helyett adatbázisba is mentheti. Előfordulhat, hogy meg kell valósítania a dokumentumobjektumok tárolását és lekérését egy adatbázisba, illetve adatbázisból. Erre akkor lenne szükség, ha bármilyen típusú tartalomkezelő rendszert implementálna. A MHTML adatbázisba mentéséhez gyakran szükség van a dokumentum szerializálására egy bájttömb beszerzéséhez. Ezt az [Aspose.Words for Java](https://products.aspose.com/words/Java/) API használatával teheti meg. A bájttömb beszerzése után SQL utasítás segítségével tárolhatja az adatbázisban. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Az **Számítógépes Grafikus Metafájl (CGM)** fájlok átalakítása **MHTML (MIME HTML)** formátumba alapvető fontosságú a bonyolult mérnöki és technikai dokumentumok beágyazott grafikáinak megőrzése érdekében egyetlen, önálló fájlban. Az **Java alapú web archiválási rendszerekben** ez a konverzió lehetővé teszi a szervezetek számára, hogy teljes dokumentumokat tároljanak—beleértve a CGM vizuális elemeket, stílusokat és erőforrásokat—egy hordozható archívumban, amely alkalmas offline megtekintésre és intranet telepítésre. Az MHTML biztosítja, hogy a tervezési specifikációk, jelentések és rajzok hosszú távú hozzáférhetőség és terjesztés szempontjából érintetlenek maradjanak.

---

## ✅ Fő felhasználási esetek

- **Mérnöki dokumentumok csomagolása beágyazott grafikákkal**  
  Csomagolja be a CGM diagramokat és a kapcsolódó tartalmat MHTML formátumba a következetes, önálló technikai nyilvántartások érdekében.

- **Offline megtekintés az intranet portálokon**  
  Biztosítsa a CGM-mel kiegészített dokumentumokat MHTML formátumban a zökkenőmentes offline hozzáférés érdekében a vállalati hálózatokon keresztül.

- **Tervezési specifikációk archiválása**  
  Tárolja a CGM alapú specifikációk MHTML verzióit a szabályozás, hivatkozás és projekt dokumentáció céljából.

---

## ⚙️ Automatizálási forgatókönyvek

- **Java könyvtárak MHTML támogatással**  
  Használja az Aspose.Words for Java és egyedi Java exportálókat az MHTML fájlok létrehozásához a CGM alapú dokumentumokból.

- **Webes exportáló eszközök**  
  Integrálja a CGM-MHTML konverziót Java-alapú webes alkalmazásokba azonnali fájlcsomagolás érdekében.

- **Servlet-alapú konverziós munkafolyamatok**  
  Telepítsen olyan Java servlet-eket, amelyek feldolgozzák a CGM bemeneteket és MHTML archívumokat állítanak elő biztonságos terjesztés céljából.

- **Automatizált archiválási csővezetékek**  
  Tartalmazza a CGM-MHTML lépéseket a Java vezérelt dokumentumkezelő vagy ETL rendszerekben ütemezett archiválás érdekében.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}