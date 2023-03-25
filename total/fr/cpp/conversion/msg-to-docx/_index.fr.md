---
title: Exporter MSG vers DOCX via C++
description: API C++ pour convertir MSG en DOCX sans utiliser Microsoft Word ou Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOCX
otherformats: SVG RTF PNG BMP DOT DOCM DOTM WORDML TIFF PS TEXT EPUB EMF PCL OTT ODT GIF PDF FLATOPC MD JPEG DOC XPS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour exporter MSG vers DOCX" h2="Transformez MSG en DOCX dans une application C++ sans nécessiter Microsoft Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Êtes-vous un développeur C++ cherchant à ajouter des fonctionnalités de conversion d'e-mails dans vos applications ? En utilisant [Aspose.Msg pour C++](https://products.aspose.com/msg/cpp/), vous pouvez convertir le format de fichier MSG en HTML. Après cela, en utilisant l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez exporter du HTML vers DOCX. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir MSG en DOCX" %}}
1. Ouvrez le fichier MSG à l'aide de la référence de classe [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message)
2. Convertissez MSG en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Enregistrez le document au format DOCX à l'aide de la méthode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) et définissez Docx comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Docx as save format
doc->Save(u"convertedFile.Docx");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier MSG via C++" %}}
Non seulement vous pouvez convertir votre MSG en DOCX, mais vous pouvez également lire, manipuler et analyser le document MSG. Vous pouvez obtenir des informations sur le sujet, l'adresse, le corps et les destinataires de l'e-mail en utilisant la classe MapiMessage de l'API [Aspose.Msg pour C++](https://products.aspose.com/msg/cpp/). Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion en utilisant la propriété get_SenderMsgAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderMsgAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="API C++ pour restreindre l'édition du format de fichier DOCX" %}}
Vous pouvez également ajouter des fonctionnalités de protection de document dans votre application lors de l'exportation du document d'MSG vers DOCX. L'ajout d'une protection à votre document est un processus simple, car tout ce que vous avez à faire est d'appliquer la méthode de protection à votre document. Vous pouvez définir le type de protection sur Lecture seule pour empêcher l'utilisateur de modifier le document.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Docx");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}