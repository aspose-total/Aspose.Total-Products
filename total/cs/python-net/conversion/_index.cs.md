---
title: Konverze dokumentů přes Python 

description: Převeďte formáty Microsoft Word DOC, DOCX do PDF, obrázky a další, stejně jako prezentační snímky, e-mailové zprávy a 3D obrázky, jen několik řádků kódu Python.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konverze dokumentů pomocí Python API" h2="Převeďte Microsoft<sup>&reg;</sup> Office Word, PDF, obrázky a různé další formáty pomocí Aspose.Words pro Python přes .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python API](https://products.aspose.com/total/python-net/) urychluje vývoj řešení pro automatizaci dokumentů od nuly nebo vylepšování stávajících aplikací pro vytváření, úpravu nebo konverzi dokumentů, prezentací, e-mailů a 3D souborů. Python API nezpracovává pouze snímky Microsoft Office Word a prezentace, ale také zpracovává soubory PDF, HTML, obrázky a e-maily a mnoho dalšího. API nezávisí na žádném softwaru a je kompletní sadou řešení pro správu a manipulaci s dokumenty.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Převést Microsoft Word do PDF" %}}
Total Python API podporuje vícenásobnou konverzi formátů, jako je Microsoft Word do PDF, Obrázky, Markdown a HTML. Rozhraní API zjednodušuje proces převodu dokumentu aplikace Word do formátu PDF s kvalitním výstupem co nejblíže dokumentu jako soubor DOC, DOCX. Proces je načtení souboru DOC nebo DOCX do objektu [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) a stačí zavolat [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) s cílovým formátem PDF spolu s jeho cestou k adresáři. Je to tak jednoduché. V případě, že je potřeba specifikovat standardy PDF, jako je PDF 1.7 nebo 1.5, API poskytuje výčet [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/) pro nastavení [PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/). 

{{% blocks/products/pf/feature-page-code h3="Python - převod Word do PDF" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převod aplikace Microsoft Word na obrázky" %}}
Konverze Word to Images je hlavní funkcí Python API. Kromě pouhého převodu lze snadno nastavit různé možnosti uložení, jako je jas, kontrast, horizontální a vertikální rozlišení atd. Proces je načíst dokument přes objekt Document a poté zavolat metodu uložení s požadovanou příponou obrazového souboru se zadanou cestou. Pro specifikaci různých možností ukládání poskytuje API [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/), [FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) nebo [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) mohou být použit podle požadovaného scénáře. Níže uvedená ukázka kódu ukazuje vytvoření náhledu první stránky dokumentu s použitím některých dalších nastavení.

{{% blocks/products/pf/feature-page-code h3="Python – převod slova na obrázek" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést Microsoft PowerPoint do Wordu" %}}
Python API podporuje převod souborů Microsoft PowerPoint PPT / PPTX na soubory Word DOC / DOCX. Dvě rozhraní API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) a [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) použitý k provedení této konverze. Načtěte soubor PPT / PPTX pomocí [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/). Získejte objekt třídy Words Document. Iterujte každý snímek, vygenerujte a vložíte obrázek snímku a poté vložte text snímku iterací přes tvary snímků.

{{% blocks/products/pf/feature-page-code h3="Python – převod snímků aplikace PowerPoint do aplikace Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}