---
title: C# API для экспорта EML в EPUB
description: Преобразование EML в EPUB без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/eml-to-epub/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: EPUB
otherformats: DOCM PCL PNG JPEG TIFF FLATOPC MD DOTM PS DOT DOCX EMF DOC WORDML ODT TEXT EPUB SVG OTT DOTX GIF RTF PDF XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EML в EPUB через .NET" h2=".NET API для преобразования электронной почты в EPUB в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EML в EPUB в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EML в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EML в EPUB" %}}
1. Откройте файл EML с помощью класса [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage).
2. Преобразуйте EML в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате EPUB с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Epub в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EML через .NET" %}}
Перед преобразованием EML в EPUB, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EML, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов EPUB через .NET" %}}
При сохранении документа из EML в EPUB вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EML в EPUB: примеры использования" %}}
Файлы EML (Electronic Mail) предназначены для хранения текстовой информации, что делает их идеальным вариантом для личного переписовки и сотрудничества. Однако при работе со структурированной информацией и содержимым, включающим медиа, форматы EPUB (Electronic Publication) становятся необходимостью для цифровой публикации и распространения.

Преобразование файлов EML в форматы EPUB позволяет раскрыть полную функциональность вашего цифрового контента и возможностей в области издания. Это преобразование позволяет:

**Использование:**

*   **Цифровое издательство**: Преобразовать файлы EML для создания интерактивных цифровых изданий, журналов и newsletters, доступных на различных устройствах.
*   **Создание электронных книг**: Использовать форматы EPUB для преобразования файлов EML в электронные книги, подходящие для чтения на электронных книжках, планшетах и смартфонах.
*   **Опубликование блог-постов**: Преобразовать файлы EML для публикации блог-постов в структурированном формате, что улучшает их обнаружимость и доступность.
*   **Научные статьи**: Использовать форматы EPUB для преобразования файлов EML в научные статьи, которые легко делятся и цитируются.
*   **Совместимое редактирование документов**: Преобразовать файлы EML для создания редактируемых документов, которые можно делиться с другими пользователями, способствуя сотрудничеству и отзывам.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}