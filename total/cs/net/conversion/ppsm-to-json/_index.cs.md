---
title: Převeďte PPSM do formátu JSON přes .NET
description: Převeďte PPSM na JSON v C# bez použití Microsoft Excel nebo Powerpoint
url_ignore: /cs/net/conversion/ppsm-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést PPSM na formát JSON přes C#" h2="Exportujte PPSM do JSON přes C# bez použití Microsoft<sup>&reg;</sup> Excel nebo PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete převést PPSM na formát JSON v rámci libovolné aplikace .NET, C#, ASP.NET a VB.NET ve dvou jednoduché kroky. Za prvé, pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) můžete exportovat PPSM do HTML. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést HTML na JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést PPSM na formát JSON přes C#" %}}
1. Otevřete soubor PPSM pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
2. Převeďte PPSM na HTML pomocí metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Načtěte dokument HTML pomocí třídy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu JSON pomocí metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převést chráněný PPSM na formát JSON přes C#" %}}
Pomocí rozhraní API můžete také otevřít dokument chráněný heslem. Pokud je váš vstupní dokument PPSM chráněn heslem, nemůžete jej převést do formátu JSON bez použití hesla. Rozhraní API vám umožňuje otevřít zašifrovaný dokument předáním správného hesla v objektu LoadOptions. Následující příklad kódu ukazuje, jak otevřít zašifrovaný dokument pomocí hesla.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést PPSM na JSON v rozsahu přes C#" %}}
Zatímco převádíte PPSM na JSON, můžete také nastavit rozsah výstupního formátu JSON. Chcete-li nastavit rozsah, můžete otevřít převedený HTML pomocí třídy Workbook, získat CellsCollection listu obsahujícího data, vytvořit rozsah z CellsCollection zadáním indexů řádků a sloupců a zavolat metodu ExportRangeToJson s odkazy na objekty Range & ExportRangeToJsonOptions. Nakonec můžete data JSON uložit do souboru pomocí metody File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}