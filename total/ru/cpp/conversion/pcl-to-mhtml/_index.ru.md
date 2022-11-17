---
title: C++ API для экспорта PCL в MHTML
description: Преобразование PCL в MHTML в приложениях C++.

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: MHTML
otherformats: MARKDOWN DOTX XAMLFLOW PS FLATOPC DOTM ODT OTT WORDML RTF DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для экспорта PCL в MHTML" h2="Рендеринг PCL в MHTML в приложениях C++ без использования каких-либо сторонних приложений." >}}

{{% blocks/products/pf/feature-page-summary %}}
Библиотеки автоматизации форматов файлов [Aspose.Total for C++](https://products.aspose.com/total/cpp/) позволяют разработчикам C++ преобразовывать PCL в MHTML в два простых шага. Во-первых, вы можете использовать API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) для преобразования формата файла PCL в DOC. Во-вторых, используя расширенный API обработки документов Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), вы можете экспортировать DOC в MHTML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для рендеринга PCL в MHTML" %}}
1. Откройте файл PCL, используя ссылку на класс [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Преобразуйте PCL в DOC с помощью функции-члена [Сохранить](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01).
3. Загрузите файл DOC, используя ссылку на класс [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) API Aspose.Words.
4. Сохраните документ в формате MHTML, используя функцию-член [Сохранить](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pcl");
// save PCL as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Mhtml
wordDoc->Save(u"output.Mhtml");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Изменить пароль документа PCL через C++" %}}
В процессе преобразования PCL в MHTML вы можете открыть защищенный паролем PCL, а также изменить его пароль. Чтобы изменить пароль файла PCL, вы должны знать пароль владельца этого документа. Вы можете загрузить PDF-документ, защищенный паролем, с помощью [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), указав его пароль владельца и используя метод ChangePasswords для смены пароля.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PCL Document
auto doc = MakeObject<Document>(L"input.pcl", L"owner");
// change password of PCL Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование файлов MHTML через C++" %}}
Вы также можете ограничить редактирование файлов MHTML с помощью API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. API позволяет вам контролировать способ ограничения контента с помощью параметра перечисления [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). В следующем примере кода показано, как ограничить редактирование в документе, чтобы было возможно только редактирование в полях формы.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Mhtml");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-markdown/" name="PCL К MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-dotx/" name="PCL К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-xamlflow/" name="PCL К XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-ps/" name="PCL К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-flatopc/" name="PCL К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-dotm/" name="PCL К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-odt/" name="PCL К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-ott/" name="PCL К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-wordml/" name="PCL К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-rtf/" name="PCL К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-dot/" name="PCL К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pcl-to-mhtml/" name="PCL К MHTML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}