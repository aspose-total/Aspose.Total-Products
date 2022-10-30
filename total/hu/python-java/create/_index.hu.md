---
title: Microsoft Excel-fájlok létrehozása és frissítése Python használatával 
url: /hu/python-java/create/
description: Hozzon létre Microsoft Excel munkalapjelentéseket a Microsoft Office telepítése nélkül 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Készítsen Excel-jelentéseket Python segítségével" h2="Hozzon létre és frissítsen Microsoft Excel SpreadSheets XLS, XLSX dokumentumokat a Python Applications alkalmazásban a Microsoft Office<sup>&reg;</sup> telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) egy Python API dokumentumok létrehozására, olvasására és írására Microsoft Excel formátumokban, beleértve az XLS-t és az XLSX-et. Ez az API az [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) csomag része. Ezenkívül a fejlesztők könnyen írhatnak kódot adatok, képek, diagramok, pivot táblák munkalapokba történő beillesztéséhez és sok más funkcióhoz. A Python API olyan funkciókat is támogat, mint például a különböző [Képletek](https://docs.aspose.com/cells/python-java/supported-formula-functions/) beállítása, a szöveg oszlopokká alakítása, az intelligens jelölő és a dinamikus képletbeállítások. Az alábbiakban néhány példakód található a táblázatok létrehozásához és módosításához.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Hogyan készítsünk Excel fájlokat Python segítségével" %}}

Az [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API munkafüzet osztályt biztosít, amely kezeli a fájlok létrehozását. A folyamat egyszerű. Hozza létre a Workbook osztály objektumot, és az index megadásával érje el a megfelelő munkalapot. Használja a putValue metódust a tartalom hozzáadásához az elért cellába, végül hívja meg a save() metódust, hogy mentse a dokumentumot adott néven.

{{% blocks/products/pf/feature-page-code h3="1. kód – Egyszerű Excel-fájl létrehozása" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="2. kód – Képek beszúrása a Microsoft Excel dokumentumokba" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Excel fájlok frissítése Python használatával" %}}

Az Excel-fájl létrehozásának és frissítésének folyamata az egyetlen különbség kivételével szinte azonos. A különbség az, hogy a létrehozási folyamat során az üres munkafüzet objektum jön létre, míg a frissítési folyamat során meglévő Excel fájlra van szükség. Tehát adja át a meglévő fájlt paraméterként a Workbook osztálynak. Pihenjen az eljárás ugyanaz

{{% blocks/products/pf/feature-page-code h3="3. kód – Frissítse a Microsoft Excel dokumentumokat" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}