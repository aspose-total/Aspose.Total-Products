---
title: C# API для экспорта EMAIL в IMAGE
description: Преобразование EMAIL в IMAGE без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/email-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: WORDML FLATOPC DOCM DOTX TIFF SVG TEXT PS DOT GIF EPUB RTF DOTM JPEG DOCX ODT PDF IMAGE XPS PNG EMF PCL DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EMAIL в IMAGE через .NET" h2=".NET API для преобразования электронной почты в IMAGE в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EMAIL в IMAGE в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EMAIL в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EMAIL в IMAGE" %}}
1. Откройте файл EMAIL с помощью класса [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Преобразуйте EMAIL в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате IMAGE с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Image в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EMAIL через .NET" %}}
Перед преобразованием EMAIL в IMAGE, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EMAIL, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов IMAGE через .NET" %}}
При сохранении документа из EMAIL в IMAGE вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.image", SaveFormat.Image);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EMAIL в IMAGE: примеры использования" %}}
Примерная конверсия email в изображение: раскрытие визуального повествования  

Электронные письма являются эффективным средством для передачи информации, но они уступают по визуальному оформлению другим форматам, таким как изображения.  

Конверсия файлов email в форматы изображений необходима для:  

**Примеры использования:**  

* **Сохранение контента**: Преобразование писем в изображения позволяет зафиксировать информацию, такую как заметки о встречах, договоры продаж или планы проектов, и сделать их доступными для будущего использования.  
* **Захисление бренда**: Использование преобразования писем в изображения позволяет сохранить визуальные элементы компании, такие как логотипы и другие символы бренда, обеспечивая одинакимость по всем каналам коммуникации.  
* **Цифровой архив**: Преобразование писем в изображения помогает создать цифровой архив истории компании, включая важные события, милистоны и процессы принятия решений.  
* **Доступность и включение**: Преобразование писем в изображения делает контент более доступным для пользователей с ограниченными зрительными возможностями или инвалидами, используя описания текста альтернативного типа для предоставления контекста.  
* **Безопасность и соответствие требованиям**: Использование преобразования писем в изображения позволяет защищать конфиденциальную информацию от несанкционированного доступа, соответствуя регуляторным требованиям по защите данных и конфиденциальности.  

Примерная конверсия файлов email в изображения позволяет организациям раскрыть полную потенциал визуального повествования, сохранить информацию и обеспечить соответствие требованиям.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}