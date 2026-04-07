---
title: Převeďte DOCX na MHTML v Pythonu
description: Formát webového archivu DOCX na mhtml a převod souborů HtmlFixed ve vašich aplikacích Python bez použití aplikace Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte DOCX na MHTML pomocí Pythonu" h2="Převod DOCX na MHTML, HtmlFixed a HTML ve vašich aplikacích Python bez instalace Microsoft Word<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat funkci převodu DOCX na MHTML (formát webového archivu) nebo HtmlFixed, znamená chtít uložit dokument ve formátu HTML pomocí absolutně umístěných prvků v aplikaci. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Je to plný balík různých API zabývajících se různými formáty. 

K přidání funkce převodu DOCX na MHTML používáme API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), které je součástí balíčku [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/). V případě, že je soubor DOCX jednoduchý, pak jsou to jen dva řádky kódu. Načtěte soubor DOCX a zavolejte metodu uložení s příslušnou cestou k souboru spolu s výčtem SaveFormat jako MHTML nebo HTML_FIXED. Ale v případě, že je potřeba obnovit model dokumentu co nejblíže původnímu, je potřeba do výsledného dokumentu uložit nějaké extra informace, tzv. round-trip information.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak Převeďte DOCX na MHTML v Pythonu" %}}
- Načtěte zdrojový soubor DOCX pomocí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Vytvořte instanci [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Nastavte export_roundtrip_information jako True
- Zadejte [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) jako MHTML
- Zavolejte metodu `save`, přičemž jako parametry zadejte cestu k výstupnímu souboru a SaveFormat. Váš soubor DOCX je tedy převeden na MHTML na zadané cestě.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}

- Pro převod formátu DOCX na MHTML nebo HtmlFixed je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Nebo použijte následující příkazy pip ```pip install aspose.words```
- Kromě toho operační systém založený na Microsoft Windows nebo Linux (viz více [Words](https://docs.aspose.com/words/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle pokynů [INSTALL](https://docs.aspose.com/words/python-net/installation/) krok za krokem.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit DOCX do MHTML v Pythonu – jednoduché" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Převod DOCX do MHTML v Pythonu" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

DOCX to MHTML conversion transforms word processing documents into web archive files that bundle HTML content and related resources into a single file. This format preserves document structure while enabling web-based viewing.

Python APIs allow DOCX-to-MHTML conversion to be integrated into automated publishing systems, web archiving workflows, and document sharing platforms.

{{% blocks/products/pf/agp/feature-section-col title="Klíčové případy použití" %}}

* **Generování webových archivů**  
  Převádí dokumenty DOCX do jednosouborových webových archivů.

* **Webové publikování dokumentů**  
  Umožňuje sdílet obsah dokumentu jako soubory kompatibilní s webem.

* **Offline prohlížení dokumentů**  
  Umožňuje prohlížet dokumenty bez externích závislostí.

* **Zachování obsahu**  
  Udržuje formátování a zdroje v jediném archivním souboru.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénáře automatizace" %}}

* **Automatizovaný export webových archivů**  
  Systémy mohou automaticky převádět soubory DOCX do archivů MHTML.

* **Dávkové publikační pipeline dokumentů**  
  Python skripty mohou generovat soubory webových archivů z dokumentů.

* **Systémy distribuce obsahu**  
  Dokumenty mohou být dynamicky převáděny do formátů webových archivů kompatibilních s webem.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}