---
title: Экспорт OFT в EMF через C++
description: C++ API для преобразования OFT в EMF без использования Microsoft Word или Outlook

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: EMF
otherformats: BMP GIF RTF WORDML DOTX TEXT DOC ODT DOCX EPUB DOT DOTM PDF TIFF JPEG FLATOPC XPS SVG MD OTT PNG PS DOCM PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для экспорта OFT в EMF" h2="Преобразование OFT в EMF в приложении C++ без использования Microsoft Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы разработчик C++ и хотите добавить функции преобразования электронной почты в свои приложения? Используя [Aspose.Oft для C++](https://products.aspose.com/oft/cpp/), вы можете преобразовать формат файла OFT в HTML. После этого, используя API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), вы можете экспортировать HTML в EMF. Оба API входят в пакет [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования OFT в EMF" %}}
1. Откройте файл OFT, используя ссылку на класс [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message).
2. Преобразуйте OFT в HTML с помощью функции-члена [Сохранить](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Сохраните документ в формате EMF с помощью метода [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) и установите Emf в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Emf as save format
doc->Save(u"convertedFile.Emf");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл OFT через C++" %}}
Вы можете не только конвертировать OFT в EMF, но и читать, манипулировать и анализировать документ OFT. Вы можете получить информацию о теме, адресе, теле и получателях электронной почты, используя класс MapiMessage API [Aspose.Oft для C++](https://products.aspose.com/oft/cpp/). Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство get_SenderOftAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API для ограничения редактирования формата файла EMF" %}}
Вы также можете добавить функции защиты документов в свое приложение при экспорте документа из OFT в EMF. Добавление защиты к вашему документу — это простой процесс, так как все, что вам нужно сделать, это применить метод защиты к вашему документу. Вы можете установить тип защиты ReadOnly, чтобы запретить пользователю редактировать документ.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Emf");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-emf/" name="OFT К EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-gif/" name="OFT К GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-rtf/" name="OFT К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-wordml/" name="OFT К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-dotx/" name="OFT К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-text/" name="OFT К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-doc/" name="OFT К DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-odt/" name="OFT К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-docx/" name="OFT К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-epub/" name="OFT К EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-dot/" name="OFT К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-dotm/" name="OFT К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-pdf/" name="OFT К PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-tiff/" name="OFT К TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-jpeg/" name="OFT К JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-flatopc/" name="OFT К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-xps/" name="OFT К XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-svg/" name="OFT К SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-md/" name="OFT К MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-ott/" name="OFT К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-png/" name="OFT К PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-ps/" name="OFT К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-docm/" name="OFT К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/oft-to-pcl/" name="OFT К PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}