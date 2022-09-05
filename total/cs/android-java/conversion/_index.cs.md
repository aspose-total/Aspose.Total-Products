---
title: Konverze dokumentů přes Android API 
url: /cs/android-java/conversion/
description: Převeďte formáty Word, Excel, PowerPoint, HTML, PDF a obrázky pomocí rozhraní API pro převod Android. Android převést Office docx, xlsx, pptx do PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konverze dokumentů pomocí Android API" h2="Převeďte Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, obrázky a různé další formáty pomocí Aspose.Total pro Android přes Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) poskytuje řešení pro převod a správu dokumentů pro aplikace Android, aniž by se spoléhalo na jakýkoli jiný software. Programátoři mohou snadno automatizovat řešení pro správu a manipulaci s dokumenty integrací API do nově vyvinutých aplikací nebo do stávajících aplikací. Díky integraci rozhraní API může programátor snadno přidávat funkce pro vytváření, úpravu nebo převod dokumentů různých formátů v rámci aplikace. PDF Converter API v Androidu zpracovává případy převodu jako Office DOCX, XLSX, PPTX do PDF nebo naopak. Kromě toho je níže uvedeno několik případů, které API řeší, a několik odkazů uvedených pro relevantní případy konverze. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Převést PDF do CSV" %}}
Total Android API podporuje převod PDF do Excelu XLSX a CSV. Je to dvoukrokový proces. Dvě rozhraní Total API [Aspose.PDF pro Android přes Javu](https://products.aspose.com/pdf/android-java/) a Aspose.Cells pro Android přes Javu](https://products.aspose.com/ buňky/android-java/). Proces je, že můžete nejprve převést PDF do formátu Excel XLSX a poté XLSX do CSV. Podrobněji načtěte soubor PDF přes třídu [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) a vykreslete do XLSX přes [uložit](https://reference. metoda aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). Poté načtěte vykreslený dokument XLSX pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a vyvolejte [uložit](https://reference.aspose.com /cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).

{{% blocks/products/pf/feature-page-code h3="Android – převod PDF do Excelu" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Převod Excelu do Wordu" %}}
Android API zvládá i převod Excelu. Postup je, načtěte soubor EXCEL XLSX pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a nejprve převeďte EXCEL do PDF nastavením SaveFormat na AUTO. Poté načtěte uložený soubor PDF pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) a vyvolejte [uložit](https://reference.aspose.com/ pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) k uložení dokumentu do formátu Word DOC / DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Převod Excelu do Wordu" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Převést POWERPOINT na HTML a MHTML" %}}
Android Total API se zabývá různými formáty včetně souborů PowerPoint, takže lze převádět prezentace do HTML a MHTML. Proces je, načtěte soubor POWERPOINT PPT/PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) a vyvolejte [uložit](https://reference.aspose .com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) pro převod POWERPOINT do HTML. Nyní navíc načtěte převedený dokument HTML pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a zavolejte [uložit](https://reference.aspose .com/cells/java/com.aspose.cells/) pro konverzi MHTML. 
{{% blocks/products/pf/feature-page-code h3="Android – Konverze snímků PowerPoint do HTML a MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}