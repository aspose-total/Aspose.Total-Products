---
title: Konvertera JSON-format till WORDML via C++
description: C++ API t0 Parse JSON till WORDML utan att använda Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: WORDML
otherformats: MOBI ODT DOTX DOT RTF EPUB CHM PCL DOC PS WORD OTT DOCM FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera JSON-format till WORDML via C++" h2="Analysera JSON till WORDML i C++-program utan att använda Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for C++](https://products.aspose.com/total/cpp/) kan du analysera JSON till WORDML i dina C++-applikationer i två enkla steg. För det första, genom att använda [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), kan du exportera JSON till PDF. Efter det, genom att använda [Aspose.Words for C++](https://products.aspose.com/words/cppp/), kan du konvertera PDF till WORDML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera JSON-format till WORDML i C++" %}}
1. Skapa ett nytt [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objekt och läs giltig JSON-data från filen
2. Spara JSON som PDF med metoden [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Ladda PDF-dokument genom att använda klassen [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Spara dokumentet i WORDML-format med metoden [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera via Package Manager-konsolen i Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ställ in layout och konvertera JSON-format till WORDML i C++" %}}
När du analyserar JSON till WORDML kan du också ställa in storleken på rader och kolumner genom att ladda JSON med klassen [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Om du behöver ställa in samma radhöjd för alla rader i kalkylbladet kan du göra det genom att använda [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467 ) metoden för samlingen [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). På samma sätt, för att ställa in samma kolumnbredd för alla kolumner i kalkylbladet, använd ICells-samlingens [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b5) metod.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera JSON-format till WORDML med vattenstämpel i C++" %}}
Med hjälp av API:t kan du också analysera JSON till WORDML med vattenstämpel. För att lägga till en vattenstämpel till ditt WORDML-dokument kan du först konvertera JSON till PDF och lägga till en vattenstämpel till den. För att lägga till en vattenstämpel, ladda den nyskapade PDF-filen med klassen [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), ställ in olika egenskaper för textvattenstämpel,
anrop SetText-metoden och skicka vattenstämpeltext och objekt för TextWatermarkOptions. När du har lagt till vattenstämpeln kan du spara dokumentet i WORDML.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}