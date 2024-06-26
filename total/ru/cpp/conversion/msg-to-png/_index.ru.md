---
title: Экспорт MSG в PNG через C++
description: C++ API для преобразования MSG в PNG без использования Microsoft Word или Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOTX RTF DOCX DOC TEXT DOTM FLATOPC DOT DOCM TIFF GIF XPS EMF WORDML PS EPUB ODT SVG PDF PCL MD OTT BMP JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для экспорта MSG в PNG" h2="Преобразование MSG в PNG в приложении C++ без использования Microsoft Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы разработчик C++ и хотите добавить функции преобразования электронной почты в свои приложения? Используя [Aspose.Msg для C++](https://products.aspose.com/msg/cpp/), вы можете преобразовать формат файла MSG в HTML. После этого, используя API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), вы можете экспортировать HTML в PNG. Оба API входят в пакет [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования MSG в PNG" %}}
1. Откройте файл MSG, используя ссылку на класс [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message).
2. Преобразуйте MSG в HTML с помощью функции-члена [Save](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Сохраните документ в формате PNG с помощью метода [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) и установите Png в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл MSG через C++" %}}
Вы можете не только конвертировать MSG в PNG, но и читать, манипулировать и анализировать документ MSG. Вы можете получить информацию о теме, адресе, теле и получателях электронной почты, используя класс MapiMessage API [Aspose.Msg для C++](https://products.aspose.com/msg/cpp/). Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство get_SenderMsgAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API для ограничения редактирования формата файла PNG" %}}
Вы также можете добавить функции защиты документов в свое приложение при экспорте документа из MSG в PNG. Добавление защиты к вашему документу — это простой процесс, так как все, что вам нужно сделать, это применить метод защиты к вашему документу. Вы можете установить тип защиты ReadOnly, чтобы запретить пользователю редактировать документ.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Png");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}