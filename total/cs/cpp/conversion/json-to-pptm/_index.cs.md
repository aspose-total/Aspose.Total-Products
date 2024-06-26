---
title: Převeďte formát JSON na PPTM přes C++
description: Analyzujte JSON na PPTM v C++ bez použití Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPTM
otherformats: PPS PPSM ODP POWERPOINT POT POTX POTM PPT PPSX OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte formát JSON na PPTM přes C++" h2="C++ API pro analýzu JSON na PPTM bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
JSON můžete převést na PPTM v jakékoli aplikaci C++ ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) můžete analyzovat JSON na PPTX. Poté můžete pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) převést PPTX na PPTM. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte formát JSON na PPTM přes C++" %}}
1. Vytvořte nový objekt [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) a načtěte platná data JSON ze souboru
2. Uložte JSON jako PPTX pomocí metody [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Uložte dokument do formátu PPTM pomocí metody [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Nainstalujte pomocí konzoly Package Manager Console sady Visual Studio pomocí ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nastavte rozložení a převeďte formát JSON na PPTM přes C++" %}}
Při analýze JSON na PPTM můžete také nastavit velikost řádků a sloupců načtením JSON s třídou [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Pokud potřebujete nastavit stejnou výšku řádku pro všechny řádky v listu, můžete to udělat pomocí [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) metoda sbírky [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Podobně, chcete-li nastavit stejnou šířku sloupce pro všechny sloupce v listu, použijte [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) kolekce ICells
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte formát JSON na PPTM s vodoznakem v C++" %}}
Pomocí API můžete také převést JSON na PPTM s vodoznakem. Chcete-li do dokumentu PPTM přidat vodoznak, můžete nejprve analyzovat JSON na PPTX a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), získejte první snímek, Přidat AutoShape typu Rectangle, přidat TextFrame do Rectangle, vytvořit objekt Odstavec pro textový rámeček, vytvořit objekt Portion pro odstavec, přidat vodoznak pomocí set_Text() a uložit dokument do PPTM.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}