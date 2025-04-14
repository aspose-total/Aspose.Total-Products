---
title: C# API для экспорта EML в MD
description: Преобразование EML в MD без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/eml-to-md/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: MD
otherformats: MD RTF FLATOPC PS ODT DOCM DOTX EMF GIF XPS WORDML OTT DOCX TIFF PNG SVG TEXT JPEG EPUB DOC PCL DOT PDF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EML в MD через .NET" h2=".NET API для преобразования электронной почты в MD в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EML в MD в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EML в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в MD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EML в MD" %}}
1. Откройте файл EML с помощью класса [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage).
2. Преобразуйте EML в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате MD с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Md в качестве формата сохранения.
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

document.Save("output.md", SaveFormat.Md); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EML через .NET" %}}
Перед преобразованием EML в MD, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EML, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов MD через .NET" %}}
При сохранении документа из EML в MD вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.md", SaveFormat.Md);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EML в MD: примеры использования" %}}
Файлы EML (Electronic Mail) используются для хранения текстовой информации, что делает их идеальным для создания простых писем и коммуникации. Однако при работе с сложной данными и визуализациями форматы Markdown (MD) становятся необходимыми для документирования и представления.

Перевёртка файлов EML в форматы Markdown необходима, чтобы раскрыть полные возможности вашей способности к документированию и созданию презентаций. Это позволяет:

**Используемые случаи:**

* **Документирование писем**: Перевёртка файлов EML создаёт читаемую документацию для писем, включая заголовки, подписи и содержимое.
* **Создание блог-постов**: Используйте Markdown для написания и форматирования постов в блоге, что упрощает деление на авторов.
* **Техническая работа**: Перевёртка файлов EML создаёт пользовательские руководства, инструкции и указания в четкой и краткой форме.
* **Социальные сети**: Форматируйте социальные сети, включая изображения, ссылки и видео, для лучшего взаимодействия и видимости.
* **Презентации и отчеты**: Перевёртка файлов EML позволяет создать интерактивные презентации и отчеты с использованием синтаксиса Markdown, что упрощает деление между стейкхолдерами.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}