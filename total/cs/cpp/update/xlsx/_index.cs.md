---
title: Aktualizujte soubor XLSX pomocí C++
description: Upravte dokument XLSX v aplikacích C++ bez použití aplikace Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualizujte soubor XLSX přes C++" h2="Upravujte tabulky XLSX prostřednictvím aplikací založených na C++ bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro programátora, který se snaží aktualizovat soubory XLSX v aplikaci C++, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API může pomoci automatizovat proces aktualizace. Je to úplný balík různých knihoven C++, které se zabývají více formáty včetně dokumentů Microsoft Excel. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API, které je součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/), usnadňuje tento proces úpravy. Proces aktualizace dokumentu XLSX je jednoduchý tím, že nejprve otevřete list a poté aktualizujete hodnotu buňky v Excelu pomocí C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak aktualizovat soubor XLSX v C++" %}}

- Načtěte soubor XLSX pomocí [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Přístup k příslušnému [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) pomocí GetIWorksheets()->GetObjectByIndex(0) a příslušné buňce pomocí GetICells()->GetObjectByIndex
- Pomocí metody PutValue vložte nová data do přístupné buňky
- Uložte soubor jako soubor .xlsx pomocí metody Save předáním souboru s cestou jako parametrem

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na úpravu" %}}

- Pro úpravu XLSX následuje [Požadavky na systém](https://docs.aspose.com/cells/cpp/system-requirements/) pro systémy Windows a Linux 
- Nainstalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp```
- Nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```
- Případně získejte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [Stahování](https://releases.aspose.comcells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kód - Aktualizujte soubor XLSX v C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}