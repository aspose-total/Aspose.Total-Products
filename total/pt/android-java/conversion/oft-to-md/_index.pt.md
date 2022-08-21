---
title: Renderize OFT para MD no aplicativo Andorid
description: Exporte OFT para MD sem usar o Microsoft Word ou Outlook em seus aplicativos Andorid
url: /pt/android-java/conversion/oft-to-md/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: MD
otherformats: PNG EPUB DOTX EMF GIF PS PCL XPS PDF RTF DOCX ODT SVG TEXT JPEG WORDML BMP DOCM DOT DOTM DOC FLATOPC TIFF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforme OFT em MD em Aplicativos Andorid" h2="Projetando aplicativos Andorid para exportar OFT para MD usando Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Os aplicativos Andorid são fáceis de usar para usuários finais diariamente. Dia a dia, o número de usuários de telefones Android está aumentando. Usando as poderosas bibliotecas [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation, você pode desenvolver aplicativos de manipulação e conversão de e-mail. Você pode converter OFT para MD pela combinação de [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Usando a primeira API, você pode converter o formato de arquivo OFT para HTML e, usando a segunda API, pode renderizar HTML como MD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter OFT para MD em Andorid" %}}
1. Abra o arquivo OFT usando a classe [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Converta OFT para HTML usando [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) método
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato MD usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e defina MD como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.Oft para Android via Java](https://docs.aspose.com/oft/androidjava/installation/) e [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.MD
document.save("output.md", SaveFormat.MD); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-png/" name="OFT Para PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-epub/" name="OFT Para EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-dotx/" name="OFT Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-emf/" name="OFT Para EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-gif/" name="OFT Para GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-ps/" name="OFT Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-pcl/" name="OFT Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-xps/" name="OFT Para XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-pdf/" name="OFT Para PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-rtf/" name="OFT Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-docx/" name="OFT Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-odt/" name="OFT Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-svg/" name="OFT Para SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-text/" name="OFT Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-jpeg/" name="OFT Para JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-wordml/" name="OFT Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-md/" name="OFT Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-docm/" name="OFT Para DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-dot/" name="OFT Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-dotm/" name="OFT Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-doc/" name="OFT Para DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-flatopc/" name="OFT Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-tiff/" name="OFT Para TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/oft-to-ott/" name="OFT Para OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}