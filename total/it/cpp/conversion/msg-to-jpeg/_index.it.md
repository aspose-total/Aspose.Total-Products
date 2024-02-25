---
title: Esporta MSG in JPEG tramite C++
description: API C++ per convertire MSG in JPEG senza utilizzare Microsoft Word o Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: JPEG
otherformats: DOCX PS TIFF XPS DOT FLATOPC PDF WORDML ODT DOC DOCM SVG PNG GIF DOTM BMP TEXT RTF MD PCL EPUB DOTX EMF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per esportare MSG in JPEG" h2="Trasforma MSG in JPEG all'interno dell'applicazione C++ senza richiedere Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sei uno sviluppatore C++ e stai cercando di aggiungere funzionalità di conversione e-mail all'interno delle tue applicazioni? Usando [Aspose.Msg per C++](https://products.aspose.com/msg/cpp/) puoi convertire il formato del file MSG in HTML. Successivamente, utilizzando l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare HTML in JPEG. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire MSG in JPEG" %}}
1. Aprire il file MSG utilizzando il riferimento alla classe [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message)
2. Converti MSG in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Carica HTML utilizzando la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salvare il documento in formato JPEG utilizzando il metodo [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) e impostare Jpeg come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Jpeg as save format
doc->Save(u"convertedFile.Jpeg");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file MSG tramite C++" %}}
Non solo puoi convertire la tua MSG in JPEG, ma puoi leggere, manipolare e analizzare il documento MSG. È possibile ottenere informazioni su oggetto, indirizzo, corpo e destinatari dell'e-mail utilizzando la classe MapiMessage dell'API [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/). Ad esempio, puoi verificare la presenza di un'e-mail del mittente specifica per la conversione utilizzando la proprietà get_SenderMsgAddress().
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

{{% blocks/products/pf/feature-page-section  h2="API C++ per limitare la modifica del formato file JPEG" %}}
Puoi anche aggiungere funzionalità di protezione dei documenti nella tua app durante l'esportazione del documento da MSG a JPEG. L'aggiunta della protezione al tuo documento è un processo semplice, poiché tutto ciò che devi fare è applicare il metodo di protezione al tuo documento. È possibile impostare il tipo di protezione su Sola lettura per limitare la modifica del documento da parte dell'utente.
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}