---
title: C++ API для экспорта CGM в DOT
description: Преобразование CGM в DOT в приложениях C++.
url: /ru/cpp/conversion/cgm-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: DOT
otherformats: DOTX FLATOPC WORDML DOCM PS DOTM RTF MHTML XAMLFLOW OTT PCL ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для экспорта CGM в DOT" h2="Рендеринг CGM в DOT в приложениях C++ без использования каких-либо сторонних приложений." >}}

{{% blocks/products/pf/feature-page-summary %}}
Библиотеки автоматизации форматов файлов [Aspose.Total for C++](https://products.aspose.com/total/cpp/) позволяют разработчикам C++ преобразовывать CGM в DOT в два простых шага. Во-первых, вы можете использовать API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) для преобразования формата файла CGM в DOC. Во-вторых, используя расширенный API обработки документов Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), вы можете экспортировать DOC в DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для рендеринга CGM в DOT" %}}
1. Откройте файл CGM, используя ссылку на класс [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Преобразуйте CGM в DOC с помощью функции-члена [Сохранить](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01).
3. Загрузите файл DOC, используя ссылку на класс [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) API Aspose.Words.
4. Сохраните документ в формате DOT, используя функцию-член [Сохранить](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load CGM file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.cgm");
// save CGM as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dot
wordDoc->Save(u"output.Dot");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Изменить пароль документа CGM через C++" %}}
В процессе преобразования CGM в DOT вы можете открыть защищенный паролем CGM, а также изменить его пароль. Чтобы изменить пароль файла CGM, вы должны знать пароль владельца этого документа. Вы можете загрузить PDF-документ, защищенный паролем, с помощью [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), указав его пароль владельца и используя метод ChangePasswords для смены пароля.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing CGM Document
auto doc = MakeObject<Document>(L"input.cgm", L"owner");
// change password of CGM Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование файлов DOT через C++" %}}
Вы также можете ограничить редактирование файлов DOT с помощью API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. API позволяет вам контролировать способ ограничения контента с помощью параметра перечисления [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). В следующем примере кода показано, как ограничить редактирование в документе, чтобы было возможно только редактирование в полях формы.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dot");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-dotx/" name="CGM К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-flatopc/" name="CGM К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-wordml/" name="CGM К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-dot/" name="CGM К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-ps/" name="CGM К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-dotm/" name="CGM К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-rtf/" name="CGM К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-mhtml/" name="CGM К MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-xamlflow/" name="CGM К XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-ott/" name="CGM К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-pcl/" name="CGM К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-odt/" name="CGM К ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}