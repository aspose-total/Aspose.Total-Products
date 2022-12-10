---
title: Exporter EMAIL vers DOTM via C++
description: API C++ pour convertir EMAIL en DOTM sans utiliser Microsoft Word ou Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOTM
otherformats: JPEG WORDML RTF TIFF BMP OTT TEXT SVG ODT EPUB DOT DOCM EMF GIF PS MD DOCX FLATOPC PCL DOTX PNG DOC PDF XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour exporter EMAIL vers DOTM" h2="Transformez EMAIL en DOTM dans une application C++ sans nécessiter Microsoft Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Êtes-vous un développeur C++ cherchant à ajouter des fonctionnalités de conversion d'e-mails dans vos applications ? En utilisant [Aspose.Email for C++](https://products.aspose.com/email/cpp/), vous pouvez convertir le format de fichier EMAIL en HTML. Après cela, en utilisant l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez exporter du HTML vers DOTM. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir EMAIL en DOTM" %}}
1. Ouvrez le fichier EMAIL à l'aide de la référence de classe [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message)
2. Convertissez EMAIL en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Enregistrez le document au format DOTM à l'aide de la méthode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) et définissez Dotm comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Dotm as save format
doc->Save(u"convertedFile.Dotm");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EMAIL via C++" %}}
Non seulement vous pouvez convertir votre EMAIL en DOTM, mais vous pouvez également lire, manipuler et analyser le document EMAIL. Vous pouvez obtenir des informations sur le sujet, l'adresse, le corps et les destinataires de l'e-mail en utilisant la classe MapiMessage de l'API [Aspose.Email for C++](https://products.aspose.com/email/cpp/). Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion en utilisant la propriété get_SenderEmailAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmailAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="API C++ pour restreindre l'édition du format de fichier DOTM" %}}
Vous pouvez également ajouter des fonctionnalités de protection de document dans votre application lors de l'exportation du document d'EMAIL vers DOTM. L'ajout d'une protection à votre document est un processus simple, car tout ce que vous avez à faire est d'appliquer la méthode de protection à votre document. Vous pouvez définir le type de protection sur Lecture seule pour empêcher l'utilisateur de modifier le document.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Dotm");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-jpeg/" name="MSG À JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-wordml/" name="MSG À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-rtf/" name="MSG À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-tiff/" name="MSG À TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-dotm/" name="MSG À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-ott/" name="MSG À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-text/" name="MSG À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-svg/" name="MSG À SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-odt/" name="MSG À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-epub/" name="MSG À EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-dot/" name="MSG À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-docm/" name="MSG À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-emf/" name="MSG À EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-gif/" name="MSG À GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-ps/" name="MSG À PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-md/" name="MSG À MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-docx/" name="MSG À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-flatopc/" name="MSG À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-pcl/" name="MSG À PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-dotx/" name="MSG À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-png/" name="MSG À PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-doc/" name="MSG À DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-pdf/" name="MSG À PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/msg-to-xps/" name="MSG À XPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}