---
title: C++ API för att exportera PCL till ODT
description: Konvertera PCL till ODT inom C++-applikationer.

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: ODT
otherformats: MARKDOWN MHTML DOT RTF FLATOPC OTT DOTM PS DOTX WORDML XAMLFLOW DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att exportera PCL till ODT" h2="Återge PCL till ODT inom C++-applikationer utan att kräva någon tredjepartsapplikation" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) filformatsautomatiseringsbibliotek tillåter C++-utvecklare att konvertera PCL till ODT i två enkla steg. För det första kan du använda [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API för att konvertera PCL-filformat till DOC. För det andra, genom att använda avancerad Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), kan du exportera DOC till ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att rendera PCL till ODT" %}}
1. Öppna PCL-filen med klassreferens [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konvertera PCL till DOC genom att använda medlemsfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Ladda DOC-filen med hjälp av [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klassreferens för Aspose.Words API
4. Spara dokumentet i ODT-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pcl");
// save PCL as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Odt
wordDoc->Save(u"output.Odt");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ändra lösenord för PCL-dokument via C++" %}}
I processen att rendera PCL till ODT kan du öppna en lösenordsskyddad PCL och även ändra dess lösenord. För att ändra lösenordet för en PCL-fil måste du känna till ägarlösenordet för det dokumentet. Du kan ladda lösenordsskyddade PDF-dokument med [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) genom att ange dess ägarlösenord och använda ChangePasswords-metoden för att ändra lösenordet.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PCL Document
auto doc = MakeObject<Document>(L"input.pcl", L"owner");
// change password of PCL Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Begränsa ODT-filredigering via C++" %}}
Du kan också begränsa redigering av ODT-filer genom att använda [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Ibland kan du behöva begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. API låter dig styra hur du begränsar innehållet med hjälp av uppräkningsparametern [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Följande kodexempel visar hur man begränsar redigering i ett dokument så att endast redigering i formulärfält är möjlig.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Odt");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-markdown/" name="PCL Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-mhtml/" name="PCL Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-dot/" name="PCL Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-rtf/" name="PCL Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-flatopc/" name="PCL Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-ott/" name="PCL Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-dotm/" name="PCL Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-ps/" name="PCL Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-dotx/" name="PCL Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-wordml/" name="PCL Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-xamlflow/" name="PCL Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pcl-to-odt/" name="PCL Till ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}