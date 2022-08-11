---
title: Exporter EMLX vers ODT via C++
description: API C++ pour convertir EMLX en ODT sans utiliser Microsoft Word ou Outlook
url: /fr/cpp/conversion/emlx-to-odt/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: ODT
otherformats: PDF DOTX DOC DOT TIFF BMP RTF OTT GIF DOCM PS DOCX XPS WORDML EPUB SVG DOTM PCL JPEG MD PNG TEXT EMF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour exporter EMLX vers ODT" h2="Transformez EMLX en ODT dans une application C++ sans nécessiter Microsoft Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Êtes-vous un développeur C++ cherchant à ajouter des fonctionnalités de conversion d'e-mails dans vos applications ? En utilisant [Aspose.Emlx pour C++](https://products.aspose.com/emlx/cpp/), vous pouvez convertir le format de fichier EMLX en HTML. Après cela, en utilisant l'API [Aspose.Words pour C++](https://products.aspose.com/words/cpp/), vous pouvez exporter du HTML vers ODT. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir EMLX en ODT" %}}
1. Ouvrez le fichier EMLX à l'aide de la référence de classe [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message)
2. Convertissez EMLX en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Enregistrez le document au format ODT à l'aide de la méthode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) et définissez Odt comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Odt as save format
doc->Save(u"convertedFile.Odt");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EMLX via C++" %}}
Non seulement vous pouvez convertir votre EMLX en ODT, mais vous pouvez également lire, manipuler et analyser le document EMLX. Vous pouvez obtenir des informations sur le sujet, l'adresse, le corps et les destinataires de l'e-mail en utilisant la classe MapiMessage de l'API [Aspose.Emlx pour C++](https://products.aspose.com/emlx/cpp/). Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion en utilisant la propriété get_SenderEmlxAddress().
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

{{% blocks/products/pf/feature-page-section  h2="API C++ pour restreindre l'édition du format de fichier ODT" %}}
Vous pouvez également ajouter des fonctionnalités de protection de document dans votre application lors de l'exportation du document d'EMLX vers ODT. L'ajout d'une protection à votre document est un processus simple, car tout ce que vous avez à faire est d'appliquer la méthode de protection à votre document. Vous pouvez définir le type de protection sur Lecture seule pour empêcher l'utilisateur de modifier le document.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Odt");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-pdf/" name="EMLX À PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-dotx/" name="EMLX À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-doc/" name="EMLX À DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-dot/" name="EMLX À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-tiff/" name="EMLX À TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-odt/" name="EMLX À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-rtf/" name="EMLX À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-ott/" name="EMLX À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-gif/" name="EMLX À GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-docm/" name="EMLX À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-ps/" name="EMLX À PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-docx/" name="EMLX À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-xps/" name="EMLX À XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-wordml/" name="EMLX À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-epub/" name="EMLX À EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-svg/" name="EMLX À SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-dotm/" name="EMLX À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-pcl/" name="EMLX À PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-jpeg/" name="EMLX À JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-md/" name="EMLX À MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-png/" name="EMLX À PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-text/" name="EMLX À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-emf/" name="EMLX À EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/emlx-to-flatopc/" name="EMLX À FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}