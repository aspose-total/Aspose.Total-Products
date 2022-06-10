---
title: Fájlformátum konvertálása C# segítségével 
url: /hu/net/conversion/
description: Konvertálja a Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D képeket, diagramokat, videoformátumokat és sok más népszerű fájlt néhány sornyi C# kóddal.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Fájlformátum konvertálása C# segítségével .NET" h2="Konvertálja a Microsoft<sup>&reg;</sup> Office-fájlokat, PDF-eket, képeket, HTML-fájlokat és különféle egyéb formátumokat bármilyen más szoftver használata nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}
[.NET Total Library](https://products.aspose.com/total/net/) felgyorsítja a dokumentumkezelési megoldások fejlesztését a semmiből, vagy a meglévő alkalmazások fejlesztését a dokumentumkezelés egyszerű kezelése érdekében. Az API nem csak a Microsoft Office dokumentumokat kezeli, hanem PDF, HTML, TIFF, JPG, PNG, BMP és SVG képeket, e-mail fájlokat, videóformátumokat, GIS adatformátumokat és még sok mást is kezel. Ez a dokumentumkezelési és -manipulációs megoldási API-k teljes készlete, szoftverfüggőségek nélkül. A programozók könnyedén létrehozhatnak, frissíthetnek, renderelhetnek, nyomtathatnak és konvertálhatnak a legnépszerűbb formátumok között bármely .NET-alapú alkalmazáson belül.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="A Word konvertálása PDF-be" %}}
A Total API nem csak a Microsoft Word formátumok interkonverzióját támogatja, hanem a Word PDF, HTML, Images, EPUB, Markdown és XPS formátumba való konvertálását is. Az átalakítás folyamata egyszerű. Töltse be a dokumentumot a Dokumentum osztályon keresztül, és hívja meg a Mentés metódust célformátummal. Ez olyan egyszerű. A fejlesztők ellenőrizhetik a [konverzió eredményét](https://products.aspose.com/words/net/conversion/word-to-pdf/) a **Word PDF-be** kódintegrációja előtt


{{% blocks/products/pf/feature-page-code h3="C# - Konverzió Word-ből PDF-be" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="PDF konvertálása képekké" %}}
Az API támogatja a PDF konvertálását Images, Powerpoint, Excel és más formátumokká. A PDF-kép konvertáláshoz tekintsük a JPG-képet célfájlnak. A folyamat a következő: töltsön be PDF-fájlt a Document osztály segítségével, és inicializálja a [JpegDevice class](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) objektumot, majd a PDF-et JPEG formátumba rendereli a [Process](https) segítségével. ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) módszer
Töltse be a JPEG-fájlt az [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával, és végül hívja meg a Mentés metódust.

{{% blocks/products/pf/feature-page-code h3="C# - PDF konvertálás képpé" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Az Excel konvertálása Word és PowerPoint formátumba" %}}

A Microsoft Excel formátumok különböző fájlokká konvertálásához, beleértve a Word és a PowerPoint, a fő Aspose.Total .NET API-hoz kapcsolódó al API-kat. Az Excel-fájlok Word-dokumentummá konvertálásának folyamata, töltse be az EXCEL-fájlt a [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) osztály segítségével, majd először konvertálja az EXCEL-t PDF-be, majd állítsa a SaveFormat-ot Auto-ra. Ezután töltse be a konvertált PDF fájlt a Document class segítségével, és hívja meg a Mentés metódust, és állítsa be a Doc, Docx fájlt SaveFormatként. A kód a Microsoft **Excel–Powerpoint** konvertálásához is szerepel.

{{% blocks/products/pf/feature-page-code h3="C# – JSON konvertálása Excelbe" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# – Konverzió az Excelből JSON-ba" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}