---
title: C# API для экспорта PS в RTF
description: Преобразование PS в RTF без использования Microsoft Word
url_ignore: /ru/net/conversion/ps-to-rtf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: RTF
otherformats: DOTM ODT PCL FLATOPC OTT DOT DOTX WORDML MHTML MARKDOWN XAMLFLOW RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг PS в RTF через .NET" h2=".NET API для экспорта PS в RTF в Windows, macOS и Linux без использования Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) — это мощный API для добавления функций обработки и преобразования документов в ваше приложение .NET. Используя расширенный API обработки PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файлов PS в DOC. После этого, используя мощный API обработки документов [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать DOC в RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования PS в RTF" %}}
1. Откройте файл PS, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте PS в Doc, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл Doc с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document) Aspose.Words.
4. Сохраните документ в формате RTF с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Rtf как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Расшифровать файл PS с помощью пароля владельца через .NET" %}}
Перед преобразованием PS в RTF, если вы хотите расшифровать свой документ, вы можете сделать это с помощью API. Чтобы расшифровать файл PDF, сначала необходимо создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть PS, используя пароль владельца. После этого необходимо вызвать метод [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) объекта Document. Наконец, сохраните обновленный файл, используя метод Save объекта Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать RTF-файл только для чтения через .NET" %}}
Чтобы защитить ваш RTF от редактирования и предотвратить редактирование важной и конфиденциальной информации в вашем документе другими людьми, вы также можете установить защиту документа с помощью API. Вы можете ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это можно сделать с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Это позволяет вам контролировать способ ограничения контента с помощью параметра перечисления [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла PS в RTF: примеры использования" %}}
**Файлы PS (Portable Document Format)** используются для хранения информации в документах, что делает их идеальным выбором для создания профессионально выглядящих документов и презентаций. Однако при работе с содержимым мультимедийного типа файлы RTF (Rich Text Format) становятся необходимостью для редактирования текста и форматирования.

Преобразование файлов PS в форматы RTF позволяет раскрыть полную функциональность вашего текстового форматирования и редактирования. Это позволяет:

**Сценарии применения:**

*   **Редактирование документов**: Преобразовать файлы PS для редактирования текста, макета и форматирования в более интуитивном понимании способе.  
*   **Создание PDF**: Использовать RTF для создания профессионально выглядящих документов PDF с точным отображением шрифтов и расположением.  
*   **Импорт текста**: Преобразовать файлы PS для импорта больших объемов текстового содержимого в другие приложения для эффективного редактирования.  
*   **Захесление документа**: Использовать RTF для сохранения форматирования документа, включая шрифты, пробелы и выравнивание, при его обмене и совместной работе.  
*   **Улучшение совместимости**: Преобразовать файлы PS для улучшения совместимости с разными приложениями и платформами, обеспечивая безмятежный обмен документами.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}