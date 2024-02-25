---
title: Exportálja az EMLX-t WORDML-be C++-on keresztül
description: C++ API az EMLX WORDML-vé konvertálásához Microsoft Word vagy Outlook használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: WORDML
otherformats: TIFF BMP DOTX PNG MD JPEG PS ODT XPS TEXT DOC PCL DOCX OTT EMF PDF DOCM FLATOPC GIF SVG DOTM DOT EPUB RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API az EMLX exportálásához WORDML-be" h2="Alakítsa át az EMLX-t WORDML-vé a C++ alkalmazáson belül Microsoft Word vagy Outlook nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ön C++ fejlesztő, aki e-mail-konverziós funkciókat szeretne hozzáadni alkalmazásaihoz? Az [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) használatával konvertálhatja az EMLX fájlformátumot HTML-re. Ezt követően az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API használatával exportálhatja a HTML-t WORDML-be. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API az EMLX WORDML-vé konvertálásához" %}}
1. Nyissa meg az EMLX fájlt a [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message) osztályhivatkozás használatával
2. Alakítsa át az EMLX-t HTML-vé a [Mentés](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) tagfüggvény használatával
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály használatával
4. Mentse a dokumentumot WORDML formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) metódussal, és állítsa be a Wordml-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing WordML as save format
doc->Save(u"convertedFile.WordML");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Elemezze az EMLX fájlt C++ segítségével" %}}
Nemcsak EMLX-jét konvertálhatja WORDML-vé, hanem olvashatja, kezelheti és elemzi az EMLX dokumentumot. Az [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API MapiMessage osztályával az e-mail tárgyára, címére, törzsére és címzettjére vonatkozó információkat kaphat. Például a get_SenderEmlxAddress() tulajdonság használatával ellenőrizheti, hogy van-e egy adott feladó e-mail a konverzióhoz.
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

{{% blocks/products/pf/feature-page-section  h2="C++ API a WORDML fájlformátum szerkesztésének korlátozásához" %}}
Dokumentumvédelmi funkciókat is hozzáadhat az alkalmazáshoz, miközben exportálja a dokumentumot a EMLX címről a WORDML-be. A védelem hozzáadása a dokumentumhoz egy egyszerű folyamat, hiszen mindössze a védelmi módszert kell alkalmaznia a dokumentumra. A védelem típusát ReadOnly értékre állíthatja, hogy korlátozza a felhasználót a dokumentum szerkesztésében.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.WordML");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}