---
title: Konverze formátu souboru přes C# 
url: /cs/net/conversion/
description: Převádějte aplikace Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D obrázky, diagramy, video formáty a mnoho dalších oblíbených souborů pomocí několika řádků kódu C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konverze formátu souboru přes C# .NET" h2="Převádějte soubory Microsoft<sup>&reg;</sup> Office, PDF, obrázky, HTML a různé další formáty bez použití jiného softwaru." >}}

{{% blocks/products/pf/feature-page-summary %}}
[.NET Total Library](https://products.aspose.com/total/net/) urychluje vývoj řešení správy dokumentů od nuly nebo vylepšení stávajících aplikací tak, aby snadno zvládaly manipulaci s dokumenty. API nejen spravuje dokumenty Microsoft Office, ale také zpracovává PDF, HTML, obrázky TIFF, JPG, PNG, BMP a SVG, e-mailové soubory, video formáty, datové formáty GIS a mnoho dalšího. Jedná se o kompletní sadu rozhraní API pro správu dokumentů a manipulaci bez jakýchkoli softwarových závislostí. Programátoři mohou snadno vytvářet, aktualizovat, vykreslovat, tisknout a převádět mezi nejoblíbenějšími formáty v rámci jakékoli aplikace založené na .NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Převést Word do PDF" %}}
Total API podporuje nejen inter konverzi formátů Microsoft Word, ale také konverzi Wordu do PDF, HTML, obrázků, EPUB, Markdown a XPS. Proces konverze je jednoduchý. Načtěte dokument přes třídu Document a zavolejte metodu Uložit s cílovým formátem. Je to tak jednoduché. Vývojáři mohou zkontrolovat [výsledek konverze](https://products.aspose.com/words/net/conversion/word-to-pdf/) před integrací kódu **Word do PDF**


{{% blocks/products/pf/feature-page-code h3="C# - převod Word do PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Převést PDF na obrázky" %}}
API podporuje převod PDF do obrázků, Powerpoint, Excel a dalších formátů. Pro převod PDF na obrázek uvažujme obrázek JPG jako cílový soubor. Proces je, načtěte soubor PDF pomocí třídy Document a inicializujte objekt [JpegDevice class](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) a vykreslete PDF do JPEG přes [Process](https ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metoda
Načtěte soubor JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) a nakonec zavolejte metodu Save.

{{% blocks/products/pf/feature-page-code h3="C# - Převod PDF na obrázek" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte Excel do Wordu a PowerPointu" %}}

Pro převod formátů Microsoft Excel do různých souborů, včetně Wordu a PowerPointu, Relevantní dílčí API zapojené do hlavního Aspose.Total pro .NET API. Proces převodu souborů Excel na dokument Word, načtení souboru EXCEL pomocí třídy [Sešit](https://reference.aspose.com/cells/net/aspose.cells/workbook) a nejprve převeďte EXCEL do PDF a nastavte SaveFormat na Auto. Poté načtěte převedený soubor PDF pomocí třídy Document a zavolejte metodu Save a nastavte Doc, Docx jako SaveFormat. Uvedený kód také pro převod Microsoft **Excel do Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="C# - Převod JSON do Excelu" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - převod Excel do JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}