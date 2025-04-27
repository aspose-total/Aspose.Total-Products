---
title: Převeďte CGM na TXT přes C# API
description: C# API pro převod souboru CGM do TXT bez použití Microsoft Excel nebo Adobe Reader
url_ignore: /cs/net/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API pro vykreslení CGM do TXT" h2="Export souboru CGM do TXT přes C# bez použití Microsoft<sup>&reg;</sup> Excel nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno převést soubor CGM na TXT v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET. Za prvé, pomocí [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete exportovat CGM do XLSX. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést XLSX na TXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod CGM na TXT" %}}
1. Otevřete soubor CGM pomocí třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte CGM na XLSX pomocí metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte dokument XLSX pomocí třídy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu TXT pomocí metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) a nastavte `Txt` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převést chráněné CGM na TXT přes C#" %}}
Pokud je váš dokument CGM chráněn heslem, nemůžete jej bez hesla převést na TXT. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) a předat název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést soubor CGM na TXT s vodoznakem přes C#" %}}
Při převodu souboru CGM na TXT můžete také přidat vodoznak do výstupního formátu souboru TXT. Chcete-li přidat vodoznak, můžete vytvořit nový objekt Workbook a otevřít převedený dokument XLSX, vybrat Worksheet přes jeho index, vytvořit Shape a použít jeho funkci AddTextEffect. Poté můžete uložit dokument XLSX jako TXT s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru CGM do TXT: Případy použití" %}}
CGM (Kompilované grafické metáfáily) soubory jsou určeny pro ukládání informací o vectorových grafech, čímž je činí ideálními pro tvorbu statických grafik a ilustrací. Nicméně při práci s dynamickými daty se stává textovými editory jako Notepad nezbytnými pro základní manipulaci textem a tvorbu dokumentace.

Přepisování CGM souborů do plain textových formátů je nezbytné, aby bylo možné uvolnit plnou potenciálku svých textových editních schopností. Toto přepisování vám umožňuje:

**Němci použití:**

*   **Dokumentace dat**: Přepisujte CGM soubory a vytvořte čitelnou dokumentaci, která usnadňuje sdílení a pochopení grafických informací.
*   **Manipulace textem**: Používáte Notepad pro editování a manipulaci s plain textovými daty vyňanými z CGM souborů, čímž je činíte vhodnými pro základní textové editační úlohy.
*   **Vytváření ASCII umění**: Přepisujte CGM soubory do ASCII artu, vytvářejte jednoduché textové znázornění grafik pro umělecké nebo dekorativní účely.
*   **Import dat do jiných nástrojů**: Používáte plain textový formát pro import grafických dat do jiných textových editorů či procesních programů, čímž rozšiřujete své možnosti manipulace textem.
*   ** Základní reporting a debugging**: Přepisujte CGM soubory a vytvořte základní hlásky a protokoly, které pomáhají identifikovat chyby a problémy během vývojového procesu.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}