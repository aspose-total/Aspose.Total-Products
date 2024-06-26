---
title: Экспорт EMLX в ODT через C++
description: C++ API для преобразования EMLX в ODT без использования Microsoft Word или Outlook

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: ODT
otherformats: PDF DOTX DOC DOT TIFF BMP RTF OTT GIF DOCM PS DOCX XPS WORDML EPUB SVG DOTM PCL JPEG MD PNG TEXT EMF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для экспорта EMLX в ODT" h2="Преобразование EMLX в ODT в приложении C++ без использования Microsoft Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы разработчик C++ и хотите добавить функции преобразования электронной почты в свои приложения? Используя [Aspose.Emlx для C++](https://products.aspose.com/emlx/cpp/), вы можете преобразовать формат файла EMLX в HTML. После этого, используя API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), вы можете экспортировать HTML в ODT. Оба API входят в пакет [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования EMLX в ODT" %}}
1. Откройте файл EMLX, используя ссылку на класс [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message).
2. Преобразуйте EMLX в HTML с помощью функции-члена [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Сохраните документ в формате ODT с помощью метода [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) и установите Odt в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.comtotal/cpp).
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

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EMLX через C++" %}}
Вы можете не только конвертировать EMLX в ODT, но и читать, манипулировать и анализировать документ EMLX. Вы можете получить информацию о теме, адресе, теле и получателях электронной почты, используя класс MapiMessage API [Aspose.Emlx для C++](https://products.aspose.com/emlx/cpp/). Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство get_SenderEmlxAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API для ограничения редактирования формата файла ODT" %}}
Вы также можете добавить функции защиты документов в свое приложение при экспорте документа из EMLX в ODT. Добавление защиты к вашему документу — это простой процесс, так как все, что вам нужно сделать, это применить метод защиты к вашему документу. Вы можете установить тип защиты ReadOnly, чтобы запретить пользователю редактировать документ.
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}