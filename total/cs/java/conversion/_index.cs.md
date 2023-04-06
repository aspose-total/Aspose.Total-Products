---
title: Konverze formátu souboru přes Java 

description: Převádějte aplikace Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D obrázky, diagramy, video formáty a různé další formáty pomocí několika řádků kódu Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konverze formátu souboru přes Java" h2="Převádějte dokumenty Microsoft<sup>&reg;</sup> Office, PDF, obrázky, HTML a mnoho dalších souborů bez použití jiného softwaru." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library](https://products.aspose.com/total/java/) urychluje vývoj řešení pro manipulaci s dokumenty od nuly nebo vylepšuje stávající aplikace, aby bylo možné snadno spravovat dokumenty. API nejen vytváří, upravuje a převádí dokumenty Microsoft Office, ale také zpracovává PDF, HTML, obrázky TIFF, JPG, PNG, BMP a SVG, e-mailové soubory, video formáty, 3D, CAD a mnoho dalšího. Jedná se o soubor rozhraní API pro řešení pro správu dokumentů a manipulaci bez jakékoli softwarové závislosti v rámci jakýchkoli aplikací Java J2SE, J2EE, J2ME. Programátoři mohou snadno vytvářet, aktualizovat, vykreslovat, tisknout a převádět mezi nejoblíbenějšími formáty v rámci jakýchkoli aplikací založených na Javě.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konverze z Wordu do Excelu" %}}
Total API podporuje nejen inter konverzi formátů Microsoft Word, ale také konverzi Wordu do Excelu, PDF, HTML, obrázků, EPUB, Markdown a XPS. Proces konverze je jednoduchý. Podívejme se na případ převodu **Word do Excelu**. Načtěte soubor Microsoft Word pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) a převeďte **WORD do HTML** pomocí [Metoda uložení](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)). Dále otevřete převedený dokument HTML pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a uložte dokument do formátu XLSX pomocí [Uložit](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
 Vývojáři mohou také převést [Word do PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="Java Konverze z Wordu do Excelu" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="Převést PDF na obrázky" %}}
API podporuje převod PDF na obrázky jako JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel a další formáty. Pro převod PDF na obrázek uvažujme obrázek JPG jako cílový soubor. Proces je, načtěte soubor PDF pomocí třídy Document a inicializujte objekt [JpegDevice class](https://reference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) a vykreslete PDF do JPEG pomocí [Process](https ://apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) metoda
Načtěte soubor JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/aspose.imaging/image) a nakonec zavolejte metodu Save.

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte PowerPoint na soubory Excel" %}}

Pro převod souborů Microsoft PowerPoint do různých souborů, včetně Excel Word, MHTML, příslušných dílčích API zahrnutých do hlavního Aspose.Total pro Java API. Proces převodu souborů PowerPoint na dokument Excel, načtení souboru PowerPoint pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) a převod **PowerPoint do HTML** pomocí pomocí metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). Poté načtěte převedený dokument HTML pomocí třídy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a uložte dokument do formátu EXCEL pomocí [uložit](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)). Kód pro převod **PowerPoint do Wordu** je také uveden.

{{% blocks/products/pf/feature-page-code h3="Konverze Java PowerPoint do Excelu" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Konverze Java PowerPoint do Wordu" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}