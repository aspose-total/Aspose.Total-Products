---
title: C# API для экспорта EML в OTT
description: Преобразование EML в OTT без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/eml-to-ott/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: OTT
otherformats: EPUB TEXT MD WORDML ODT GIF EMF SVG DOCX PCL DOTM FLATOPC DOC PS PDF XPS RTF DOCM DOT TIFF DOTX OTT PNG JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EML в OTT через .NET" h2=".NET API для преобразования электронной почты в OTT в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EML в OTT в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EML в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в OTT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EML в OTT" %}}
1. Откройте файл EML с помощью класса [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage).
2. Преобразуйте EML в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате OTT с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Ott в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EML через .NET" %}}
Перед преобразованием EML в OTT, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EML, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов OTT через .NET" %}}
При сохранении документа из EML в OTT вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EML в OTT: примеры использования" %}}
Конвертация файлов EML в форматы OTT (Office Template) необходима для раскрытия полной функциональности вашего документа редактирования и настройки. Эта конвертация позволяет:

**Использование случаев:**

*   **Автоматизированное生成 отчетов**: Преобразование файлов EML в создаваемые шаблоны для автоматизированного generation отчетов, упрощение задач для команд администраторов.  
*   **Стандартизация документа редактирования**: Использование форматов OTT для стандартизации разметки документа, что делает его проще для сотрудничества и просмотра в пределах организации.  
*   **Оптимизация шаблонов маркетинга**: Преобразование файлов EML для оптимизации дизайнов шаблонов маркетинга, сокращение времени на повторяющиеся работы дизайна и ускорение создания контента.  
*   **Управление предложениями и контрактами**: Использование форматов OTT для создания настраиваемых шаблонов предложений и контрактов, снижение ошибок и повышение эффективности в процессе просмотра документов.  
*   **Создание шаблонов внутренней коммуникации**: Преобразование файлов EML для создания шаблонов внутренней коммуникации для объявлений компании, сокращение необходимости повторяющихся работ по дизайну.  

Конвертация файлов EML в форматы OTT позволяет раскрыть ряд преимуществ, которые повышают эффективность вашего workflow, продуктивность и общую производительность.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}