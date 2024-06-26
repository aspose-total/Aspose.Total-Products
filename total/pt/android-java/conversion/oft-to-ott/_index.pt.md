---
title: Renderize OFT para OTT no aplicativo Andorid
description: Exporte OFT para OTT sem usar o Microsoft Word ou Outlook em seus aplicativos Andorid

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: OTT
otherformats: DOCX WORDML ODT MD FLATOPC DOT EMF TEXT JPEG PDF PCL DOC SVG RTF BMP DOTX GIF PNG PS TIFF XPS DOCM EPUB DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforme OFT em OTT em Aplicativos Andorid" h2="Projetando aplicativos Andorid para exportar OFT para OTT usando Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Os aplicativos Andorid são fáceis de usar para usuários finais diariamente. Dia a dia, o número de usuários de telefones Android está aumentando. Usando as poderosas bibliotecas [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation, você pode desenvolver aplicativos de manipulação e conversão de e-mail. Você pode converter OFT para OTT pela combinação de [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Usando a primeira API, você pode converter o formato de arquivo OFT para HTML e, usando a segunda API, pode renderizar HTML como OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter OFT para OTT em Andorid" %}}
1. Abra o arquivo OFT usando a classe [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Converta OFT para HTML usando [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) método
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato OTT usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e defina OTT como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://releases.aspose.com/total/java/) e instale [Aspose.Oft para Android via Java](https://docs.aspose.com/oft/androidjava/installation/) e [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.OTT
document.save("output.ott", SaveFormat.OTT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}