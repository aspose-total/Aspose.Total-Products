---
title: Konvertera JSON-format till POT via C++
description: Analysera JSON till POT i C++ utan att använda Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POT
otherformats: OTP ODP PPSX PPT POTM PPS PPTM POTX PPSM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera JSON-format till POT via C++" h2="C++ API för att tolka JSON till POT utan att använda Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera JSON till POT i vilken C++-applikation som helst i två enkla steg. För det första, genom att använda [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), kan du analysera JSON till PPTX. Efter det, genom att använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), kan du konvertera PPTX till POT. Båda API:erna kommer under paketet [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera JSON-format till POT via C++" %}}
1. Skapa ett nytt [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objekt och läs giltig JSON-data från filen
2. Spara JSON som PPTX med metoden [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Ladda PPTX-dokument genom att använda klassen [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Spara dokumentet i POT-format med metoden [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera via Package Manager-konsolen i Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ställ in layout och konvertera JSON-format till POT via C++" %}}
När du analyserar JSON till POT kan du också ställa in storleken på rader och kolumner genom att ladda JSON med klassen [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Om du behöver ställa in samma radhöjd för alla rader i kalkylbladet kan du göra det genom att använda [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467 ) metoden för samlingen [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). På samma sätt, för att ställa in samma kolumnbredd för alla kolumner i kalkylbladet, använd ICells-samlingens [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b5) metod.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera JSON-format till POT med vattenstämpel i C++" %}}
Med hjälp av API:t kan du också konvertera JSON till POT med vattenstämpel. För att lägga till ett vattenmärke till ditt POT-dokument kan du först analysera JSON till PPTX och lägga till ett vattenmärke till det. För att lägga till en vattenstämpel, ladda den nyskapade PPTX-filen med klassen [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), hämta den första bilden, Lägg till en AutoShape av typen Rectangle, lägg till TextFrame till Rectangle, skapa Paragraph-objektet för en textram, skapa Portion-objekt för stycke, lägg till vattenstämpel med set_Text() och kan spara dokumentet till POT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}