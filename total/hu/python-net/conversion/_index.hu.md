---
title: Dokumentumkonverzió Python segítségével 

description: Konvertálja a Microsoft Word formátumokat DOC, DOCX PDF-vé, képeket és sok mást, valamint prezentációs diákat, e-mail üzeneteket és 3D képeket csak néhány sor Python kóddal.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Dokumentumkonverzió Python API-k használatával" h2="Konvertálja a Microsoft<sup>&reg;</sup> Office Word-et, PDF-et, képeket és számos egyéb formátumot az Aspose.Words for Python segítségével .NET-en keresztül." >}}

{{% blocks/products/pf/feature-page-summary %}}
A [Total Python API-k](https://products.aspose.com/total/python-net/) felgyorsítják a dokumentumautomatizálási megoldások fejlesztését a semmiből, vagy a meglévő alkalmazások fejlesztését dokumentumok, prezentációk, e-mailek és 3D-fájlok létrehozásához, szerkesztéséhez vagy konvertálásához. A Python API nem csak a Microsoft Office Word és Presentation diákat kezeli, hanem a PDF-, HTML-, kép- és e-mail fájlokat és még sok mást is. Az API nem függ semmilyen szoftvertől, és a dokumentumkezelési és -manipulációs megoldások teljes készlete.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="A Microsoft Word konvertálása PDF-be" %}}
A Total Python API támogatja az olyan formátumok többszörös konvertálását, mint a Microsoft Word PDF-vé, Képek, Markdown és HTML. Az API leegyszerűsíti a Word-dokumentum PDF-be konvertálásának folyamatát, mivel a minőségi kimenet olyan közel van a dokumentumhoz, mint a DOC, DOCX fájlé. A folyamat a DOC- vagy DOCX-fájl betöltése a [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) objektumba, és csak hívja a [mentés](https://reference) .aspose.com/words/python-net/aspose.words/document/save/) metódus a cél PDF formátummal, valamint a könyvtár elérési útja. Ez olyan egyszerű. Ha olyan PDF szabványokat kell megadni, mint a PDF 1.7 vagy 1.5, az API [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/) felsorolást biztosít a beállításhoz. [PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/). 

{{% blocks/products/pf/feature-page-code h3="Python – Word-ből PDF-be konvertálás" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word konvertálása képekké" %}}
A Word képekké konvertálása a Python API anthor funkciója. Az egyszerű átalakításon kívül könnyen beállíthatunk különféle mentési beállításokat, mint például a fényerőt, kontrasztot, vízszintes és függőleges felbontást stb. A folyamat lényege, hogy betöltjük a dokumentumot a Document objektumon keresztül, majd meghívjuk a mentési módot a kívánt képfájl-kilépéssel, megadott elérési úttal. A különféle mentési beállítások megadásához az API a következőt kínálja: [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/), [FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) vagy [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) osztályok lehetnek a szükséges forgatókönyv szerint használják. Az alábbi kódminta bemutatja az első dokumentumoldal előnézetének létrehozását néhány további beállítás alkalmazásával.

{{% blocks/products/pf/feature-page-code h3="Python – Word-be konvertálás" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="A Microsoft PowerPoint konvertálása Word-be" %}}
A Python API támogatja a Microsoft PowerPoint PPT / PPTX konvertálását Word DOC / DOCX fájlokká. Két API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) és [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) az átalakításhoz. Töltse be a PPT/PPTX fájlt a [Presentation] segítségével (https://reference.aspose.com/slides/python-net/aspose.slides/presentation/). Szerezze be a Words Document osztály objektumot. Iteráljon az egyes diákon, létrehozza és beszúrja a diaképet, majd a diák alakzatainak iterálásával illessze be a dia szövegét.

{{% blocks/products/pf/feature-page-code h3="Python – PowerPoint diák konvertálása Wordbe" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}