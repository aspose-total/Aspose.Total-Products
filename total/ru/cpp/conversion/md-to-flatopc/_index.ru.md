---
title: C++ API для экспорта MD в FLATOPC
description: Преобразование MD в FLATOPC в приложениях C++.
url: /ru/cpp/conversion/md-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: FLATOPC
otherformats: MARKDOWN DOTX DOTM MHTML WORDML OTT XAMLFLOW ODT PCL DOCM DOT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для экспорта MD в FLATOPC" h2="Рендеринг MD в FLATOPC в приложениях C++ без использования каких-либо сторонних приложений." >}}

{{% blocks/products/pf/feature-page-summary %}}
Библиотеки автоматизации форматов файлов [Aspose.Total for C++](https://products.aspose.com/total/cpp/) позволяют разработчикам C++ преобразовывать MD в FLATOPC в два простых шага. Во-первых, вы можете использовать API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) для преобразования формата файла MD в DOC. Во-вторых, используя расширенный API обработки документов Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), вы можете экспортировать DOC в FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для рендеринга MD в FLATOPC" %}}
1. Откройте файл MD, используя ссылку на класс [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Преобразуйте MD в DOC с помощью функции-члена [Сохранить](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01).
3. Загрузите файл DOC, используя ссылку на класс [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) API Aspose.Words.
4. Сохраните документ в формате FLATOPC, используя функцию-член [Сохранить](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MD file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.md");
// save MD as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as FlatOpc
wordDoc->Save(u"output.FlatOpc");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Изменить пароль документа MD через C++" %}}
В процессе преобразования MD в FLATOPC вы можете открыть защищенный паролем MD, а также изменить его пароль. Чтобы изменить пароль файла MD, вы должны знать пароль владельца этого документа. Вы можете загрузить PDF-документ, защищенный паролем, с помощью [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), указав его пароль владельца и используя метод ChangePasswords для смены пароля.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing MD Document
auto doc = MakeObject<Document>(L"input.md", L"owner");
// change password of MD Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование файлов FLATOPC через C++" %}}
Вы также можете ограничить редактирование файлов FLATOPC с помощью API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. API позволяет вам контролировать способ ограничения контента с помощью параметра перечисления [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). В следующем примере кода показано, как ограничить редактирование в документе, чтобы было возможно только редактирование в полях формы.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.FlatOpc");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-markdown/" name="MD К MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-dotx/" name="MD К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-dotm/" name="MD К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-mhtml/" name="MD К MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-wordml/" name="MD К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-ott/" name="MD К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-xamlflow/" name="MD К XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-odt/" name="MD К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-pcl/" name="MD К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-flatopc/" name="MD К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-dot/" name="MD К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/md-to-rtf/" name="MD К RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}