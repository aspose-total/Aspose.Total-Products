---
title: Renderize EMAIL para JPEG no aplicativo Andorid
description: Exporte EMAIL para JPEG sem usar o Microsoft Word ou Outlook em seus aplicativos Andorid

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: JPEG
otherformats: DOT DOCM DOCX RTF ODT WORDML TIFF DOTM PNG EMF SVG GIF BMP XPS OTT FLATOPC MD TEXT DOTX PDF PCL EPUB PS DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforme EMAIL em JPEG em Aplicativos Andorid" h2="Projetando aplicativos Andorid para exportar EMAIL para JPEG usando Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Os aplicativos Andorid são fáceis de usar para usuários finais diariamente. Dia a dia, o número de usuários de telefones Android está aumentando. Usando as poderosas bibliotecas [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation, você pode desenvolver aplicativos de manipulação e conversão de e-mail. Você pode converter EMAIL para JPEG pela combinação de [Aspose.Email for Android Java](https://products.aspose.com/email/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Usando a primeira API, você pode converter o formato de arquivo EMAIL para HTML e, usando a segunda API, pode renderizar HTML como JPEG. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter EMAIL para JPEG em Andorid" %}}
1. Abra o arquivo EMAIL usando a classe [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converta EMAIL para HTML usando [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) método
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato JPEG usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e defina JPEG como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://releases.aspose.com/total/java/) e instale [Aspose.Email for Android via Java](https://docs.aspose.com/email/androidjava/installation/) e [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.JPEG
document.save("output.jpeg", SaveFormat.JPEG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}