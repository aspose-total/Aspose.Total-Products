---
title: Экспорт EML в DOCX через C++
description: C++ API для преобразования EML в DOCX без использования Microsoft Word или Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: DOCX
otherformats: TEXT WORDML PDF SVG ODT DOTM DOT MD XPS TIFF DOCM JPEG PNG PS BMP GIF PCL RTF EPUB OTT EMF FLATOPC DOC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для экспорта EML в DOCX" h2="Преобразование EML в DOCX в приложении C++ без использования Microsoft Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы разработчик C++ и хотите добавить функции преобразования электронной почты в свои приложения? Используя [Aspose.Eml для C++](https://products.aspose.com/eml/cpp/), вы можете преобразовать формат файла EML в HTML. После этого, используя API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), вы можете экспортировать HTML в DOCX. Оба API входят в пакет [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования EML в DOCX" %}}
1. Откройте файл EML, используя ссылку на класс [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message).
2. Преобразуйте EML в HTML с помощью функции-члена [Сохранить](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Сохраните документ в формате DOCX с помощью метода [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) и установите Docx в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Docx as save format
doc->Save(u"convertedFile.Docx");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EML через C++" %}}
Вы можете не только конвертировать EML в DOCX, но и читать, манипулировать и анализировать документ EML. Вы можете получить информацию о теме, адресе, теле и получателях электронной почты, используя класс MapiMessage API [Aspose.Eml для C++](https://products.aspose.com/eml/cpp/). Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство get_SenderEmlAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API для ограничения редактирования формата файла DOCX" %}}
Вы также можете добавить функции защиты документов в свое приложение при экспорте документа из EML в DOCX. Добавление защиты к вашему документу — это простой процесс, так как все, что вам нужно сделать, это применить метод защиты к вашему документу. Вы можете установить тип защиты ReadOnly, чтобы запретить пользователю редактировать документ.
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
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-text/" name="EML К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-wordml/" name="EML К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-pdf/" name="EML К PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-svg/" name="EML К SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-odt/" name="EML К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-dotm/" name="EML К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-dot/" name="EML К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-md/" name="EML К MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-xps/" name="EML К XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-tiff/" name="EML К TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-docm/" name="EML К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-jpeg/" name="EML К JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-png/" name="EML К PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-ps/" name="EML К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-docx/" name="EML К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-gif/" name="EML К GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-pcl/" name="EML К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-rtf/" name="EML К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-epub/" name="EML К EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-ott/" name="EML К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-emf/" name="EML К EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-flatopc/" name="EML К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-doc/" name="EML К DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/eml-to-dotx/" name="EML К DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}