---
title: Renderize EMLX para PNG no aplicativo Andorid
description: Exporte EMLX para PNG sem usar o Microsoft Word ou Outlook em seus aplicativos Andorid
url: /pt/android-java/conversion/emlx-to-png/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: PNG
otherformats: MD TIFF DOCM DOTX OTT TEXT DOC PCL GIF DOTM FLATOPC EMF DOT PDF XPS JPEG BMP RTF WORDML DOCX PS ODT EPUB SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforme EMLX em PNG em Aplicativos Andorid" h2="Projetando aplicativos Andorid para exportar EMLX para PNG usando Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Os aplicativos Andorid são fáceis de usar para usuários finais diariamente. Dia a dia, o número de usuários de telefones Android está aumentando. Usando as poderosas bibliotecas [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation, você pode desenvolver aplicativos de manipulação e conversão de e-mail. Você pode converter EMLX para PNG pela combinação de [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Usando a primeira API, você pode converter o formato de arquivo EMLX para HTML e, usando a segunda API, pode renderizar HTML como PNG. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter EMLX para PNG em Andorid" %}}
1. Abra o arquivo EMLX usando a classe [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Converta EMLX para HTML usando [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions )) método
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato PNG usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e defina PNG como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.Emlx para Android via Java](https://docs.aspose.com/emlx/androidjava/installation/) e [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-md/" name="EMLX Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-tiff/" name="EMLX Para TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-docm/" name="EMLX Para DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-dotx/" name="EMLX Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-ott/" name="EMLX Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-text/" name="EMLX Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-doc/" name="EMLX Para DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-pcl/" name="EMLX Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-gif/" name="EMLX Para GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-dotm/" name="EMLX Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-flatopc/" name="EMLX Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-emf/" name="EMLX Para EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-dot/" name="EMLX Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-pdf/" name="EMLX Para PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-xps/" name="EMLX Para XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-jpeg/" name="EMLX Para JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-png/" name="EMLX Para PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-rtf/" name="EMLX Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-wordml/" name="EMLX Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-docx/" name="EMLX Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-ps/" name="EMLX Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-odt/" name="EMLX Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-epub/" name="EMLX Para EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/emlx-to-svg/" name="EMLX Para SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}