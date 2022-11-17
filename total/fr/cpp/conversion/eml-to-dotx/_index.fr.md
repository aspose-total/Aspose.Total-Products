---
title: Exporter EML vers DOTX via C++
description: API C++ pour convertir EML en DOTX sans utiliser Microsoft Word ou Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: DOTX
otherformats: BMP GIF EMF PDF JPEG PNG ODT TIFF DOTM PS DOC DOT MD FLATOPC TEXT RTF DOCX PCL DOCM WORDML OTT EPUB XPS SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour exporter EML vers DOTX" h2="Transformez EML en DOTX dans une application C++ sans nécessiter Microsoft Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Êtes-vous un développeur C++ cherchant à ajouter des fonctionnalités de conversion d'e-mails dans vos applications ? En utilisant [Aspose.Eml pour C++](https://products.aspose.com/eml/cpp/), vous pouvez convertir le format de fichier EML en HTML. Après cela, en utilisant l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez exporter du HTML vers DOTX. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir EML en DOTX" %}}
1. Ouvrez le fichier EML à l'aide de la référence de classe [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Convertissez EML en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Enregistrez le document au format DOTX à l'aide de la méthode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) et définissez Dotx comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Dotx as save format
doc->Save(u"convertedFile.Dotx");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EML via C++" %}}
Non seulement vous pouvez convertir votre EML en DOTX, mais vous pouvez également lire, manipuler et analyser le document EML. Vous pouvez obtenir des informations sur le sujet, l'adresse, le corps et les destinataires de l'e-mail en utilisant la classe MapiMessage de l'API [Aspose.Eml pour C++](https://products.aspose.com/eml/cpp/). Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion en utilisant la propriété get_SenderEmlAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="API C++ pour restreindre l'édition du format de fichier DOTX" %}}
Vous pouvez également ajouter des fonctionnalités de protection de document dans votre application lors de l'exportation du document d'EML vers DOTX. L'ajout d'une protection à votre document est un processus simple, car tout ce que vous avez à faire est d'appliquer la méthode de protection à votre document. Vous pouvez définir le type de protection sur Lecture seule pour empêcher l'utilisateur de modifier le document.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Dotx");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-dotx/" name="EML À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-gif/" name="EML À GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-emf/" name="EML À EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-pdf/" name="EML À PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-jpeg/" name="EML À JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-png/" name="EML À PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-odt/" name="EML À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-tiff/" name="EML À TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-dotm/" name="EML À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-ps/" name="EML À PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-doc/" name="EML À DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-dot/" name="EML À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-md/" name="EML À MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-flatopc/" name="EML À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-text/" name="EML À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-rtf/" name="EML À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-docx/" name="EML À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-pcl/" name="EML À PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-docm/" name="EML À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-wordml/" name="EML À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-ott/" name="EML À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-epub/" name="EML À EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-xps/" name="EML À XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/eml-to-svg/" name="EML À SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}