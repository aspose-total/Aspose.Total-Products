---
title: C# API для экспорта EMLX в ODT
description: Преобразование EMLX в ODT без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/emlx-to-odt/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: ODT
otherformats: ODT PS TIFF GIF PNG DOTM DOC DOTX OTT PDF DOCX SVG XPS TEXT RTF MD DOCM PCL EMF JPEG FLATOPC DOT WORDML EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EMLX в ODT через .NET" h2=".NET API для преобразования электронной почты в ODT в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EMLX в ODT в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EMLX в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EMLX в ODT" %}}
1. Откройте файл EMLX с помощью класса [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Преобразуйте EMLX в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате ODT с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Odt в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EMLX через .NET" %}}
Перед преобразованием EMLX в ODT, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EMLX, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов ODT через .NET" %}}
При сохранении документа из EMLX в ODT вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EMLX в ODT: примеры использования" %}}
Преобразование файлов формата EMLX в формат ODT позволяет раскрыть полную функциональность возможностей редактирования и совместной работы с контентом. Это преобразование позволяет:

**Использование случаев:**

*   **Совместная работа над документами**: Преобразовать файлы EMLX для совместного редактирования с другими пользователями и отслеживания изменений.  
*   **Переезд контента**: Использовать формат ODT для миграции существующих документов из других форматов, обеспечивая минимальную потерю данных и сохранение форматирования.  
*   **Создание шаблонов**: Преобразовать файлы EMLX для создания персонализированных шаблонов для часто используемых документов, упрощая процесс создания контента.  
*   **Опции экспорта**: Использовать формат ODT для экспорта разметки документа, стилей и графических элементов, предоставляя гибкость в редактировании и повторном использовании контента.  
*   **Интеграция с другими инструментами**: Преобразовать файлы EMLX для интеграции с другими инструментами продуктивности, такими как LibreOffice или Microsoft Office.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}