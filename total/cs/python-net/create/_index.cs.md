---
title: Vytvořte soubor pomocí Pythonu 
url: /cs/python-net/create/
description: Vytvářejte textové dokumenty a dokumenty Microsoft Word bez instalace sady Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vytvářejte dokumenty pomocí Pythonu" h2="Vytvářejte textové soubory a soubory Microsoft Word DOCX, DOC v aplikacích Python bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Ukládání dat je základem každé softwarové aplikace v závislosti na povaze aplikace. Místo uložení může být databáze, XML, JSON, textové soubory, sestavy Excel nebo dokumenty Microsoft Word. File I/O je součástí jakéhokoli jazyka a většinou jazyky včetně Pythonu podporují zápis dat do textových souborů. Podívejme se na jazyk Python. Zápis existujících textových souborů pomocí Pythonu, poskytuje pro tyto úkoly metodu otevírání, zápisu a zavření. Nejprve otevřete soubor s příslušnou cestou k souboru a připojte nebo zapište funkci jako argumenty. Poté zapište požadovaný text do souboru a nakonec soubor zavřete pomocí metody close(). 

Pro vytváření dokumentů Microsoft Word pomocí Pythonu používáme balíček [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API, který má [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API jako součást svého balíčku. Toto API poskytuje kompletní řešení pro automatizaci dokumentů pro faktury, zprávy a technické články. Postup tvorby wordového dokumentu je uveden níže.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Jak vytvořit textový soubor pomocí Pythonu" %}}

Vytváření a zápis do textových souborů je jednoduchý. Python poskytuje metodu open() se třemi parametry a musí použít jeden z parametrů spolu s cestou k souboru. Tři parametry jsou "x", "a" a "w". Zadáním "x" bude vytvořen nový soubor, ale vyvolá chybu v případě, že soubor již existuje. Zadáním "a" se vytvoří nový textový soubor, pokud neexistuje, a pokud existuje, bude obsah připojen na konec. A nakonec poskytnutím "w" bude vytvořen nový textový dokument a přepsán novým obsahem v případě, že již existuje.

{{% blocks/products/pf/feature-page-code h3="Python - Vytvořte textový soubor" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvářejte dokumenty Microsoft Word" %}}

Total Python Word API má několik funkcí včetně vytváření souborů Microsoft Word, vkládání obrázků a textu do dokumentů, přidávání tabulek a seznamů do souborů a také snadné úpravy existujících dokumentů. Chcete-li vytvořit proces dokumentu Microsoft Word, vytvořte objekt tříd [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) a [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/). Přidejte požadovaný text, odstavec, seznamy a tabulky do dokumentu a nakonec jej uložte.

{{% blocks/products/pf/feature-page-code h3="Python – Vytvářejte dokumenty Microsoft Word" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}