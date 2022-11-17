---
title: Renderize EML para BMP no aplicativo Andorid
description: Exporte EML para BMP sem usar o Microsoft Word ou Outlook em seus aplicativos Andorid

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: BMP
otherformats: PDF TIFF ODT DOTX WORDML DOCX TEXT RTF DOTM EMF DOC OTT FLATOPC PNG EPUB DOCM PCL JPEG MD GIF DOT XPS PS SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforme EML em BMP em Aplicativos Andorid" h2="Projetando aplicativos Andorid para exportar EML para BMP usando Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Os aplicativos Andorid são fáceis de usar para usuários finais diariamente. Dia a dia, o número de usuários de telefones Android está aumentando. Usando as poderosas bibliotecas [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation, você pode desenvolver aplicativos de manipulação e conversão de e-mail. Você pode converter EML para BMP pela combinação de [Aspose.Eml for Android Java](https://products.aspose.com/eml/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Usando a primeira API, você pode converter o formato de arquivo EML para HTML e, usando a segunda API, pode renderizar HTML como BMP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter EML para BMP em Andorid" %}}
1. Abra o arquivo EML usando a classe [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Converta EML para HTML usando [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions )) método
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato BMP usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e defina BMP como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.Eml para Android via Java](https://docs.aspose.com/eml/androidjava/installation/) e [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.BMP
document.save("output.bmp", SaveFormat.BMP); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-pdf/" name="EML Para PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-tiff/" name="EML Para TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-odt/" name="EML Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-dotx/" name="EML Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-wordml/" name="EML Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-docx/" name="EML Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-text/" name="EML Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-rtf/" name="EML Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-dotm/" name="EML Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-emf/" name="EML Para EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-doc/" name="EML Para DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-ott/" name="EML Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-flatopc/" name="EML Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-png/" name="EML Para PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-epub/" name="EML Para EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-docm/" name="EML Para DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-pcl/" name="EML Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-jpeg/" name="EML Para JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-md/" name="EML Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-gif/" name="EML Para GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-dot/" name="EML Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-xps/" name="EML Para XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-ps/" name="EML Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/eml-to-svg/" name="EML Para SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}