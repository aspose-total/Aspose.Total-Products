---
title: A DOCM konvertálása JSON formátumba Java segítségével
description: A DOCM konvertálása JSON formátumba Java segítségével Microsoft Word vagy Microsoft Excel használata nélkül
url_ignore: /hu/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A DOCM konvertálása JSON formátumba Java segítségével" h2="On Premise Java API a DOCM konvertálásához JSON formátumba Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A DOCM konvertálása JSON formátumba az [Aspose.Total for Java](https://products.aspose.com/total/java/) egy egyszerű kétlépéses folyamat. A funkciókban gazdag, dokumentumkezelési és -konverziós API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával DOCM-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával konvertálhatja a HTML-t JSON-ba.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="A DOCM konvertálása JSON formátumba Java segítségével" %}}
1. Nyissa meg a DOCM-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
2. A [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével konvertálja a DOCM-t HTML-vé. ) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot JSON formátumba a [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bevitt DOCM-dokumentum jelszóval védett, nem konvertálhatja azt JSON-formátumba a jelszó használata nélkül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban. A következő kódpélda bemutatja, hogyan próbáljon meg jelszóval megnyitni egy titkosított dokumentumot:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="A védett DOCM konvertálása JSON formátumba Java segítségével" %}}
Miközben a DOCM-t JSON-ba konvertálja, beállíthatja a kimeneti JSON-formátum tartományát is. A tartomány beállításához megnyithatja a konvertált HTML-t a Workbook osztály segítségével, létrehozhat egy tartományt exportálandó adatokból a Cells.createRange metódussal, meghívhatja a JsonUtility.exportRangeToJson metódust Range & ExportRangeToJsonOptions hivatkozásokkal, és karakterlánc JSON adatokat írhat a fájlba a következőn keresztül. BufferedWriter.write metódus. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Az **DOCM (Word Macro-Enabled Documents)** átalakítása **JSON (JavaScript Object Notation)** formátumba létfontosságú a statikus dokumentumtartalom, táblázatok és űrlapmezők **strukturált, gép által olvasható adattá** alakításához. A JSON könnyű, ember által olvasható és széles körben használt **API-kban, analitikában, webes alkalmazásokban és automatizálási folyamatokban**. A DOCM-ből való adatok kinyerésével JSON formátumba szervezetek képesek az interoperabilitás feloldására a modern platformokon, gyorsabb integrációk lehetővé tételére és az adatok készenlétbe hozására **valós idejű feldolgozásra, validálásra és skálázható terjesztésre**.  

## ✅ Fő felhasználási esetek  

- **Dokumentumadatok közzététele REST/GraphQL API-kon keresztül**  
  Szolgáltassa ki a kinyert DOCM tartalmat JSON formátumban közvetlen API-felhasználásra webes és mobilalkalmazásokban.  

- **NoSQL adatbázisok és adattavak táplálása**  
  Töltse be a DOCM-ből származó strukturált adatokat MongoDB-be, Elasticsearch-be vagy felhőalapú adattavakba.  

- **Műszerfalak meghajtása valós idejű JSON adatokkal**  
  Áramoltassa a dokumentumalapú KPI-kat és mutatókat BI műszerfalakba és monitorozó eszközökbe.  

- **Bemenetek ellenőrzése JSON séma alapján**  
  Biztosítsa a konzisztenciát és integritást a DOCM mezőadatainak összehangolásával a JSON séma szabályaival.  

- **Fej nélküli CMS vagy mikroszolgáltatás architektúrák lehetővé tétele**  
  Integrálja a DOCM tartalmat elosztott, API-centrikus rendszerekbe, ahol a JSON a lingua franca.  

## ⚙️ Automatizálási forgatókönyvek  

- **DOCM-to-JSON kinyerés mezőlek leképezésével**  
  Definiáljon leképezéseket a táblázatok, fejlécek és mezők átalakításához strukturált JSON objektumokká.  

- **Szerver nélküli funkciók, amelyek JSON eseményeket alakítanak és kibocsátanak**  
  Kiváltásokat indítson fálfeltöltéskor, JSON terheléseket bocsátva ki eseményvezérelt rendszerekbe.  

- **ETL feladatok, amelyek normalizálják a típusokat és kulcsokat**  
  Szabványosítsa a DOCM exportokat következetes JSON struktúrákká az alárendelt analitikákhoz.  

- **Webhorgonyok, amelyek JSON-t tolják lefelé irányuló rendszerekbe**  
  Automatizálja a DOCM-to-JSON exportokat, amelyek táplálják a CRM-eket, ERP eszközöket vagy harmadik féltől származó alkalmazásokat.  

- **Irányítási szabályok, amelyek eltávolítják a makrókat és PII-t a JSON export előtt**  
  Alkalmazzon megfelelőségi ellenőrzéseket annak érdekében, hogy biztonságos, szanitizált JSON kimeneteket biztosítson a makróval ellátott fájlokból.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}