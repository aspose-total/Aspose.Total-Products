---
title: C# API для экспорта EMAIL в PCL
description: Преобразование EMAIL в PCL без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/email-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PCL
otherformats: DOTX EPUB ODT RTF GIF DOCX FLATOPC DOC TIFF JPEG EMF SVG PS PCL MD DOT PDF OTT PNG TEXT DOCM XPS WORDML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EMAIL в PCL через .NET" h2=".NET API для преобразования электронной почты в PCL в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EMAIL в PCL в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EMAIL в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EMAIL в PCL" %}}
1. Откройте файл EMAIL с помощью класса [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Преобразуйте EMAIL в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате PCL с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Pcl в качестве формата сохранения.
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

document.Save("output.pcl", SaveFormat.Pcl); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EMAIL через .NET" %}}
Перед преобразованием EMAIL в PCL, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EMAIL, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов PCL через .NET" %}}
При сохранении документа из EMAIL в PCL вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EMAIL в PCL: примеры использования" %}}
Преобразование файлов электронной почты в форматы PCL (Язык управления принтером) является необходимым шагом для раскрытия полной потенциалитеты своих возможностей в области печати.

Этот процесс преобразования позволяет:

**Использования:**

*   **Автоматизированное расписание печати документов**: Преобразование файлов электронной почты позволяет автоматически планировать печать, что обеспечивает то, чтобы документы печатались вовремя и снижает количество усилий, требуемых для выполнения руцовых действий.
*   **Настройка персонализированной печати**: Использование форматов PCL позволяет применять настроения печати, такие как размер бумаги, ориентация и стили шрифтов, что улучшает опыт печати.
*   **Действительное мониторинг печати**: Преобразование файлов электронной почты в форматы PCL позволяет реализовать системы мониторинга печати на уровне реального времени, что обеспечивает мгновенный контроль за печатными задачами и оптимизацию ресурсов принтера.
*   **Безопасная печать документов**: Использование форматов PCL позволяет внедрять функции защиты информации, такие как шифрование и аутентификация, что обеспечивает защиту конфиденциальной информации.
*   **Оптимизация рабочего процесса печати**: Преобразование файлов электронной почты в форматы PCL позволяет упростить процесс подготовки к печати, снижая время, затраченное на руцовые действия, и увеличивая продуктивность.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}