---
title: Exportálja az EMLX-t JPEG-be C++-on keresztül
description: C++ API az EMLX JPEG-vé konvertálásához Microsoft Word vagy Outlook használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: JPEG
otherformats: SVG WORDML DOCX MD FLATOPC ODT DOT PCL EPUB BMP EMF DOC GIF TEXT OTT TIFF PDF DOCM PNG DOTM XPS DOTX RTF PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API az EMLX exportálásához JPEG-be" h2="Alakítsa át az EMLX-t JPEG-vé a C++ alkalmazáson belül Microsoft Word vagy Outlook nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ön C++ fejlesztő, aki e-mail-konverziós funkciókat szeretne hozzáadni alkalmazásaihoz? Az [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) használatával konvertálhatja az EMLX fájlformátumot HTML-re. Ezt követően az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API használatával exportálhatja a HTML-t JPEG-be. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API az EMLX JPEG-vé konvertálásához" %}}
1. Nyissa meg az EMLX fájlt a [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message) osztályhivatkozás használatával
2. Alakítsa át az EMLX-t HTML-vé a [Mentés](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) tagfüggvény használatával
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály használatával
4. Mentse a dokumentumot JPEG formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) metódussal, és állítsa be a Jpeg-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Jpeg as save format
doc->Save(u"convertedFile.Jpeg");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Elemezze az EMLX fájlt C++ segítségével" %}}
Nemcsak EMLX-jét konvertálhatja JPEG-vé, hanem olvashatja, kezelheti és elemzi az EMLX dokumentumot. Az [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API MapiMessage osztályával az e-mail tárgyára, címére, törzsére és címzettjére vonatkozó információkat kaphat. Például a get_SenderEmlxAddress() tulajdonság használatával ellenőrizheti, hogy van-e egy adott feladó e-mail a konverzióhoz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlxAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API a JPEG fájlformátum szerkesztésének korlátozásához" %}}
Dokumentumvédelmi funkciókat is hozzáadhat az alkalmazáshoz, miközben exportálja a dokumentumot a EMLX címről a JPEG-be. A védelem hozzáadása a dokumentumhoz egy egyszerű folyamat, hiszen mindössze a védelmi módszert kell alkalmaznia a dokumentumra. A védelem típusát ReadOnly értékre állíthatja, hogy korlátozza a felhasználót a dokumentum szerkesztésében.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Jpeg");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-svg/" name="EMLX Nak nek SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-wordml/" name="EMLX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-docx/" name="EMLX Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-md/" name="EMLX Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-flatopc/" name="EMLX Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-odt/" name="EMLX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-dot/" name="EMLX Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-pcl/" name="EMLX Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-epub/" name="EMLX Nak nek EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-jpeg/" name="EMLX Nak nek JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-emf/" name="EMLX Nak nek EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-doc/" name="EMLX Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-gif/" name="EMLX Nak nek GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-text/" name="EMLX Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-ott/" name="EMLX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-tiff/" name="EMLX Nak nek TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-pdf/" name="EMLX Nak nek PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-docm/" name="EMLX Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-png/" name="EMLX Nak nek PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-dotm/" name="EMLX Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-xps/" name="EMLX Nak nek XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-dotx/" name="EMLX Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-rtf/" name="EMLX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/emlx-to-ps/" name="EMLX Nak nek PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}